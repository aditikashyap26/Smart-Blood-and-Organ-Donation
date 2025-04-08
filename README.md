
# 🩸 Smart Blood and Organ Donation System

A full-stack web application designed to intelligently manage and synchronize blood and organ donation activities based on **urgency, availability, and compatibility**. The system ensures that critical cases are prioritized efficiently, enhancing the chances of timely donations and saving lives.

## 🚀 Features

- 🗂️ **Donor & Recipient Registration**
- 🧠 **Smart Matching Algorithm** for Blood and Organ compatibility
- 📍 **Real-time Availability Tracking** of Blood Units and Organs
- ⏱️ **Priority-Based Allocation** (using factors like blood group, organ type, medical urgency)
- 📊 **Admin Dashboard** for Monitoring and Analytics
- 🌐 **Responsive Frontend** using React

## 🧰 Tech Stack

### Frontend:
- **React.js**
- **Axios** (for API communication)
- **React Router** (for navigation)
- **Bootstrap/Tailwind CSS** (for responsive design)

### Backend (Optional if already defined):
- **Node.js** with **Express.js**
- **MongoDB** (NoSQL database for storing user and donation data)
- **JWT** (for authentication)
- **Mongoose** (for schema modeling)

## 🏗️ System Architecture

```
[User (Donor/Recipient)] <---> [React Frontend] <---> [Node/Express Backend API] <---> [MongoDB Database]
                                                                  |
                                                        [Matching & Priority Logic]
```

## 🧪 Matching Algorithm Logic (Simplified)

1. **Blood Donation**:
   - Matches donor and recipient by **blood group compatibility**.
   - Filters based on **availability** and **location proximity**.
   - Assigns donations by **urgency level**.

2. **Organ Donation**:
   - Matches based on **organ type**, **medical urgency**, **age**, **tissue type**, and **waiting time**.
   - Prioritization ensures the **most critical and compatible patient** receives the donation.

## 📦 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/aditikashyap26/Smart-Blood-and-Organ-Donation
cd Smart-Blood-and-Organ-Donation
```

### 2. Install Frontend Dependencies
```bash
cd client
npm install
npm start
```

### 3. Install Backend Dependencies(Upcoming in progress)
```bash
cd server
npm install
npm run dev
```

## 📈 Future Enhancements

- The Organ donation Integration is currently under working with backend integration.
- Integrate with **Government Health Databases**
- Add **SMS/Email Notifications** for match alerts
- Use **AI for more accurate organ matching**
- Add **Google Maps API** to calculate hospital/donor proximity

