# 🚀 TalentIQ - Full-Stack Interview Platform

<div align="center">

![TalentIQ Banner](./frontend/public/hero.png)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js](https://img.shields.io/badge/Node.js-18+-green.svg)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-19.1+-blue.svg)](https://reactjs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-6.0+-green.svg)](https://www.mongodb.com/)
[![TypeScript](https://img.shields.io/badge/TypeScript-Supported-blue.svg)](https://www.typescriptlang.org/)
[![GitHub stars](https://img.shields.io/github/stars/bouzayenilyes/TalentIQ_Code_Together?style=social)](https://github.com/bouzayenilyes/TalentIQ_Code_Together)
[![GitHub forks](https://img.shields.io/github/forks/bouzayenilyes/TalentIQ_Code_Together?style=social)](https://github.com/bouzayenilyes/TalentIQ_Code_Together)

**A comprehensive full-stack interview platform built with modern technologies for conducting technical interviews with real-time collaboration features.**

[Live Demo](#-live-demo) • [Features](#-features) • [Getting Started](#-getting-started) • [Documentation](#-documentation) • [Contributing](#-contributing)

</div>

---

## 📋 Table of Contents

- [🎯 About](#-about)
- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📦 Package Versions](#-package-versions)
- [🚀 Live Demo](#-live-demo)
- [📦 Installation](#-installation)
- [🔧 Configuration](#-configuration)
- [🏃‍♂️ Usage](#️-usage)
- [📚 API Documentation](#-api-documentation)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👨‍💻 Author](#-author)
- [🙏 Acknowledgments](#-acknowledgments)

---

## 🎯 About

TalentIQ is a modern, full-stack interview platform designed to revolutionize the technical interview process. Built with cutting-edge technologies, it provides a seamless experience for both interviewers and candidates, featuring real-time collaboration tools, secure code execution, and comprehensive interview management.

**Key Highlights:**
- 🧑‍💻 VSCode-powered code editor with syntax highlighting
- 🎥 Integrated video conferencing with screen sharing
- 🔐 Secure authentication and authorization
- ⚡ Real-time collaboration and communication
- 🎯 Automated testing and feedback system
- 📊 Comprehensive dashboard and analytics

---

## ✨ Features

### 🎯 Core Functionality

| Feature | Description |
|---------|-------------|
| **🧑‍💻 Code Editor** | VSCode-powered editor with syntax highlighting for 10+ languages |
| **🎥 Video Interviews** | 1-on-1 video call rooms with HD quality streaming |
| **💬 Real-time Chat** | Integrated messaging system with file sharing |
| **📊 Dashboard** | Live statistics and interview analytics |
| **🔐 Authentication** | Secure login via Clerk with role-based access |
| **🎯 Problem Library** | Curated coding problems with difficulty levels |

### 🚀 Advanced Features

- **🔊 Media Controls**: Toggle mic, camera, and screen sharing
- **📹 Recording**: Automatic session recording for review
- **🔒 Room Management**: Secure room locking (max 2 participants)
- **⚙️ Code Execution**: Isolated environment with multiple language support
- **🎉 Feedback System**: Instant success/fail notifications with confetti animations
- **🔄 Background Jobs**: Asynchronous processing with Inngest
- **🧠 Smart Analytics**: Performance insights and improvement suggestions

### 🛡️ Security & Reliability

- **🔒 Secure Code Execution**: Sandboxed environment for code running
- **⚡ Data Caching**: Optimized performance with TanStack Query
- **🔐 Protected Routes**: Middleware-based access control
- **📱 Responsive Design**: Mobile-friendly interface

---

## 🛠️ Tech Stack

### Frontend
- **⚛️ React 19.1+** with TypeScript
- **⚡ Vite 7.1+** for blazing fast development
- **🎨 Tailwind CSS 4.1+** for styling
- **📡 TanStack Query 5.90+** for data fetching and caching
- **🔐 Clerk 5.53+** for authentication
- **📹 Stream 1.24+** for video calling and real-time features
- **📝 Monaco Editor 4.7+** for code editing
- **🚀 Axios 1.12+** for API requests

### Backend
- **🟢 Node.js** with Express.js 5.1+
- **🍃 MongoDB** with Mongoose 8.19+ ODM
- **🔄 Inngest 3.44+** for background job processing
- **📡 Stream 0.7+** for real-time communication
- **🔐 Clerk 1.7+** for secure authentication

### Infrastructure & Deployment
- **🚀 Vercel** for frontend deployment
- **🖥️ Sevalla** for backend hosting
- **🐳 Docker** containerization support
- **📊 Analytics** and monitoring tools

## 📦 Package Versions

### Frontend Dependencies
- **React**: 19.1.1
- **Vite**: 7.1.7
- **Tailwind CSS**: 4.1.14
- **TanStack Query**: 5.90.5
- **Clerk**: 5.53.3
- **Stream Video SDK**: 1.24.0
- **Monaco Editor**: 4.7.0
- **Axios**: 1.12.2

### Backend Dependencies
- **Express**: 5.1.0
- **Mongoose**: 8.19.1
- **Clerk**: 1.7.41
- **Stream Node SDK**: 0.7.12
- **Inngest**: 3.44.3

---

## 🚀 Live Demo

🔗 **[Experience TalentIQ Live](https://your-demo-url.com)** 

*Note: Replace with actual demo URL when deployed*

---

## 📦 Installation

### Prerequisites

- **Node.js** 18.0 or higher (compatible with latest features)
- **npm** or **yarn** package manager
- **MongoDB** database (local or cloud)
- **Git** for version control

### Quick Start

```bash
# Clone the repository
git clone https://github.com/bouzayenilyes/TalentIQ_Code_Together.git
cd TalentIQ_Code_Together

# Install dependencies
npm install

# Setup environment variables (see Configuration section)
cp .env.example .env

# Start development servers
npm run dev
```

---

## 🔧 Configuration

### Environment Variables

#### Backend Configuration (`/backend/.env`)

```bash
# Server Configuration
PORT=3000
NODE_ENV=development

# Database
DB_URL=mongodb://localhost:27017/talent-iq

# Authentication (Clerk)
CLERK_PUBLISHABLE_KEY=pk_test_your_clerk_key
CLERK_SECRET_KEY=sk_test_your_clerk_secret

# Real-time Communication (Stream)
STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret

# Background Jobs (Inngest)
INNGEST_EVENT_KEY=your_inngest_event_key
INNGEST_SIGNING_KEY=your_inngest_signing_key

# Client Configuration
CLIENT_URL=http://localhost:5173
```

#### Frontend Configuration (`/frontend/.env`)

```bash
# Authentication (Clerk)
VITE_CLERK_PUBLISHABLE_KEY=pk_test_your_clerk_key

# API Configuration
VITE_API_URL=http://localhost:3000/api

# Real-time Communication (Stream)
VITE_STREAM_API_KEY=your_stream_api_key
```

### 🔑 Required API Keys

1. **Clerk**: Sign up at [clerk.dev](https://clerk.dev)
2. **Stream**: Get credentials from [getstream.io](https://getstream.io)
3. **Inngest**: Register at [inngest.com](https://inngest.com)
4. **MongoDB**: Use local installation or [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)

---

## 🏃‍♂️ Usage

### Starting the Application

```bash
# Start both frontend and backend
npm run dev

# Or start individually:
# Backend only
npm run server

# Frontend only
npm run client
```

### 🎯 Interview Flow

1. **Setup**: Configure environment variables
2. **Authentication**: Sign in via Clerk
3. **Create Session**: Set up interview room
4. **Code Interview**: Use the integrated code editor
5. **Video Call**: Enable video/audio communication
6. **Review Results**: Analyze performance and feedback

### 📝 API Endpoints

```bash
# Authentication
POST /api/auth/login
POST /api/auth/logout

# Sessions
GET /api/sessions
POST /api/sessions
PUT /api/sessions/:id
DELETE /api/sessions/:id

# Chat
GET /api/chat/:sessionId
POST /api/chat/:sessionId

# Code Execution
POST /api/execute
```

---

## 📚 API Documentation

### Authentication

All protected routes require authentication via Clerk JWT tokens.

```javascript
// Example request
const response = await fetch('/api/sessions', {
  headers: {
    'Authorization': 'Bearer YOUR_JWT_TOKEN',
    'Content-Type': 'application/json'
  }
});
```

### Code Execution API

```javascript
// Execute code
POST /api/execute
{
  "language": "javascript",
  "code": "console.log('Hello, World!')",
  "input": ""
}

// Response
{
  "output": "Hello, World!\n",
  "error": null,
  "executionTime": 0.156
}
```

---

## 🧪 Development

### Project Structure

```
talent-IQ/
├── backend/                 # Express.js API server
│   ├── src/
│   │   ├── controllers/     # Route handlers
│   │   ├── models/         # Database models
│   │   ├── routes/         # API routes
│   │   ├── middleware/     # Custom middleware
│   │   └── lib/           # Utility libraries
│   └── package.json
├── frontend/               # React application
│   ├── src/
│   │   ├── components/     # Reusable components
│   │   ├── pages/         # Route components
│   │   ├── hooks/         # Custom React hooks
│   │   ├── lib/           # Utility functions
│   │   └── api/           # API clients
│   └── package.json
└── README.md
```

### 🏗️ Architecture Overview

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   Frontend      │    │    Backend      │    │   Database      │
│   (React/TS)    │◄──►│  (Node.js)      │◄──►│   (MongoDB)     │
│                 │    │                 │    │                 │
│ • UI Components │    │ • REST API      │    │ • User Data     │
│ • State Mgmt    │    │ • Auth Middleware│   │ • Sessions      │
│ • Real-time UI  │    │ • WebSocket     │    │ • Chat Messages │
└─────────────────┘    └─────────────────┘    └─────────────────┘
         │                       │                       │
         │                       │                       │
         ▼                       ▼                       ▼
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   Stream SDK    │    │    Inngest      │    │   Clerk Auth    │
│                 │    │                 │    │                 │
│ • Video Calls   │    │ • Background    │    │ • User Auth     │
│ • Chat          │    │   Jobs          │    │ • Role Mgmt     │
│ • Recording     │    │ • Notifications │    │ • Session Mgmt  │
└─────────────────┘    └─────────────────┘    └─────────────────┘
```

### Available Scripts

```bash
# Development
npm run dev              # Start both servers with hot reload
npm run dev:server       # Start backend only
npm run dev:client       # Start frontend only

# Building
npm run build            # Build for production
npm run build:client     # Build frontend only
npm run build:server     # Build backend only

# Testing
npm run test             # Run all tests with coverage
npm run test:client      # Run frontend tests
npm run test:server      # Run backend tests
npm run test:watch       # Watch mode for tests

# Linting & Formatting
npm run lint             # Check code quality
npm run lint:fix         # Fix linting issues automatically
npm run format           # Format code with Prettier

# Database
npm run db:seed          # Seed database with sample data
npm run db:migrate       # Run database migrations
npm run db:backup        # Backup database

# Utilities
npm run clean            # Clean build artifacts
npm run type-check       # TypeScript type checking
npm run security         # Security audit
```

---

## 🤝 Contributing

We welcome contributions! Please read our contributing guidelines before submitting PRs.

### Development Workflow

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'feat: add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Code Standards

- Follow TypeScript best practices
- Use conventional commit messages
- Add tests for new features
- Ensure all linting checks pass
- Update documentation as needed

### 🐛 Reporting Issues

When reporting issues, please include:
- **OS and Browser** details
- **Steps to reproduce**
- **Expected vs actual behavior**
- **Screenshots** (if applicable)
- **Console errors**

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Ilyes Bouzayen

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 👨‍💻 Author

<div align="center">

**Ilyes Bouzayen**  
*Full-Stack Developer*

[![GitHub](https://img.shields.io/badge/GitHub-bouzayenilyes-blue?style=for-the-badge&logo=github)](https://github.com/bouzayenilyes)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ilyes--bouzayen-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/ilyes-bouzayen)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit_Site-green?style=for-the-badge&logo=website)](https://your-portfolio-url.com)

*"Building the future of technical interviews, one commit at a time."*

</div>

---

## 🙏 Acknowledgments

Special thanks to the open-source community and the following technologies that made this project possible:

- **Clerk** - Seamless authentication and user management
- **Stream** - Real-time communication infrastructure
- **MongoDB** - Flexible database solution
- **Inngest** - Reliable background job processing
- **Piston** - Secure code execution environment
- **React Ecosystem** - Modern UI development
- **Node.js Community** - Robust backend infrastructure

---

<div align="center">

### ⭐ Show Your Support

If this project helped you, please consider giving it a ⭐ on GitHub!

[⬆ Back to Top](#-talentiq---full-stack-interview-platform)

</div>

---

---

<div align="center">

### 📊 Project Statistics

[![GitHub Issues](https://img.shields.io/github/issues/bouzayenilyes/TalentIQ_Code_Together)](https://github.com/bouzayenilyes/TalentIQ_Code_Together/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/bouzayenilyes/TalentIQ_Code_Together)](https://github.com/bouzayenilyes/TalentIQ_Code_Together/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/bouzayenilyes/TalentIQ_Code_Together)](https://github.com/bouzayenilyes/TalentIQ_Code_Together/commits/main)
[![Code Quality](https://img.shields.io/badge/Code%20Quality-A+-green)](https://github.com/bouzayenilyes/TalentIQ_Code_Together)

### 🎯 Live Application
- **🚀 Production URL**: [Coming Soon](#)
- **🔗 Staging Environment**: [Coming Soon](#)
- **📱 Mobile Responsive**: ✅
- **♿ Accessibility**: WCAG 2.1 AA Compliant

### 🏆 Achievements & Recognition
- **⭐ Best Practices**: Follows industry standards
- **🔒 Security**: Enterprise-grade security implementation
- **📱 UX/UI**: Modern, intuitive user interface
- **⚡ Performance**: Optimized for speed and efficiency

---

**Built with ❤️ by [Ilyes Bouzayen](https://github.com/bouzayenilyes) | Powered by Innovation 🚀**
