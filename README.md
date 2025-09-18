📸 SocialSquare –

SocialSquare is a modern social media platform inspired by Instagram, built with React + Vite for blazing-fast performance, TailwindCSS for responsive design, and Redux Toolkit for state management. It supports real-time updates using Socket.io and comes with a clean, user-friendly interface.

🚀 Features

🔐 User Authentication – Secure login & signup flow

🖼️ Create & Manage Posts – Upload, edit, and delete posts with captions

❤️ Likes & Comments – Interact with content in real-time

💬 Live Updates – Real-time interactions via Socket.io

🎨 Responsive UI – Styled with TailwindCSS & Radix UI components

🌙 Dark Mode Support – Integrated with next-themes

♻️ Persistent State – Using Redux Toolkit + Redux Persist

🔔 Toast Notifications – With sonner

⚡ Optimized Dev Experience – Powered by Vite

🛠️ Tech Stack

Frontend:

React 18 + Vite 6

TailwindCSS + tailwind-merge + tailwindcss-animate

Radix UI (@radix-ui/react-*)

Lucide React & React Icons

State & Data:

Redux Toolkit

React Redux

Redux Persist

Axios (API calls)

Socket.io Client (real-time communication)

Utilities & Dev Tools:

dotenv

ESLint (React + Hooks + Refresh plugins)

PostCSS & Autoprefixer

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/yourusername/socialsquare.git
cd socialsquare/frontend

2️⃣ Install dependencies
npm install

3️⃣ Configure environment variables

Create a .env file in the project root:

VITE_API_URL=http://localhost:5000/api
VITE_SOCKET_URL=http://localhost:5000

4️⃣ Start development server
npm run dev

5️⃣ Build for production
npm run build
npm run preview

📜 Scripts

npm run dev → Start development server

npm run build → Build production bundle

npm run preview → Preview production build

npm run lint → Run ESLint checks

🧩 Future Enhancements

📩 Direct Messaging (real-time chat)

🏷️ Hashtags & Explore page

🔔 Push notifications

🎥 Stories & Reels features

🤝 Contributing

Contributions are welcome!

Fork this repo

Create a new branch (feature/your-feature)

Commit your changes

Push and create a PR 🚀
