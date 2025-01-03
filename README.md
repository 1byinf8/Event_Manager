# Event Manager

A Node.js application for managing events, scheduling, and attendee coordination.

## 🚀 Features

- Create and manage events with detailed information
- Track attendee registrations and RSVPs
- Handle event scheduling and calendar integration
- Real-time updates for event changes
- User authentication and authorization
- Event categories and tagging system
- Search and filter events
- Email notifications for event updates

## 📋 Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MongoDB (v4.4 or higher)
- Modern web browser

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/1byinf8/Event_Manager.git
cd Event_Manager
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your environment variables:
```env
PORT=3000
MONGODB_URI=mongodb://localhost:27017/event_manager
JWT_SECRET=your_jwt_secret
SMTP_HOST=your_smtp_host
SMTP_PORT=587
SMTP_USER=your_email
SMTP_PASS=your_password
```

## 🚦 Running the Application

### Development Mode
```bash
npm run dev
```

### Production Mode
```bash
npm run build
npm start
```

The application will be available at `http://localhost:3000`

## 📚 API Documentation

### Authentication Endpoints

```
POST /api/auth/register - Register new user
POST /api/auth/login - User login
POST /api/auth/logout - User logout
```

### Event Endpoints

```
GET /api/events - Get all events
GET /api/events/:id - Get specific event
POST /api/events - Create new event
PUT /api/events/:id - Update event
DELETE /api/events/:id - Delete event
```

### User Endpoints

```
GET /api/users/profile - Get user profile
PUT /api/users/profile - Update user profile
GET /api/users/events - Get user's events
```

## 🏗️ Project Structure

```
Event_Manager/
├── src/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   └── utils/
├── tests/
├── .env
├── .gitignore
├── package.json
└── README.md
```

## 🧪 Testing

Run the test suite:
```bash
npm test
```

Run tests with coverage:
```bash
npm run test:coverage
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- @1byinf8 - Initial work and maintenance

## 🙏 Acknowledgments

- Node.js community
- Express.js team
- MongoDB team
- All contributors who help improve this project

## 📞 Support

For support, please open an issue in the GitHub repository or contact the maintainers.

## 🔄 Updates

Check the [CHANGELOG](CHANGELOG.md) for information about the latest updates and versions.
