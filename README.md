
Distributed File System (DFS) with Fault Tolerance — Visual Simulator

This project is an advanced Distributed File System (DFS) Fault-Tolerance Simulator designed to visually demonstrate how real-world distributed storage systems work, such as HDFS, Ceph, Google File System (GFS), and Cassandra. Built using React, TypeScript, and TailwindCSS, the simulator provides an immersive and interactive environment to explore key distributed system concepts, including replication, auto-healing, node failures, rack awareness, file distribution, and data integrity.

The system allows users to upload files, which are split into blocks and distributed across multiple nodes according to a configurable replication factor. When nodes fail or replicas are lost/corrupted, the simulator automatically detects the issue and triggers an auto-healing mechanism to restore availability and consistency. This brings concepts like fault tolerance, durability, and high availability to life through real-time visuals.

A major highlight of the project is its futuristic UI/UX, featuring glassmorphism, neon glows, soft transitions, and 3D animated elements. The login screen includes a rotating DFS node graphic, while the dashboard showcases animated clusters, real-time terminal-style logs, glowing block indicators, rack layouts, capacity heatmaps, micro-interactions, and seamless animations during node failures or recovery events.

Users can toggle node status, inject corruption, simulate rack outages, or enable Chaos Mode, which randomly creates faults to test the resilience of the system. The dashboard also includes a floating metrics panel, detailed node information modals, and intelligent replica placement based on load and capacity.

This simulator is perfect for students and developers looking to understand distributed systems practically, build a strong academic project, or create a standout portfolio piece. It combines technical depth with premium UI/UX to make DFS concepts clear, engaging, and visually dynamic.

🌐 Live Demo

View the live app:
➡️ https://dfs-with-fault-tolerance.netlify.app/

🛠 Run Locally
Prerequisites:

Node.js installed

Steps to Run

Install dependencies:

npm install


Set your Gemini API key in .env.local:

GEMINI_API_KEY=your_api_key_here


Start the development server:

npm run dev


# project outlook
<img width="1906" height="850" alt="Screenshot 2025-12-09 141305" src="https://github.com/user-attachments/assets/cc3d91d0-b82d-4a10-813f-b6289c841f35" />
<img width="1910" height="849" alt="Screenshot 2025-12-09 141240" src="https://github.com/user-attachments/assets/202ac790-c457-4a60-877d-f2aa8e4f8621" />
<img width="1910" height="849" alt="Screenshot 2025-12-09 141240" src="https://github.com/user-attachments/assets/bfc42cb9-9fed-4fa6-a2ec-ac2fcfb8a3cf" />

