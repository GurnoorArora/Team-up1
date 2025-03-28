<h1 align="center">
  <img src="https://user-images.githubusercontent.com/59141533/131732817-23a34498-10d3-4024-9519-d064a67a8482.png" width=50px height=50px />
  Team-up
</h1>

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/GurnoorArora/Team-up1/blob/main/LICENSE)

[Live Link](https://connect-team.herokuapp.com/) | [Demo](https://www.loom.com/share/2079f9206a6d4b31a29a9f1f829bae25)

---

## 🚀 **Overview**

**Team-up** is a MERN stack platform that connects developers looking to form teams for hackathons. It simplifies finding teammates, exploring hackathons, and collaborating efficiently.

---

## 🎯 **The Problem Team-up Solves**

Finding suitable teammates for hackathons can be a challenge. Team-up solves this by:
- Allowing users to **create teams** and specify their skill requirements.
- Enabling users to **search for existing teams** based on filters.
- Displaying detailed **user profiles** for better matching.
- Listing **upcoming hackathons** from platforms like Unstop, Devpost, and Devfolio.

---

## 🚦 **Features**

✅ User and Admin Authentication  
✅ Create and Join Teams  
✅ Real-time Chat Functionality with Teams  
✅ List of Hackathons with filters  
✅ Admin Privileges to Add/Modify Events  
✅ User and Team Profiles  
✅ Socket.io-based Collaboration  

---

## ⚙️ **Tech Stack**

**Frontend:** React.js, Redux, Material UI  
**Backend:** Node.js (Express.js)  
**Database:** MongoDB  
**Other Tools:** Socket.io, AWS S3, Day.js  

---

## 🌐 **Environment Variables**

To run this project, add the following environment variables in the `.env` file at the root:

```plaintext
MONGO_URI=your_mongodb_connection_string  
JWT_SECRET=your_secret_key  
AWS_S3_ACCESS_KEY=your_aws_key  
AWS_S3_SECRET_KEY=your_aws_secret  
AWS_S3_BUCKET_NAME=your_bucket_name  
