# Hotel-Booking
This project is based on the mern stack. In this project the client can book any hotels in the world if the hotel is listed with the website 
A full-stack hotel booking system built with React (frontend), Express.js & MongoDB (backend), and Razorpay for payment integration. This platform allows users to browse hotels, check room availability, and make online payments seamlessly.

✨ Features
✅ User-Friendly Interface – Responsive design with a clean UI.
✅ Hotel Listings – Search hotels by city, state, or name.
✅ Room Selection – View room details, pricing, and availability.
✅ Secure Payment – Integrated Razorpay for smooth transactions.
✅ User Authentication – Signup/Login functionality for booking history.
✅ Admin Dashboard – Manage hotels, rooms, and bookings.

🛠 Tech Stack
Frontend: React.js, React Router, Tailwind CSS
Backend: Node.js, Express.js, MongoDB
Authentication: JWT-based authentication
Payments: Razorpay API integration
Deployment: Vercel (Frontend), Render/Heroku (Backend)
🚀 Setup Instructions (MacOS)
1️⃣ Clone the repo:

bash
Copy
Edit
git clone https://github.com/Ankityadav222/hotel-booking.git  
cd hotel-booking
2️⃣ Install dependencies:

bash
Copy
Edit
cd client  
npm install  
cd ../server  
npm install  
3️⃣ Set up environment variables (.env):

bash
Copy
Edit
PORT=8800  
MONGO_URL=your_mongodb_connection  
RAZORPAY_KEY_ID=your_key  
RAZORPAY_KEY_SECRET=your_secret  
4️⃣ Run the project:

bash
Copy
Edit
# Start backend  
cd server  
npm start  

# Start frontend  
cd client  
npm start  
5️⃣ Open the browser and go to:

arduino
Copy
Edit
http://localhost:3000  
📌 Future Enhancements
Add Google OAuth for login
Implement hotel reviews & ratings
Add email notifications for bookings
