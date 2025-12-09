# 📦 Distributed File System (DFS) with Fault Tolerance — Visual Simulator

A fully interactive **Distributed File System (DFS) Fault-Tolerance Simulator** built with **React, TypeScript, and TailwindCSS**. This project visually demonstrates how distributed systems such as **HDFS, Ceph, Google File System (GFS), and Cassandra** handle **replication, node failures, auto-healing, rack awareness, block distribution, and data integrity**.

Designed with a futuristic **neon + glassmorphism UI**, this simulator transforms complex system behaviors into clear, engaging visualizations.

---

## 🌐 Live Demo  
🔗 **https://dfs-with-fault-tolerance.netlify.app/**

---

## 📘 Table of Contents  
- [✨ Overview](#-overview)  
- [⚙️ Features](#️-features)  
  - [1️⃣ Distributed Storage](#1️⃣-distributed-storage)  
  - [2️⃣ Fault Tolerance](#2️⃣-fault-tolerance)  
  - [3️⃣ Simulation Tools](#3️⃣-simulation-tools)  
  - [4️⃣ UIUX Enhancements](#4️⃣-uiux-enhancements)  
- [🛠 Tech Stack](#-tech-stack)  
- [📂 Project Structure](#-project-structure)  
- [🧪 Run Locally](#-run-locally)  
- [📸 Screenshots](#-screenshots)  
- [🎯 Purpose](#-purpose)  
- [🤝 Contributing](#-contributing)  
- [📄 License](#-license)

---

## ✨ Overview

This simulator allows users to upload files, which are split into blocks and replicated across distributed nodes. If a node fails or a replica becomes corrupted, the system automatically detects the issue and triggers **auto-healing** to restore missing copies. This simulates real-world DFS behaviors like **high availability, durability, and fault tolerance**.

With its advanced visualization engine and interactive dashboard, the project bridges the gap between theory and real distributed system behavior.

---

## ⚙️ Features

### 1️⃣ Distributed Storage
- File upload with block splitting  
- Configurable replication factor  
- Smart replica placement based on load  
- Rack-aware distribution  
- Visual block mappings for each node  

### 2️⃣ Fault Tolerance
- Node failure simulation  
- Automatic detection of missing replicas  
- Auto-healing and self-recovery  
- Block corruption injection  
- Checksum-based integrity verification  
- Rack-level outages  

### 3️⃣ Simulation Tools
- Toggle nodes (active/dead)  
- Enable **Chaos Mode** for random failures  
- Read-file simulation with pass/fail outcome  
- Floating live metrics panel  
- Detailed modal for each node (capacity, blocks, health)  

### 4️⃣ UIUX Enhancements
- Glassmorphism + neon effects  
- 3D rotating DFS animation on login page  
- Animated cluster visualizer  
- Terminal-style real-time logs  
- Smooth transitions and micro-interactions  
- Capacity heatmaps  
- Fully responsive dashboard  

---

## 🛠 Tech Stack

- **React.js**  
- **TypeScript**  
- **TailwindCSS**  
- **Vite**  
- **Framer Motion** (optional animations)

---
src/
├── components/
│ ├── NodeCard.tsx
│ ├── FileUpload.tsx
│ ├── LogsPanel.tsx
│ ├── MetricsHUD.tsx
│ └── DFS3DRotation.tsx
├── visuals/
├── utils/
├── App.tsx
├── index.tsx
└── styles/


---

## 🧪 Run Locally

### Prerequisites  
- Node.js installed

### Steps  
1. Install dependencies  
   ```bash
   npm install


Add your Gemini API key in .env.local:

GEMINI_API_KEY=your_api_key_here


Start development server

npm run dev

 # 📸 Screenshots
<img width="1906" height="850" alt="Screenshot 2025-12-09 141305" src="https://github.com/user-attachments/assets/371a6920-72c4-4df1-8b1b-e5a66eb00c44" />
<img width="1910" height="849" alt="Screenshot 2025-12-09 141240" src="https://github.com/user-attachments/assets/cb588e5f-9006-4fb9-910f-3e79823d48e0" />
<img width="1910" height="849" alt="Screenshot 2025-12-09 141240" src="https://github.com/user-attachments/assets/3c0779c0-8b66-4363-99d8-49bd403fa981" />


Dashboard	Node Cluster	Login Page

	
	
 # 🎯 Purpose

This project is ideal for:

Students learning distributed systems

Final-year academic projects

Developers building advanced portfolio projects

Understanding DFS concepts through visual simulation

It combines technical depth with premium UI/UX for an immersive learning experience.

# 🤝 Contributing

Contributions, feature requests, and feedback are welcome!
Open an issue or submit a pull request.
