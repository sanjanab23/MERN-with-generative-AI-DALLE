# MERN with Generative AI (DALLE)

A full-stack **MERN (MongoDB, Express.js, React, Node.js)** application integrated with **OpenAI's DALL·E** API to generate AI-based images from text prompts.

---

## Features

- User-friendly interface to input text prompts
- Generate high-quality images using OpenAI DALL·E
- Full-stack architecture with RESTful API
- Stores generated images and user data in MongoDB
- Responsive and modern React frontend

---

## Tech Stack

- **Frontend:** React.js, Tailwind CSS (or your CSS framework)
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **AI Integration:** OpenAI DALL·E API
- **Deployment:** (Optional) Vercel / Heroku / Render

---

## Installation

1. **Clone the repository**
```bash
git clone https://github.com/sanjanab23/MERN-with-generative-AI-DALLE.git
cd MERN-with-generative-AI-DALLE
````

2. **Install dependencies for both backend and frontend**

```bash
npm install        # installs backend dependencies in the root (or server folder if structured)
cd client
npm install        # installs frontend dependencies
cd ..
```

3. **Set up environment variables**

Create a `.env` file in the `server` folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
OPENAI_API_KEY=your_openai_api_key
```

---

## Usage

1. **Start the backend**

```bash
cd server
npm start
```

2. **Start the frontend**

```bash
cd client
npm start
```

3. Open `http://localhost:3000` in your browser and start generating AI images.

```
