# 🎲 Random Activity Generator

Tired of being bored? This fun web app fetches **random activities** based on your preferences (like type of activity and number of participants) using the Bored API. Whether you're alone or with friends, it finds something fun for you to do!

![image](https://github.com/user-attachments/assets/ec3efbb1-8164-4d73-b47f-45ec2a730bb7)


---

## 🚀 Features

- 🎯 Suggests random activities
- 📚 Filter by type (education, relaxation, music, etc.)
- 👥 Filter by number of participants
- 🌈 Colorful SVG pattern background
- 📱 Responsive design

---

## 🛠 Tech Stack

- **Node.js**
- **Express.js**
- **EJS** (Embedded JavaScript templates)
- **Axios** (for making API requests)
- **HTML/CSS** for frontend styling

---

## 📦 Installation

1. **Clone the repository**
git clone https://github.com/HARSHITASINHA1124/random-task-generator.git
cd random-task-generator

2. **Install dependencies**
npm install

3. **Run the app**
node index.js

4. **Open your browser and go to**
http://localhost:3000

---

## 📂 **Project Structure**

random-task-generator/
├── public/
│   └── styles/
│       └── main.css        # Styling and SVG background
├── views/
│   └── index.ejs           # EJS template
├── index.js                # Express server
├── package.json            # Project metadata and dependencies
└── README.md               # This file

---

## 🧠 How It Works

--> On visiting the homepage, a random activity is fetched from the API.

--> Users can filter activities by type or number of participants using the dropdowns.

--> Submitting the form sends a POST request to fetch a filtered activity.

--> If no activity is found, an error message is displayed.

---


