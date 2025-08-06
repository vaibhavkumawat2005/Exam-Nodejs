

  <h1>🗂️ Task Manager App</h1>
  <p>
    A full-stack Task Management System built with <strong>Node.js</strong>, <strong>Express</strong>, <strong>MongoDB</strong>, and <strong>EJS</strong>. It includes JWT authentication, role-based access (admin/user), category management, task management, and a minimalist glassmorphism UI.
  </p>

  <h2>✨ Features</h2>
  <ul>
    <li>✅ User Authentication (Login/Register)</li>
    <li>🔐 JWT Token + Cookie-based Authentication</li>
    <li>👥 Role-based Access (Admin & User)</li>
    <li>📝 Task Management (Create, Edit, Delete, List)</li>
    <li>🗂️ Category Management</li>
    <li>🔍 Multi-user support</li>
    <li>🌙 Glassmorphism Dark UI using custom CSS</li>
    <li>🧩 Modular architecture (Controllers, Models, Routes, Middleware, Views)</li>
  </ul>

   <h2> Screenshot </h2>
<img width="1919" height="966" alt="Screenshot 2025-08-06 105101" src="https://github.com/user-attachments/assets/c8d415ef-bd09-4312-a7ff-3bb8a1f43d4d" />
<img width="1918" height="972" alt="Screenshot 2025-08-06 105045" src="https://github.com/user-attachments/assets/974b6102-fc75-4220-9f71-4874de295a89" />
<img width="1901" height="970" alt="Screenshot 2025-08-06 105444" src="https://github.com/user-attachments/assets/23cfce1e-3d43-40c8-8885-ad8d00829fed" />
<img width="1901" height="968" alt="Screenshot 2025-08-06 105508" src="https://github.com/user-attachments/assets/c8a481ca-b9fa-4c0c-816e-6114a42a4b35" />
    <img width="1904" height="968" alt="Screenshot 2025-08-06 105522" src="https://github.com/user-attachments/assets/f379b395-e9fc-4b5c-adcc-18815e6628f1" />


  

  <h2>📁 Project Structure</h2>
  <div class="codeblock">
    <pre>
task-manager/
├── controllers/
│   ├── authController.js
│   ├── taskController.js
│   └── categoryController.js
├── middleware/
│   └── authMiddleware.js
├── models/
│   ├── User.js
│   ├── Task.js
│   └── Category.js
├── public/
│   └── style.css
│  
├── routes/
│   ├── authRoutes.js
│   ├── taskRoutes.js
│   └── categoryRoutes.js
├── views/
│   ├── partials/
│   │   └── navbar.ejs
│   │   └── taskitem.ejs
│   ├── categoryList.ejs
│   ├── login.ejs
│   ├── register.ejs
│   └── taskForm.ejs
│   └── taskList.ejs
│   
├── config/
│   └── config.js
├── app.js
└── package.json
    </pre>
  </div>

  <h2>🚀 Installation & Usage</h2>

  <h3>1. Clone the Repository</h3>
  <div class="codeblock"><code>git clone https://github.com/yourusername/task-manager.git</code></div>

  <h3>2. Install Dependencies</h3>
  <div class="codeblock"><code>npm install</code></div>

  <h3>3. Configure MongoDB Connection</h3>
  <div class="codeblock">
    <pre>
module.exports = {
  MONGO_URI: "your_mongo_db_uri",
  JWT_SECRET: "your_jwt_secret_key",
  PORT: 5000
};
    </pre>
  </div>

  <h3>4. Start the Server</h3>
  <div class="codeblock"><code>npm start</code></div>

  <p>Visit <a href="http://localhost:5000">http://localhost:5000</a> in your browser.</p>

  <h2>👨‍💻 Tech Stack</h2>
  <ul>
    <li><strong>Backend:</strong> Node.js, Express.js</li>
    <li><strong>Database:</strong> MongoDB + Mongoose</li>
    <li><strong>Frontend:</strong> EJS Templates</li>
    <li><strong>Authentication:</strong> JWT + Cookies</li>
    <li><strong>Styling:</strong> Custom CSS (Glassmorphism + Light Mode)</li>
  </ul>

  <h2>🔐 Roles & Access</h2>
  <table>
    <thead>
      <tr>
        <th>Role</th>
        <th>Features</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>User</td>
        <td>Login, Manage personal tasks</td>
      </tr>
      <tr>
        <td>Admin</td>
        <td>Manage users, categories, and view all user tasks</td>
      </tr>
    </tbody>
  </table>

  <h2>🧪 TODO / Improvements</h2>
  <ul>
    <li>[ ] Task priority & due date</li>
    <li>[ ] Task completion status toggle</li>
    <li>[ ] Admin dashboard metrics</li>
    <li>[ ] Responsive UI enhancements</li>
    <li>[ ] Email verification (optional)</li>
  </ul>


  <h2>📬 Contact</h2>
  <p><strong>Author:</strong> Vaibhav</p>
  <p><strong>Email:</strong> kumawatvaibhav05@gamil.com</p>
  <p><strong>GitHub:</strong> <a href="https://github.com/yourusername">vaibhavkumawat2005 </a></p>


