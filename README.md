# Voice-Transcriber

**Voice-Transcriber** is a Spring Boot backend service that allows users to upload audio files and receive transcribed text.  
It can be used as a standalone REST API or together with the Front-End project.

---

## Features

- Upload audio files
- Process audio and return transcription
- User authentication (registration & login)
- Role-based access control
- CRUD operations for users and notes

---

## Tech Stack

- **Java 17**
- **Spring Boot**
- **Spring Security**
- **MongoDB**
- **Gradle**
- **REST API**

---

## Run Locally

### 1. Clone the repository
```bash
1. Copy the repository URL from GitHub:  
2. Open your terminal (Git Bash, PowerShell, CMD, or VS Code Terminal).  
3. Navigate to the folder where you want to store the project:  
cd "C:\Users\YourName\Desktop"
mkdir my-projects
cd my-projects
git clone https://github.com/nazarbokalo/Voice-Transcriber
```

### 2. Configure environment variables
```bash
SPRING_DATA_MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

### 3. Build the project
```bash
./gradlew build
```

### 4. Run the application
Backend will start at: http://localhost:8080




