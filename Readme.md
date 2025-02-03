# **Home Rental Project**

## **Overview**
The **Home Rental Project** is a full-stack web application that facilitates the rental of properties. Users can browse available properties, contact landlords, and manage rental agreements. The project is built using the **MERN (MongoDB, Express, React, Node.js) stack**.

## **Features**
- **User Authentication:** Secure login and registration for users and landlords.
- **Property Listings:** Users can browse and search for available properties.
- **Booking System:** Renters can book properties and schedule visits.
- **Landlord Dashboard:** Property owners can list, edit, and manage their rental properties.
- **Payment Integration:** Online payment options for renting properties.
- **Reviews & Ratings:** Users can leave feedback on properties and landlords.

## **Technologies Used**
- **Frontend:** React.js, Redux, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Token)
- **Payment Gateway:** Stripe (or any preferred payment provider)
- **Hosting:** Vercel (Frontend), Render/Heroku (Backend)

## **Installation**
### **Prerequisites**
- **Node.js (Latest version)**
- **MongoDB (Locally or using MongoDB Atlas)**
- **Git**

### **Setup Instructions**
1. **Clone the repository:**
   ```sh
   git clone https://github.com/Ramishworsah/MearnProject.git
   cd MearnProject
   ```
2. **Install backend dependencies:**
   ```sh
   cd backend
   npm install
   ```
3. **Configure environment variables:**
   - Create a `.env` file in the backend directory.
   - Add the following variables:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     STRIPE_SECRET_KEY=your_stripe_secret_key
     ```
4. **Start the backend server:**
   ```sh
   npm start
   ```
5. **Install frontend dependencies:**
   ```sh
   cd ../FrontEnd
   npm install
   ```
6. **Start the frontend server:**
   ```sh
   npm start
   ```

## **Usage**
- Visit `http://localhost:3000/` to access the frontend.
- Use the landlord dashboard to add property listings.
- Renters can search and book properties.
- Payments can be processed through the integrated payment gateway.

## **Contributing**
Pull requests are welcome. Please follow these steps:
1. **Fork the repository.**
2. **Create a feature branch (`git checkout -b feature-branch`).**
3. **Commit your changes (`git commit -m 'Add new feature'`).**
4. **Push to the branch (`git push origin feature-branch`).**
5. **Open a pull request.**



## **Contact**
For any queries or issues, feel free to reach out:
- **GitHub:** [Ramishworsah](https://github.com/Ramishworsah)
- **Email:** 2203051050822@paruluniversity.ac.in
