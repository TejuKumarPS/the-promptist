# The Promptist 🎨

A full-stack MERN application that generates unique, AI-powered images from text prompts. Users can browse creations and share their own.

---

## 🚀 Live Demo

[**View the live application here!**](https://the-promptist.netlify.app/)

---

## 🌟 Features

* **Text-to-Image Generation:** Create stunning images by providing a descriptive text prompt.
* **Community Gallery:** Browse a gallery of images created by other users.
* **Share Your Creations:** Share your favorite generated images with the community.
* **Responsive Design:** A clean and modern UI that works on all devices.
* **Download Images:** Save your favorite generated images directly to your device.

---

## 🛠️ Tech Stack

This project is a full-stack MERN application.

* **Frontend:** React, Vite, Tailwind CSS, FileSaver.js
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (with Mongoose)
* **Services:**
    * Workers AI API
    * **Cloudinary** for image hosting and management
* **Deployment:**
    * Frontend on Netlify
    * Backend on Render
    * Database on MongoDB Atlas

---

## ⚙️ Getting Started

To get a local copy up and running, follow these simple steps.

### ### Prerequisites

* Make sure you have Node.js and npm installed on your machine.
* npm
    ```sh
    npm install npm@latest -g
    ```
* Login to cloudinary and generate api key for storing images in the cloud.
* Login to account in cloudflare and create a serverless api in it.
  Refer to this youtube video:
  [(https://img.youtube.com/vi/VliEpQl06pE/0.jpg)](https://www.youtube.com/watch?v=VliEpQl06pE)

### ### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/TejuKumarPS/the-promptist.git](https://github.com/TejuKumarPS/the-promptist.git)
    cd the-promptist
    ```

2.  **Set up the Backend (Server):**
    ```sh
    cd Server
    npm install
    ```
    *Create a `.env` file in the `Server` directory and add your environment variables (see below).*
    ```sh
    npm start
    ```

3.  **Set up the Frontend:**
    *Open a new terminal window.*
    ```sh
    cd Frontend
    npm install
    ```
    *Create a `.env` file in the `Frontend` directory and add your environment variables.*
    ```sh
    npm run dev
    ```

---

## 🔑 Environment Variables

To run this project, you will need to add the following environment variables to your `.env` files. **Do not commit these files to GitHub.**

* **In `/Server/.env`:**
    ```
    MONGODB_URI=your_mongodb_connection_string
    CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_api_secret
    ```

* **In `/Frontend/.env`:**
    ```
    VITE_WORKER_URL=your_worker_api_url
    VITE_API_KEY=your_worker_api_key
    ```

---

## 📬 Contact

Teju Kumar - [tejukumar257@gmail.com]

Project Link: [https://github.com/TejuKumarPS/the-promptist](https://github.com/TejuKumarPS/the-promptist)


