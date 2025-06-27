# DailyServiceReportSystem-
Daily Service Report System 



backend/ – Spring Boot Folder Structure


backend/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── yourcompany/
│   │   │           └── appname/
│   │   │               ├── Application.java
│   │   │               ├── config/
│   │   │               │   └── CorsConfig.java
│   │   │               ├── controller/
│   │   │               │   └── UserController.java
│   │   │               ├── service/
│   │   │               │   └── UserService.java
│   │   │               ├── model/
│   │   │               │   └── User.java
│   │   │               └── repository/
│   │   │                   └── UserRepository.java
│   │   └── resources/
│   │       ├── application.yml
│   │       └── static/      <-- For serving static files (e.g. frontend build)
├── pom.xml


-------------------------------------------------------------------------------------------------

frontend/ – React App Folder Structure

frontend/
├── public/
│   └── index.html
├── src/
│   ├── api/                  <-- Axios calls, API services
│   │   └── userApi.js
│   ├── components/           <-- Reusable components (Button, Input, etc.)
│   ├── pages/                <-- Views like Dashboard, Login, etc.
│   ├── context/              <-- Global state (React Context/Redux)
│   ├── hooks/                <-- Custom React hooks
│   ├── utils/                <-- Helper functions
│   ├── App.js
│   ├── index.js
│   └── styles/               <-- CSS, Tailwind, Sass
│       └── main.css
├── .env
├── package.json
