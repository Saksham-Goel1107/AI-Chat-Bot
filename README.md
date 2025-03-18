# AI Chat Bot

An AI-powered chat application built using the MERN (MongoDB, Express, React, Node.js) stack, featuring collaborative chat capabilities and AI functionalities.

## 🚀 Live Demo

[![Live Site](https://img.shields.io/badge/Live%20Demo-Online-green)](https://ai-chat-bot-yc0x.onrender.com)

## Features

- Real-time chat with the ability to add collaborators
- AI-powered responses
- User authentication

## Tech Stack

- **Frontend:** React,Tailwind
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **AI Integration:** Google Gemini API

## Installation

1. **Clone the repository**
   ```sh
   git clone https://github.com/Saksham-Goel1107/AI-Chat-Bot.git
   cd AI-Chat-Bot
   ```

2. **Set up the server**
   ```sh
   cd backend
   npm install
   ```
   - Create a `.env` file and add the following:
     ```env
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     REDIS_HOST=your_redis_host_id
     REDIS_PORT=your_redis_port
     REDIS_PASSWORD=your_redis_password
     GEMINI_API_KEY=your_gemini_api_key
     ```
   - Start the backend server:
     ```sh
     node server
     ```

3. **Set up the client**
   ```sh
   cd frontend
   npm install
   npm run dev
   ```

## Usage

1. Open the app in your browser at `http://localhost:5173`.
2. Register or log in to access the chat interface.
3. Start a conversation, add collaborators, and utilize AI features.

## Folder Structure
```
AI-Chat-Bot/
├── backend/
│   ├── controllers/
│   ├── db/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── auth/
│   │   ├── config/
│   │   ├── context/
│   │   ├── routes/
│   │   ├── screens/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
└── README.md
```

## Deployment
To deploy the application:
- Use **Render** or **Heroku** for the backend
- Use **Vercel** or **Netlify** for the frontend

## Future Changes

| Feature/Fix         | Description                            |  Status      |
|---------------------|----------------------------------------|--------------|
| Bug Fixes           | Fixing UI glitches and API issues      |  Planned     |
| New AI Features     | Improving AI responses and context     |  Planned     |
| UI Enhancements     | Enhancing chat UI for better UX        |  Planned     |
| Notifications       | Adding real-time chat notifications    |  Planned     |
| User Roles          | Implementing admin and moderator roles |  Planned     |

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -m 'Add feature'`
4. Push to branch: `git push origin feature-name`
5. Open a pull request

## Contact

For any inquiries, feel free to reach out:
- **Email:** [sakshamgoel1107@gmail.com](mailto:sakshamgoel1107@gmail.com)
- **GitHub:** [Saksham-Goel1107](https://github.com/Saksham-Goel1107)

## License

This project is licensed under the MIT License.

---

Happy coding! 🚀

