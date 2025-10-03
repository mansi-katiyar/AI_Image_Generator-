# 🖼️ AI Image Generator

## 📌 Overview
The **AI Image Generator** is a full-stack project developed by **Mansi Katiyar**.  
It allows users to generate unique AI-powered images from text prompts using advanced machine learning models (such as OpenAI/DALLE or Stable Diffusion).  

The application is designed with a **React frontend** and a **Node.js + Express backend**, providing a clean UI and powerful API integration.

---

## ✨ Features
- 📝 Text-to-Image generation  
- 💾 Save and download generated images  
- 🌐 Share images with the community  
- 🔐 User authentication (login/signup)  
- ⚡ Real-time API communication  
- 📱 Responsive design for all devices  

---

## 🛠️ Tech Stack
- **Frontend:** React.js, HTML, CSS, JavaScript  
- **Styling:** TailwindCSS / Bootstrap  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **AI API:** OpenAI API / Stable Diffusion (configurable)  
- **Authentication:** JWT  
- **Version Control:** Git & GitHub  

---

##🚀 Roadmap / To-Do

 Add advanced image editing features

 Implement prompt history & trending prompts

 Add community feed with likes/comments

 Support multiple AI models (Stable Diffusion, DALLE)

 Deploy on Vercel (frontend) & Render/Heroku (backend)
---
##🤝 Contributing

Contributions are welcome!
Steps:

Fork this repo

Create a feature branch (git checkout -b feat/feature-name)

Commit changes (git commit -m "feat: add feature")

Push to branch and open a PR
---
##📜 License

Specify a license (e.g., MIT).
---
## 📂 Repository Structure
AI_Image_Generator

│

├─ client/ # Frontend (React)

│ ├─ public/

│ └─ src/

│ ├─ components/

│ ├─ pages/

│ ├─ services/

│ └─ App.jsx

│

├─ server/ # Backend (Node + Express)

│ ├─ controllers/

│ ├─ models/

│ ├─ routes/

│ └─ app.js

│

├─ .gitignore

└─ README.md

---

## ⚡ Installation & Setup
1. Clone the repository
```bash
git clone https://github.com/mansi-katiyar/AI_Image_Generator-.git
cd AI_Image_Generator-
Setup Backend

cd server
npm install
# create .env file with API key and DB connection
npm run dev
Setup Frontend

---
cd ../client
npm install
npm start
👉 Open the app at: http://localhost:3000
---

🔧 Environment Variables
Create a .env file inside server/ with:

PORT=5000
DB_URI=mongodb://localhost:27017/ai_image_generator
JWT_SECRET=your_secret_key
OPENAI_API_KEY=your_openai_api_key
---
