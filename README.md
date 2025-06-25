💸 Expense Management System (MERN Stack)

🔗 Vercel Frontend: https://expense-tracker-app-three-beryl.vercel.app/
📂 GitHub Repo: [Expense Tracker App](https://github.com/Sunnykumar2247/Track_the_Expense)

📌 Project Description
The Expense Management System is a web-based application built with the MERN Stack (MongoDB, Express, React, Node). It enables users to track and manage daily expenses efficiently with an intuitive interface and powerful reporting features.

🎯 Objectives
Simplify expense tracking for individuals and teams.

Provide insights into spending habits via reports and charts.

Allow CRUD operations on expenses and categories.

Support visual reports for budgeting and financial planning.

🚀 Features
✅ User Authentication & Authorization
Secure sign-up and login with JWT-based authentication.

Role-based access for admin/user separation.

💼 Expense & Category Management
Add, edit, delete expenses and categories.

Filter by date, category, and description.

Upload receipts or attach documents.

📊 Dashboard & Reporting
View overall spending statistics (pie/bar charts).

Report generation by date range and category.

Recent transactions and category-based summaries.

📱 Responsive UI
Built with React.js, Bootstrap, and Material Icons.

Fully responsive on desktop, tablet, and mobile.

Animated background with tsparticles.

⚙️ Technical Stack
Layer	Tech Used
Frontend	React.js, Redux, React-Bootstrap, tsparticles, Material Icons
Backend	Node.js, Express.js, JWT, bcrypt
Database	MongoDB with Mongoose ORM
Deployment	AWS Amplify (Frontend), Render (Backend), Vercel (Optional frontend)

🧩 Technical Architecture
React.js for dynamic UI and reusable components.

Express.js REST API to handle client-server interaction.

JWT Auth with middleware to secure protected routes.

MongoDB for persistent data storage and easy scaling.

⚙️ Running Locally
bash
Copy
Edit
# Clone repository
git clone (https://github.com/Sunnykumar2247/Track_the_Expense)
cd Expense-Tracker-App
🔧 Setup Frontend
bash
Copy
Edit
cd frontend
npm install
npm start
🔧 Setup Backend
bash
Copy
Edit
cd ../backend
npm install
npm run dev
🌐 Environment Variables
Create a file at backend/config/config.env with:

env
Copy
Edit
MONGO_URL=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_jwt_secret
📸 Screenshots
Add screenshots here:

sql
Copy
Edit
📷 App Screenshot 1  
📷 App Screenshot 2  
📷 Dashboard  
📷 Report Visualization  
📷 Mobile View  
🧪 CI/CD & Deployment
Frontend hosted on AWS Amplify and Vercel.

