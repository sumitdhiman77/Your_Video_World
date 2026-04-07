# 🎬 YourVideoWorld 

> **A Full-Stack Cloud Video Streaming Platform.** > Live Demo: [View App](https://yourvideoworld.vercel.app) | Repository: [GitHub](https://github.com/sumitdhiman77/yourvideoworld)

## 📌 Overview
YourVideoWorld is a modern streaming solution designed to handle media at scale. It allows users to upload videos to the cloud, manages secure authentication, and delivers content using adaptive streaming technology.

## ✨ Key Features
- 🔐 **Secure Auth:** Session management and protected routes via **NextAuth.js**.
- 🎥 **Adaptive Streaming:** Implemented **HLS.js** for smooth buffer-free video delivery.
- 📤 **Cloud Management:** Automated media uploads and optimization via **Cloudinary**.
- 📱 **Responsive Design:** Fully optimized for mobile, tablet, and desktop using **Tailwind CSS**.

## 🛠️ Technical Implementation
- **Framework:** Next.js 14 (App Router)
- **Language:** TypeScript (Type-safe development)
- **Database:** MongoDB with Mongoose ODM
- **Media Engine:** HLS.js & Video.js for cross-browser compatibility

## 💡 Engineering Challenges & Learnings
- **Challenge:** Handling large video file uploads without crashing the server.
- **Solution:** Integrated Cloudinary’s signed upload presets to offload processing to the cloud.
- **Learning:** Gained deep insight into the **HLS (HTTP Live Streaming)** protocol and media segments.

## ⚙️ Quick Start
1. `git clone https://github.com/sumitdhiman77/yourvideoworld`
2. `npm install`
3. Create a `.env` file with your MongoDB, NextAuth, and Cloudinary keys.
4. `npm run dev`
