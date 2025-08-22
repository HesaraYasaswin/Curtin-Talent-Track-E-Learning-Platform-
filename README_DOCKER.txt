# CurtinTalentTrack – Dockerized Setup Guide

## Prerequisites:
- Docker Desktop installed and running
- Git (optional)

## How to Run the App

1. Open Docker Desktop
2. In terminal, go to the project folder
3. Run the following:

   docker-compose build
   docker-compose up

4. Access the system at:
   - Frontend: http://localhost:5173
   - Backend API: http://localhost:5000

## Notes:
- MongoDB data will persist using Docker volumes
- Uploaded files will be stored in the `uploads/` folder
- You can shut down with: `docker-compose down`
