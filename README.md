# CareerSphere - Student Career Portal

A comprehensive MERN stack application that helps students manage their career development, access courses, take tests, build resumes, and find job opportunities.

## Features

- 🔐 Authentication (JWT-based)
- 📚 Course Access Module
- 📝 Test Series & Practice
- 📄 Resume Builder with AI Enhancement
- 💼 Job Finder with AI Matchmaking
- 🤖 AI Chatbot Assistant
- 🔔 Notifications & Reminders
- 🌓 Dark/Light Mode

## Tech Stack

- **Frontend**: React.js, Material-UI, Redux Toolkit
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT
- **AI Integration**: OpenAI GPT API
- **PDF Generation**: React-PDF
- **Real-time Features**: Socket.io

## Prerequisites

- Node.js (v14 or higher)
- MongoDB
- npm or yarn

## Project Structure

```
careersphere/
├── client/                 # React frontend
├── server/                 # Node.js backend
├── .env.example           # Example environment variables
└── README.md              # Project documentation
```

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/careersphere.git
cd careersphere
```

2. Install dependencies:
```bash
# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```

3. Set up environment variables:
```bash
# In the server directory
cp .env.example .env
# Edit .env with your configuration
```

4. Start the development servers:
```bash
# Start backend server (from server directory)
npm run dev

# Start frontend server (from client directory)
npm start
```

## Environment Variables

Create a `.env` file in the server directory with the following variables:

```
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
OPENAI_API_KEY=your_openai_api_key
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.
