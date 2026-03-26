# 🌍 Real-Time Location Tracking App

A real-time location tracking web application that allows users to share and visualize their live location on an interactive map. Built using **Node.js**, **Express**, **EJS**, **Socket.io**, and **Leaflet with OpenStreetMap**.

---

## 🚀 Features

- 📍 Real-time location tracking using browser Geolocation API  
- 🗺️ Interactive map powered by Leaflet + OpenStreetMap  
- 🔄 Live updates using WebSockets (Socket.io)  
- 👥 Multiple users can share and view locations simultaneously  
- ⚡ Fast and lightweight server using Express  
- 🎯 Automatic map centering on user location  

---

## 🛠️ Tech Stack

- **Frontend:** EJS, HTML, CSS, JavaScript  
- **Backend:** Node.js, Express.js  
- **Real-time Communication:** Socket.io (WebSockets)  
- **Maps & Visualization:** Leaflet.js + OpenStreetMap  
- **APIs Used:** Browser Geolocation API  

---

## 📂 Project Structure
```
project/
│── public/
│ ├── css/
│ │ └── style.css
│ ├── js/
│ │ └── script.js
│
│── views/
│ └── index.ejs
│
│── app.js
│── package.json
```

---

## ⚙️ Installation & Setup

1. Clone the repository
```
git clone https://github.com/your-username/real-time-tracking-app.git
cd real-time-tracking-app
```
2. Install dependencies
```
npm install
```
3. Start the server
```
node app.js
```
4. Open in browser
```
http://localhost:3000
```

## 📸 How It Works

- User opens the app → browser asks for location permission
- App fetches coordinates using Geolocation API
- Coordinates are sent to server via Socket.io
- Server broadcasts location to all connected users
- Map updates in real-time with latest positions

## 🧠 Key Concepts Used
- Real-time communication using WebSockets
- Event-driven architecture (Socket.io events)
- Client-server data flow
- Map rendering & tile layers
- Handling geolocation permissions and errors

## ⚠️ Notes
#### Make sure to allow location access in your browser
#### Works best on secure contexts (HTTPS or localhost)
##### Geolocation accuracy depends on device & network

- 🔮 Future Improvements
- 👤 User identification (names / avatars)
- 📌 Custom markers for different users
- 🗺️ Route tracking & history
- 🔐 Authentication system
- 📱 Mobile responsiveness improvements
