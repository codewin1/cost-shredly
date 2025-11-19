# Cost Sharing App  

A *premium, futuristic, and realtime Expense Splitter* built with *React, TailwindCSS, Node.js, Express, MongoDB, and Socket.io*.  
Split costs or bills with friends, track balances, chat inside groups, and get realtime notifications – all in one place.  

## Features  

- *Group Management*  
  - Create groups with friends/colleagues  
  - Invite/remove members  
  - Manage member balances  

- *Expense Tracking*  
  - Add shared expenses (auto-split)  
  - Track who owes / who gets back  
  - Realtime balance updates  

- *Realtime Chat*  
  - Group chat with Socket.io  
  - Typing + instant message delivery  

- *Notifications*  
  - Expense added  
  - New member invited  
  - Member removed  

- *Premium UI (Figma → React + Tailwind)*  
  - Futuristic glowing gradients  
  - 3D glassmorphism effects  
  - Theme toggle (Light/Dark)  
  - Mobile + Desktop responsive  

---

## Screenshots  

### Authentication  

![Login Page](screenshots/login.png)  
![Signup Page](screenshots/signup.png)  

### Dashboard  
![Dashboard](screenshots/dashboard.png)  

### Group Details  
![Group Details](screenshots/group-details.png)  

### Realtime Chat  
![Chat](screenshots/chat.png)  

---

## Tech Stack  

*Frontend*:  
- React  
- TailwindCSS  
- Axios  
- React Router  
- React Toastify  
- Socket.io-client  

*Backend*:  
- Node.js + Express  
- MongoDB Atlas  
- JWT Authentication  
- Socket.io  

*Deployment*:  
- Frontend → Vercel  
- Backend → Render  

---

##License

This project is licensed under the MIT License — see the LICENSE file for details

## Author  

*Edwin Murimi - codewin1*  

### Clone the repo  

```bash
# Clone the repository
git clone https://github.com/codewin1/cost-shredly.git

# --- Backend Setup ---
cd server
npm install

# Add a .env file with the following:
# MONGO_URI=your_mongo_atlas_uri
# JWT_SECRET=your_secret_key

npm run dev

# --- Frontend Setup ---
cd ../client
npm install
npm start


---      
