
SignLang Connect

A real-time video call application designed to bridge communication gaps by enabling users to communicate using speech-to-text live captions and sign language recognition. The app incorporates innovative technology to detect sign language gestures through the camera and convert them to text in real-time, fostering inclusive communication.


---

Features

Real-Time Video and Audio Calling: Seamless video and audio communication using WebRTC.

Speech-to-Text Conversion: Converts speech to text in real-time using the Google Speech-to-Text API.

Sign Language Detection: Detects sign language gestures using OpenCV and machine learning models, converting them into text.

Cross-Platform Accessibility: Accessible via web browsers for a broad audience.

User-Friendly Interface: Clean and intuitive design for effective communication.


---

Tech Stack

Backend

Node.js: Handles server-side operations and WebSocket communication.

Express.js: Backend framework for API routes and middleware.

Socket.IO: Manages real-time communication.

Python: Processes sign language detection and speech-to-text functionalities.

OpenCV: Detects and processes sign language gestures.


Frontend

React.js: Frontend framework for building the user interface.

WebRTC: Enables video and audio communication.

CSS/Bootstrap: Designs a responsive UI.



---

Project Structure

root
│
├── backend
│   ├── server.js               
│   ├── routes                 
│   ├── controllers             
│   ├── python_modules       
│   └── .env                   
│
├── frontend
│   ├── public                  
│   ├── src
│   │   ├── components       
│   │   ├── pages               
│   │   └── styles              
│   └── package.json           
│
└── README.md                 


---

Getting Started

Prerequisites

Node.js (v16 or later)

Python (v3.9 or later)

Git (latest version)


Setup Instructions

1. Clone the repository:

git clone https://github.com/AdwaithAswan/project-da-vinci
cd project-da-vinci


2. Install backend dependencies:

cd backend
npm install
pip install -r requirements.txt


3. Install frontend dependencies:

cd ../frontend
npm install


4. Start the backend server:

cd ../backend
node server.js


5. Start the frontend server:

cd ../frontend
npm start




---

Environment Variables

Create a .env file in the backend directory with the following details:

SECRET_KEY=<top-secret>
GOOGLE_API_KEY=<this-is-da-api-key>


---

Key Functionalities

Speech-to-Text Conversion

Tool: Google Speech-to-Text API

Process: Translates speech from the user's audio input into live captions.


Sign Language Detection

Tool: OpenCV + Machine Learning

Process: Captures gestures via the webcam and processes them to convert into text.


Real-Time Communication

Tool: WebRTC + Socket.IO

Process: Streams video and audio in real-time while synchronizing captions and gesture outputs.



---

Contributing

1. Fork the repository.


2. Create a new branch:

git checkout -b feature-name


3. Commit changes:

git commit -m "Added a new feature"


4. Push to the branch:

git push origin feature-name


5. Create a pull request.




---

License

This project is licensed under the MIT License.


---

Contact

For any queries or contributions, contact the project team:

Team Lead: Adwaith Aswan

Email: adwaithaswakumar@gmail.com 


