# ChatSphere - Real-Time Chat Application

![image](https://github.com/user-attachments/assets/9bae32f9-8891-44de-a4e2-2374d80ee7aa)



## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About the Project
**ChatSphere** is a real-time chat application that allows users to send and receive messages instantly. Built with **MERN Stack** and **Socket.IO**, it offers a smooth messaging experience with features like authentication, group chats, and media sharing. The app integrates **Clerk** for authentication and **Sentry** for error tracking.

## Features
- 💬 **Real-Time Messaging** - Send and receive messages instantly using WebSockets.
- 🏢 **User Authentication** - Secure login/signup using Clerk.
- 🔒 **End-to-End Encryption** - Ensuring message privacy.
- 👥 **Group Chats** - Create and manage chat groups.
- 📂 **Media Sharing** - Share images, videos, and documents.
- 🛠 **Error Tracking** - Integrated with Sentry for monitoring.
- 🚀 **Deployed on Vercel** - Ensuring scalability and uptime.

## Tech Stack
- **Frontend:** React, Tailwind CSS
- **Backend:** Node.js, Express.js, Socket.IO
- **Database:** MongoDB
- **Authentication:** Clerk
- **Real-Time Communication:** Socket.IO
- **Monitoring:** Sentry
- **Deployment:** Vercel

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/TuShArBhArDwA/ChatSphere.git
   cd ChatSphere
   ```
2. **Install dependencies**
   ```sh
   npm install
   ```
3. **Set up environment variables**
- Create a `.env` file in the root directory.
- Add the required environment variables (see Environment Variables section).

4. **Start the development server**
   ```sh
   npm run dev
   ```
- The application will be available at http://localhost:3000.

## Environment Variables
Create a `.env` file in the root directory and add:
```env
MONGODB_URI=your_mongodb_connection_string
CLERK_API_KEY=your_clerk_api_key
SENTRY_DSN=your_sentry_dsn
VERCEL_URL=your_vercel_project_url
```
### Configuration Instructions:
- **MONGODB_URI** → MongoDB connection string from [MongoDB Atlas](https://www.mongodb.com/atlas).
- **CLERK_API_KEY** → API key from [Clerk](https://clerk.dev/) for authentication.
- **SENTRY_DSN** → DSN from [Sentry](https://sentry.io/) for monitoring errors.
- **VERCEL_URL** → Your Vercel deployment URL (optional for production setups).

## Usage
1. **Run the development server**  
   ```sh
   npm run dev
   ```
- The app will be available at http://localhost:3000.

2. **Sign up or log in**
   - Start chatting with friends or create group chats.
   - Share media files in conversations.
   
3. **Real-Time Chatting**
   - Users can send and receive messages instantly using WebSockets.
   
4. **Monitor Performance (Admins/Developers)**
   - Use Sentry for error tracking and optimizing queries.

## Deployment
- The project is deployed on **Vercel**.
- To deploy the frontend and backend, use:
  ```sh
  vercel
  ```
- Ensure Vercel CLI is installed and logged in.
- Configure environment variables on Vercel.
- After deployment, access the live app via the Vercel URL.

## Contributing
Contributions are welcome! Follow these steps:

1. **Fork the repository**  
   Click the "Fork" button on GitHub.

2. **Clone your forked repository**  
   ```sh
   git clone https://github.com/TuShArBhArDwA/ChatSphere.git
   cd ChatSphere
   ```

3. **Create a new branch**
   ```sh
   git checkout -b feature-name
   ```

4. **Make your changes and commit them**
   ```sh
   git add .
   git commit -m "Add feature: description of changes"
   ```

5. **Push your changes**
   ```sh
   git push origin feature-name
   ```

6. **Create a Pull Request (PR)**
   - Go to the original repository on GitHub.
   - Click on "Compare & pull request."
   - Add a meaningful title and description.
   - Submit the PR for review.

### Guidelines
- Follow best coding practices.
- Write clear commit messages.
- Ensure the code is linted and tested.

## License
Distributed under the MIT License. See LICENSE for details.

## Contact
- **Tushar Bhardwaj** - [Portfolio](https://tushar-bhardwaj.vercel.app/)
- **Connect 1:1** - [Topmate](https://topmate.io/tusharbhardwaj)
- **GitHub:** [TuShArBhArDwA](https://github.com/TuShArBhArDwA)
- **LinkedIn:** [Tushar Bhardwaj](https://www.linkedin.com/in/bhardwajtushar2004/)
- **Email:** [tusharbhardwaj2617@example.com](mailto:tusharbhardwaj2617@example.com)
