# **PlayerTracker** 🏆📊  
🚀 **AI-powered player tracking and automated statistics for futsal**  

## 📌 **Introduction**  
**PlayerTracker** is an innovative platform that uses **artificial intelligence** to automatically **detect players** and **generate advanced statistics** from futsal match videos.  

Designed for **data analysts, coaches, and clubs**, PlayerTracker provides an **automated** and **intuitive** way to track team performances, offering valuable insights without requiring manual intervention.  

This project was developed for **commercial purposes** and was also used as a **final-year academic project in software engineering**.

---

## 🔥 **Key Features**  
### 🏟 **Automated Match Analysis**
- **Player detection** from match videos 🎥  
- **Automatic generation of game statistics** 📊  
- **Identification of key events** (goals, passes, shots, possession) ⚽  

### 🎛 **Dashboard & Statistics**
- **Recent matches analysis** at a glance  
- **Performance comparison** across multiple matches  
- **Dynamic visual analytics**, including:  
  - **Goal ratio** per match  
  - **Possession rate**  
  - **Heatmaps** for player and ball movements 🔥  

### 🚀 **Match & Team Management**
- **Upload matches** (video files must meet specific requirements)  
- **Edit match details** (team names, date, etc.)  
- **Export match reports as PDFs** 📄  
- **Add and manage team players & coaching staff** 👥  
- **Team Management page** to set up club details  

### 🔐 **Security & User Management**
- **Secure authentication system** 🔑  
- **Role-based access** (analyst, admin)  
- **Multi-user support** (add staff members to a team)  

---

## 🛠 **Tech Stack**
PlayerTracker leverages a **modern full-stack architecture**, combining **a powerful backend, an intuitive frontend, and AI-driven analytics**.

### 🏗 **Backend**
- **Next.js** – API development & server-side rendering  
- **MinIO** – Object storage for video processing
- **PostgreSQL** - Data storing

### 🎨 **Frontend**
- **React** – React-based frontend with server-side rendering  
- **TailwindCSS** – Clean and responsive UI design  

### 🤖 **Artificial Intelligence**
- **YOLO (You Only Look Once)** – Player & ball detection  
- **OpenCV** – Video & image processing  
- **TensorFlow / PyTorch** – AI model training & optimization  

---

## 📂 **Installation & Deployment**  

### 1️⃣ **Prerequisites**
Ensure you have the following installed:  
- **Node.js (v16+)** and **npm** (or yarn)  
- **Docker & Docker Compose** (recommended)  
- **MinIO** (for video storage)  
- **FFmpeg** (for video processing)  

### 2️⃣ **Clone the repositories**
```bash
git clone https://github.com/PlayerTracker-EHB/PlayerTracker-Frontend.git
git clone https://github.com/PlayerTracker-EHB/PlayerTracker-Backend.git
git clone https://github.com/PlayerTracker-EHB/AI-tracker.git
```

### 3️⃣ **Backend Setup**
```bash
cd PlayerTracker-Backend
npm install
node ace migration:fresh
node ace db:seed
node ace serve
```

### 4️⃣ **Frontend Setup**
```bash
cd ../PlayerTracker-Frontend
npm install
npm run dev
```

### 5️⃣ **AI Processing Setup**
```bash
cd ../AI-tracker
pip install -r requirements.txt
python detect.py --source sample.mp4
```

### 6️⃣ **Accessing the Platform**
- **Backend API**: `http://localhost:3333`  
- **Frontend UI**: `http://localhost:5173`  

---

## 🏆 **How to Use PlayerTracker?**
### 1️⃣ **Create an Account & Login**
Users sign up and log into their **secure dashboard**.

### 2️⃣ **Upload a Match**
- Go to the **Uploader** page  
- Enter **match details** (teams, date, etc.)  
- Select a **video file** and click **Upload**  
- AI **automatically analyzes** the match 🧠  

### 3️⃣ **Analyze Match Statistics**
- View **all generated statistics** on the **Statistics page** 📊  
- Compare **performance across matches**  
- Explore **dynamic charts & heatmaps** 🔥  

### 4️⃣ **Export Reports**
- Match reports can be **exported as PDFs** 📄  

### 5️⃣ **Manage Team & Staff**
- Add/edit **players & coaching staff** 👥  
- Customize **club details** 📋  

![image](https://github.com/user-attachments/assets/beb9aa76-9eef-4d44-8fc6-6250ef3c5a9e)
![image](https://github.com/user-attachments/assets/ca300b94-85bf-4b5e-bcf0-2be19262cef2)
![image](https://github.com/user-attachments/assets/40d60fc4-128f-45a0-98d5-a44a1fbfadf5)
![image](https://github.com/user-attachments/assets/20201a0b-2cac-4b8f-95f8-201f690b81eb)
![image](https://github.com/user-attachments/assets/bd8997f2-32c1-4681-a121-761bc4f1c089)
![image](https://github.com/user-attachments/assets/b1f43889-95c8-4ceb-8a05-2b2e8bf43546)


---

## 🌍 **Roadmap & Future Developments**
✅ **MVP available** with core features 🎉  
🔜 **Upcoming Enhancements**:  
➜ **Pass tracking** 🎯  
➜ **Advanced analytics on shots, goals & duels** ⚽  
➜ **Player ID tracking for individual performance monitoring** 🔍  
➜ **Enhanced AI models for improved accuracy** 🤖  

---

## 💼 **Business Opportunities**
We are open to:  
✅ **Collaborations with futsal clubs & federations**  
✅ **Investment opportunities to expand & enhance the platform**  
✅ **Acquisition of the MVP and concept under specific conditions**  

📩 If you’re interested, feel free to reach out to us!  

---

## 🔒 **Security & Confidentiality**
- **The full source code remains private** within our GitHub organization.  
- **No API keys or sensitive data** are shared in this repository.  
- **LICENSE.md** ensures intellectual property protection.  

📢 _If we decide to release an open-source version, only selected non-critical components will be public._  

---

## 📝 **Contributors**
- **Nawfel Ajari** – Project Manager  
- **Kristian Vasiaj** – Fullstack, AI Specialist
- **Ismael Bouzrouti** – Backend, Devops & AI Specialist
- **Mehdi Merkachi** – Fullstack & Performance Optimization
- **Soufiane Hamoumi** – Frontend & UX/UI

The analysis phase of **PlayerTracker** began in **October 2024**. The contributors worked on this project across **five different sprints** between **February and March 2025**, following the **Scrum methodology** combined with **Kanban** for task management and workflow optimization.

A huge thank you to everyone contributing to PlayerTracker! 🚀  

---

## 📞 **Contact & Support**
📧 Email: **info@nainnovations.be**  
🔗 GitHub:  [n4wf3l](https://github.com/n4wf3l)  
- **Frontend**: [PlayerTracker-Frontend](https://github.com/PlayerTracker-EHB/PlayerTracker-Frontend)  
- **Backend**: [PlayerTracker-Backend](https://github.com/PlayerTracker-EHB/PlayerTracker-Backend)  
- **AI Processing**: [AI-tracker](https://github.com/PlayerTracker-EHB/AI-tracker)  

---

### 🚀 **PlayerTracker - AI-powered performance tracking for futsal!** 🏆📊  
