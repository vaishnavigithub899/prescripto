
# Doctor Appointment Booking App (MERN Stack)

## 📌 Project Overview
This is a **MERN (MongoDB, Express.js, React.js, Node.js)** stack-based web application that allows patients to book appointments with doctors. The system provides user authentication, role-based access control, and booking appointment scheduling.

## 🚀 Features
- **User Authentication & Authorization** (JWT-based login for Patients and Doctors)
- **Admin Panel** to manage users and appointments
- **Doctor Registration & Approval System**
- **Appointment Booking & Scheduling**
- **Payment Integration** (Razorpay for paid consultations)
- **Profile Management** (Patients & Doctors can update their details)
- **Responsive Design** (Works on all devices)

## 🛠️ Tech Stack
### Frontend:
- React.js (Vite)
- Tailwind CSS (Styling)
- React Router DOM (Navigation)
- Axios (API Requests)

### Backend:
- Node.js
- Express.js
- MongoDB (Mongoose ORM)
- JSON Web Token (JWT Authentication)
- Cloudinary (For profile images upload)

## 🔧 Installation & Setup
### Prerequisites:
Ensure you have the following installed:
- Node.js
- MongoDB
- Git

### Steps to Run Locally
1. **Clone the Repository**
   ```sh
   git clone https://github.com/vaishnavigithub899/prescripto.git
   cd prescripto
   ```

2. **Backend Setup**
   ```sh
   cd backend
   npm install
   npm run server  # Starts the backend server
   ```

3. **Frontend Setup**
   ```sh
   cd frontend
   npm install
   npm run dev  # Runs the frontend
   ```

4. **Environment Variables**
   Create a `.env` file in the backend folder with the following:
   ```env
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   RAZORPAY_SECRET=your_stripe_key
   CLOUDINARY_URL=your_cloudinary_url
   ```

## 🔄 API Endpoints
| Method | Endpoint               | Description                   |
|--------|------------------------|-------------------------------|
| POST   | `/api/auth/register`   | Register new user             |
| POST   | `/api/auth/login`      | Login user                    |
| GET    | `/api/doctors`         | Get all doctors               |
| POST   | `/api/appointments`    | Book an appointment           |
| GET    | `/api/my-appointments`    | Get all appointments          |



## 👨‍💻 Contributors
- [@vaishnavigithub899]

## 💬 Feedback
If you have any suggestions or issues, feel free to open an issue in this repository!



