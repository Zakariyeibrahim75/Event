# 🎉 Eventify


## 📖 Overview

Eventify is a comprehensive event management platform that bridges the gap between event organizers and attendees. With an intuitive interface and powerful backend, Eventify simplifies the entire event lifecycle from creation to attendance tracking.

Whether you're planning a corporate retreat, a tech conference, or a wedding celebration, Eventify provides the tools you need to make your event a success.

## ✨ Features

### For Admins
- 📅 Create and manage events with detailed information
- 👥 Track attendee registrations and engagement
- 📊 View comprehensive event analytics
- 📣 Send notifications to registered attendees
- 🗑️ Delete or modify events as needed

### For Attendees
- 🔍 Discover events with powerful search and filtering
- ✅ Register for events with a single click
- 📱 Receive event updates and notifications
- 📆 View personal event calendar
- 🌟 Rate and review attended events

## 🚀 Getting Started

### Prerequisites

- React (v14.0.0 or higher)
- Python (v3.8 or higher)
- pip (Python package manager)
- npm or yarn

### Installation

#### Clone the repository
\`\`\`bash
git clone https://github.com/yourusername/eventify.git
cd eventify
\`\`\`

#### Backend Setup
\`\`\`bash
# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment variables
cp .env.example .env
# Edit .env with your database credentials and other configurations

# Initialize the database
flask db init
flask db migrate
flask db upgrade

# Start the Flask server
flask run
\`\`\`

#### Frontend Setup
\`\`\`bash
# Navigate to the frontend directory
cd frontend

# Install dependencies
npm install

# Start the development server
npm run dev
\`\`\`

## 🔧 Tech Stack

### Frontend
- **React.js**: For building the user interface
- **React Router**: For navigation and routing
- **Tailwind CSS**: For styling and responsive design
- **Lucide React**: For beautiful icons
- **React Hook Form**: For form handling and validation

### Backend
- **Flask**: Python web framework
- **SQLAlchemy**: ORM for database interactions
- **Flask-JWT-Extended**: For authentication and authorization
- **Flask-CORS**: For handling Cross-Origin Resource Sharing
- **Werkzeug**: For password hashing and security

### Database
- **SQLite** (Development)
- **PostgreSQL** (Production)

## 📱 Application Structure

\`\`\`
eventify/
├── backend/
│   ├── app.py                # Main Flask application
│   ├── models/               # Database models
│   ├── routes/               # API routes
│   ├── services/             # Business logic
│   └── utils/                # Helper functions
│
├── frontend/
│   ├── public/               # Static files
│   └── src/
│       ├── components/       # Reusable UI components
│       ├── pages/            # Page components
│       ├── hooks/            # Custom React hooks
│       ├── utils/            # Utility functions
│       ├── App.jsx           # Main application component
│       └── index.js          # Entry point
│
└── README.md                 # Project documentation
\`\`\`

## 🔄 API Endpoints

### Authentication
- `POST /login` - User login
- `POST /signup` - User registration
- `GET /me` - Get current user information

### Events
- `GET /events` - Get all events
- `GET /events/:id` - Get specific event
- `POST /events` - Create new event
- `PUT /events/:id` - Update event
- `DELETE /events/:id` - Delete event

### Attendees
- `GET /events/:id/attendees` - Get attendees for an event
- `POST /attendees` - Register for an event
- `DELETE /attendees/:id` - Cancel registration

### Notifications
- `POST /notifications` - Send notification to event attendees

## 🎨 Color Palette

Eventify uses a vibrant and accessible color palette:

- Primary: Purple (`#6D28D9`) - Represents creativity and ambition
- Secondary: Pink (`#EC4899`) - Adds warmth and energy
- Accent: Blue (`#3B82F6`) - Conveys trust and reliability
- Background: Gradient from light purple to pink
- Dark Mode: Deep purple to black gradient

## 🛣️ Roadmap

- [ ] Mobile application (React Native)
- [ ] Event ticketing and payment processing
- [ ] QR code check-in system
- [ ] Social media integration
- [ ] Advanced analytics dashboard
- [ ] Multi-language support
- [ ] Offline mode

## 🤝 Contributing

We welcome contributions to Eventify! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgements

- [React](https://reactjs.org/)
- [Flask](https://flask.palletsprojects.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Lucide Icons](https://lucide.dev/)
- All our amazing contributors and users!

---

 Great events don't just happen, they're Eventified!"

