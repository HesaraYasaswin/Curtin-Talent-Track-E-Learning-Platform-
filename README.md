# CurtinTalentTrack

<div align="center">
  <img src="https://img.shields.io/badge/Version-2.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/Status-Development-yellow.svg" alt="Status">
  <img src="https://img.shields.io/badge/MERN-Stack-green.svg" alt="MERN Stack">
  <img src="https://img.shields.io/badge/License-MIT-red.svg" alt="License">
</div>

<div align="center">
  <h3>Empowering Communication Skills in the Curtin Community</h3>
  <p>A comprehensive web platform designed to enhance public speaking, written communication, and critical thinking skills for students, faculty, and alumni.</p>
</div>

---

## Project Screenshots

### Dashboard Overview
```
[Add your dashboard screenshot here]
<!-- Example: ![Dashboard](./screenshots/dashboard.png) -->
```

### Public Speaking Practice
```
[Add your public speaking interface screenshot here]
<!-- Example: ![Public Speaking](./screenshots/public-speaking.png) -->
```

### Written Communication Hub
```
[Add your written communication interface screenshot here]
<!-- Example: ![Written Communication](./screenshots/written-comm.png) -->
```

### Critical Thinking Exercises
```
[Add your critical thinking interface screenshot here]
<!-- Example: ![Critical Thinking](./screenshots/critical-thinking.png) -->
```

---

## Features

### Core Functionalities

| Feature | Description | Status |
|---------|-------------|--------|
| **User Authentication** | Secure login/registration system | Complete |
| **Profile Management** | Personalized user profiles | Complete |
| **Public Speaking Practice** | Record & submit speeches (max 5 min) | In Progress |
| **Interview Simulation** | Mock interview sessions with feedback | In Progress |
| **Written Communication** | Email, CV, letter practice | In Progress |
| **Critical Thinking Quizzes** | Interactive problem-solving exercises | In Progress |
| **Event Management** | Create and manage community events | In Progress |
| **Admin Dashboard** | Comprehensive system management | In Progress |

### Key Features

- **Responsive Design** - Works seamlessly across all devices
- **Real-time Notifications** - Instant feedback and updates
- **Progress Tracking** - Monitor your skill development journey
- **Expert Evaluation** - Professional feedback from qualified evaluators
- **Role-based Access** - Tailored experiences for Users, Evaluators, and Admins

---

## Technology Stack

<div align="center">
  <table>
    <tr>
      <td align="center" width="25%">
        <h3>Frontend</h3>
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" width="50" height="50"/>
        <br><strong>React.js</strong>
        <br>Modern UI Library
      </td>
      <td align="center" width="25%">
        <h3>Backend</h3>
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" width="50" height="50"/>
        <br><strong>Node.js</strong>
        <br>Runtime Environment
      </td>
      <td align="center" width="25%">
        <h3>Framework</h3>
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express" width="50" height="50"/>
        <br><strong>Express.js</strong>
        <br>Web Framework
      </td>
      <td align="center" width="25%">
        <h3>Database</h3>
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB" width="50" height="50"/>
        <br><strong>MongoDB</strong>
        <br>NoSQL Database
      </td>
    </tr>
  </table>
</div>

### Additional Technologies
- **Styling**: CSS3, Tailwind CSS
- **Authentication**: JWT (JSON Web Tokens)
- **File Storage**: Multer for file uploads
- **API**: RESTful API design
- **Testing**: Jest, React Testing Library

---

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (Local or Atlas)
- Git

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/curtin-talent-track.git
   cd curtin-talent-track
   ```

2. **Install Backend Dependencies**
   ```bash
   cd backend
   npm install
   ```

3. **Install Frontend Dependencies**
   ```bash
   cd ../frontend
   npm install
   ```

4. **Environment Setup**
   
   Create `.env` file in the backend directory:
   ```env
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   PORT=5000
   NODE_ENV=development
   EMAIL_SERVICE=your_email_service
   EMAIL_USER=your_email
   EMAIL_PASS=your_email_password
   ```

5. **Run the Application**
   
   Backend (Terminal 1):
   ```bash
   cd backend
   npm run dev
   ```
   
   Frontend (Terminal 2):
   ```bash
   cd frontend
   npm start
   ```

6. **Access the Application**
   - Frontend: `http://localhost:3000`
   - Backend API: `http://localhost:5000`

---

## Project Structure

```
curtin-talent-track/
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── utils/
│   │   └── App.js
│   └── package.json
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   └── server.js
├── screenshots/
├── README.md
└── .gitignore
```

---

## User Roles

### Students/Alumni (Users)
- Practice public speaking with video uploads
- Participate in mock interviews
- Complete written communication exercises
- Take critical thinking quizzes
- Register for community events

### Evaluators
- Review and provide feedback on submissions
- Grade written assignments
- Conduct mock interview sessions
- Track evaluation history

### Administrators
- Manage user accounts and roles
- Create and organize events
- Monitor system analytics
- Manage content and resources

---

## Contributing

We welcome contributions from the community! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Contribution Guidelines
- Follow the existing code style
- Write meaningful commit messages
- Include tests for new features
- Update documentation as needed

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Support & Contact

- **Email**: curtintalenttrack@curtin.edu.au
- **University**: Curtin University, Colombo Campus
- **Course**: ISAD 3000 - Capstone Computing Project 1

---

<div align="center">
  <h3>Empowering the Curtin Community, One Skill at a Time</h3>
  
  <img src="https://img.shields.io/badge/Made%20with-MERN-blue" alt="Made with MERN">
  <img src="https://img.shields.io/badge/Curtin-University-red" alt="Curtin University">
  <img src="https://img.shields.io/badge/Education-Technology-green" alt="EdTech">
</div>

---

**Star this repository if you find it helpful!**
