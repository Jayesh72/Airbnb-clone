# WanderStay 🏕️
A full-stack travel accommodation listing platform. Built using **Node.js**, **Express**, **MongoDB**, **EJS**.

---

## 🚀 Features

- 🏡 Create, update, and delete property listings
- 📷 Image upload with Cloudinary
- 👤 User authentication and authorization (login/signup)
- 💬 Leave and delete reviews on listings
- 🔒 Session-based user access control with Passport.js
- 📱 Fully responsive frontend (EJS + Bootstrap)

---

## 🛠️ Tech Stack

| Technology | Description |
|------------|-------------|
| **Node.js** | Server-side JavaScript runtime |
| **Express** | Web framework for Node.js |
| **MongoDB** | NoSQL database for storing listings, users, reviews |
| **Mongoose** | ODM for MongoDB |
| **EJS** | Templating engine for rendering views |
| **Cloudinary** | Image hosting and manipulation |
| **Passport.js** | Authentication middleware |

---

## 📸 Screenshots

![image](https://github.com/user-attachments/assets/d52aa9cd-51db-4349-ae02-14cc1cc4685b)
![image](https://github.com/user-attachments/assets/4cfdc495-2a47-4e7c-80df-92cdbfd88981)
![image](https://github.com/user-attachments/assets/7c60da4a-cc37-41ef-8ceb-7d10b58c749d)

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/Jayesh72/Airbnb-clone.git

# Navigate to the project directory
cd wanderstay

# Install dependencies
npm install

# Create a .env file and add the following:
ATLASDB_URL=your_mongodb_connection
CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_key
CLOUD_API_SECRET=your_secret

# Start the server
node app.js
