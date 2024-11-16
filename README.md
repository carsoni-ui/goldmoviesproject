# goldmoviesproject

A full-stack movie review application with a React frontend and a Spring Boot backend. Allows users to browse movies, watch trailers, and post reviews.

---

## Project Structure

goldmoviesproject/ 
  ├── frontend/ # React application 
  ├── backend/ # Spring Boot application


---

## How to Run the Project

### Backend
1. Navigate to the `backend` folder:
   ```bash
   cd backend
2. Run Command:
   ```bash
   mvn spring-boot:run
3. Next, Run Command:
   ```bash
   ngrok http 8080
4. Finally, Copy and paste the generated Forwarding URL into the base URL variable located in goldmoviesproject\Frontend\movie-gold-v1\src\api\axiosConfig.js
   ```bash
   Example URL: https://8bb2-207-196-181-78.ngrok-free.app
   
### Frontend
1. Navigate to the `frontend` folder:
    ```bash
    cd frontend
2. Install dependencies:
    ```bash
    npm install
3. Start the `frontend` application:
   ```bash
   npm start

---

### MUST COMPLETE BACKEND AND FRONTEND STEPS TO RUN PROPERLY

