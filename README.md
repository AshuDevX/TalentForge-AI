# TalentForge-AI

TalentForge-AI is a full-stack web application designed to assist job seekers in preparing for technical interviews. The platform allows users to upload resumes, analyze job descriptions, identify potential skill gaps, and generate interview preparation questions using generative AI.

The project demonstrates how modern web technologies and AI services can be integrated to support common steps in the job application and interview preparation process.

---

## Features

- Resume upload and analysis  
- Job description comparison  
- Skill gap identification  
- AI-generated interview questions  
- Suggestions for improving ATS compatibility  
- Secure user authentication  

---

## Tech Stack

### Frontend
- React  
- Vite  
- Tailwind CSS  

### Backend
- Node.js  
- Express.js  

### Database
- MongoDB  
- Mongoose  

### AI Integration
- Google Gemini API  

---

## Project Structure

```bash
talentForge-ai
│
├── Backend
│   ├── src
│   │   ├── config
│   │   ├── controllers
│   │   ├── models
│   │   ├── routes
│   │   └── services
│   │
│   ├── server.js
│   └── package.json
│
├── Frontend
│   ├── src
│   ├── components
│   ├── pages
│   └── package.json
│
└── README.md
```

---

## Installation

Clone the repository.

```bash
git clone (https://github.com/AshuDevX/TalentForge-AI)
```

---

## Backend Setup

Navigate to the backend directory and install dependencies.

```bash
cd Backend
npm install
```

Create a `.env` file in the **Backend** directory.

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_gemini_api_key
JWT_SECRET=your_secret_key
```

Start the development server.

```bash
npm run dev
```



---

## Frontend Setup

Open a new terminal and run:

```bash
cd Frontend
npm install
npm run dev
```



---

## Environment Variables

Create a `.env` file inside the **Backend** directory.

```env
PORT=
MONGO_URI=
GEMINI_API_KEY=
JWT_SECRET=
```

---

## Purpose of the Project

This project was built to explore and demonstrate:

- Full-stack application development  
- REST API design and architecture  
- MongoDB integration with Mongoose  
- Authentication using JWT  
- Handling file uploads in web applications  
- Integrating generative AI into practical workflows  

---

## License

This project is licensed under the MIT License.
