# Meet Sync  

Meet Sync is a web application designed to help users summarize their meetings efficiently. The project is divided into two parts: a backend and a frontend.  

## Features  
- Upload meeting recordings for summarization.  
- Process audio files using FFmpeg for optimal handling.  
- Seamlessly hosted frontend and backend for user accessibility.  

## Project Structure  
### Frontend  
- Built using **React** for an interactive user interface.  
- Hosted on the Railway platform.  
- GitHub repository: [Meet Sync Frontend](https://github.com/ankit14-dev/Meet-Sync.git)  
- Hosted URL: [Meet Sync Frontend on Railway](https://meet-sync-production.up.railway.app/)  

### Backend  
- Built using **Node.js** and **Express** for efficient server-side operations.  
- Utilizes **FFmpeg** for audio processing and **Multer** for file handling.  
- Hosted on AWS.  
- GitHub repository: [Meet Sync Backend](https://github.com/ankit14-dev/Meet-Sync-Backend.git)  
- Hosted URL: `http://13.201.188.161:5000/`  

## How to Use  
1. Visit the hosted frontend URL: [Meet Sync Frontend](https://meet-sync-production.up.railway.app/).  
2. Upload your meeting recording using the provided interface.  
3. The backend processes the audio file, and a summarized version of the meeting will be generated.  

## Getting Started (For Local Development)  
### Frontend  
1. Clone the frontend repository:  
   ```bash  
   git clone https://github.com/ankit14-dev/Meet-Sync.git  
   cd Meet-Sync
   ```
2. Install dependencies:
    ```bash
    npm install
    ```
4. Start the development server:
  ```bash
  npm start
  ```
# Backend
## Clone the backend repository:
  ```bash
  git clone https://github.com/ankit14-dev/Meet-Sync-Backend.git  
  cd Meet-Sync-Backend
  ```
# Install dependencies:
  ```bash
  npm install
  ```
# Start the server:
  ```bash
  node index.js
  ```
## Technologies Used
- Frontend: React
- Backend: Node.js, Express
- Audio Processing: FFmpeg
- File Handling: Multer
- Hosting: Railway (Frontend), AWS (Backend)
