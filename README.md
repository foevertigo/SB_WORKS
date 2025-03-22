SB Works - Freelancing Marketplace (MERN Stack)



INTRODUCTION


SB Works is an innovative freelance marketplace designed to connect project owners with skilled independent professionals. It offers a user-friendly dashboard for project posting, bidding, collaboration, and streamlined communication. The platform ensures data integrity and secure transactions, making it a reliable workspace for freelancers and clients alike.

FEATURES

    🔐 User Authentication: Secure login and registration for clients and freelancers.

    📌 Project Posting: Clients can post new projects with descriptions and requirements.

    💼 Bidding System: Freelancers can submit proposals for projects.

    💬 Chat System: Secure interactive communication between clients and freelancers.

    📊 Project Management: Tracking of project progress and submission.

    🎛️ Admin Panel: Manage users, projects, and transactions.

    🔔 Real-Time Updates: Notifications for bids, messages, and project milestones.


TECHNOLOGY STACK

   Frontend
   

    ⚛️ React.js

    🎨 Material UI

    🎭 Bootstrap

    🌐 Axios (for API requests)

   Backend

    🟢 Node.js

    🚀 Express.js

    🛢️ MongoDB (Mongoose for database interaction)

    🔑 JWT Authentication

    🔄 WebSockets for real-time chat

 PREREQUISITES

Ensure the following are installed before setting up the project:

    📦 Node.js & npm

    🗄️ MongoDB

    🌍 Git   

INSTALLATION AND SETUP

1️⃣ Clone the repository by running the following command:

    git clone https://github.com/your-repo/SB-Works.git
    cd SB-Works

2️⃣ Install dependencies for both frontend and backend:

Frontend:

    cd client
    npm install

Backend:

    cd server
    npm install

3️⃣ Start the development server:

Backend:

    cd server
    npm start

Frontend:

    cd client
    npm start

API Routes (🔑 User Authentication)

        POST /api/auth/register - Register a new user

        POST /api/auth/login - Login user

📌 Projects

    POST /api/projects - Create a new project

    GET /api/projects - Fetch all projects

    GET /api/projects/:id - Fetch project details

💼 Bidding

    POST /api/bids - Submit a bid

    GET /api/bids/:projectId - Fetch bids for a project

💬 Chat System

    POST /api/chat/send - Send a message

    GET /api/chat/:projectId - Retrieve messages



    
