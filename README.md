# Real-Time Chat Application

A modern, responsive real-time chat application built with React, featuring user authentication, real-time messaging, image sharing, and online status indicators.

## ✨ Features

- **Real-time Messaging**: Instant message delivery and updates
- **User Authentication**: Secure login and signup system
- **Image Sharing**: Send and receive images in conversations
- **Online Status**: See who's currently online
- **Profile Management**: Update profile picture, name, and bio
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Message History**: View conversation history with timestamps
- **Media Gallery**: Browse shared images in conversations
- **Search Functionality**: Find users quickly with search
- **Unread Message Indicators**: Badge notifications for new messages

## 🚀 Tech Stack

### Frontend
- **React 18** - Modern React with hooks
- **React Router DOM** - Client-side routing
- **Tailwind CSS** - Utility-first CSS framework
- **React Hot Toast** - Beautiful toast notifications
- **Context API** - State management for auth and chat

### Key Dependencies
- `react-router-dom` - Navigation and routing
- `react-hot-toast` - Toast notifications
- `tailwindcss` - Styling

## 📱 Screenshots

### Desktop View
- Clean three-column layout with sidebar, chat area, and user info
- Real-time message updates with smooth scrolling
- Online/offline status indicators

### Mobile View
- Responsive single-column layout
- Touch-friendly interface
- Optimized for mobile messaging

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/chat-app.git
   cd chat-app
   ```

2. **Install dependencies**
   ```bash
   cd client
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## 📂 Project Structure

```
client/
├── src/
│   ├── components/
│   │   ├── ChatContainer.jsx    # Main chat interface
│   │   ├── SideBar.jsx         # User list and search
│   │   └── RightSideBar.jsx    # User info and media
│   ├── pages/
│   │   ├── HomePage.jsx        # Main chat page
│   │   ├── LoginPage.jsx       # Authentication
│   │   └── ProfilePage.jsx     # Profile management
│   ├── context/
│   │   ├── AuthContext.jsx     # Authentication state
│   │   └── ChatContext.jsx     # Chat functionality
│   ├── lib/
│   │   └── utils.js           # Utility functions
│   ├── assets/               # Images and icons
│   ├── App.jsx              # Main app component
│   └── main.jsx             # App entry point
└── public/
    └── bgImage.svg          # Background image


chat-app/
├── server/
│   ├── controllers/
│   │   ├── messageController.js     # Message CRUD operations, real-time messaging
│   │   └── userController.js        # User authentication, profile management
│   ├── lib/
│   │   ├── cloudinary.js           # Cloudinary configuration for image uploads
│   │   ├── db.js                   # MongoDB connection setup
│   │   └── utils.js                # JWT token generation utilities
│   ├── middleware/
│   │   └── auth.js                 # JWT authentication middleware
│   ├── models/
│   │   ├── Message.js              # Message schema (text, image, seen status)
│   │   └── User.js                 # User schema (profile, authentication)
│   ├── routes/
│   │   ├── messageRoutes.js        # Message API endpoints
│   │   └── userRoutes.js           # User API endpoints
│   └── server.js                   # Main server file with Socket.IO setup
├── client/                         # Frontend application files
├── .env                           # Environment variables
├── package.json                   # Dependencies and scripts
└── README.md                      # Project documentation

```

## 🎯 Key Components

### Authentication System
- **Login/Signup**: Secure user authentication
- **Profile Management**: Update profile information and avatar
- **Protected Routes**: Route guards for authenticated users

### Chat Features
- **Real-time Messaging**: Instant message delivery
- **Image Sharing**: Upload and share images
- **Message History**: Persistent conversation history
- **Online Status**: Real-time online/offline indicators

### User Interface
- **Responsive Design**: Mobile-first approach
- **Modern UI**: Clean, gradient-based design
- **Smooth Animations**: Polished user experience
- **Toast Notifications**: User feedback for actions

## 🔧 Configuration

### Environment Setup
The application uses Context API for state management. Make sure to:

1. Set up your backend API endpoints
2. Configure authentication endpoints
3. Set up real-time connection (WebSocket/Socket.io)

### Styling
- **Tailwind CSS** for responsive design
- **Custom gradients** for modern UI elements
- **Google Fonts** (Outfit) for typography
- **Hidden scrollbars** for clean appearance

## 📋 Usage

### Getting Started
1. **Sign Up**: Create a new account with email and bio
2. **Login**: Access your account
3. **Find Users**: Search for other users in the sidebar
4. **Start Chatting**: Click on a user to begin conversation
5. **Share Media**: Send images using the gallery icon
6. **Update Profile**: Modify your profile information anytime

### Features Guide
- **Send Messages**: Type and press Enter to send
- **Share Images**: Click gallery icon to upload images
- **View Online Status**: Green dot indicates online users
- **Browse Media**: View shared images in the right sidebar
- **Search Users**: Use the search bar to find specific users

## 🎨 Design Philosophy

- **Glassmorphism**: Backdrop blur effects for modern aesthetics
- **Purple Gradient Theme**: Consistent color scheme throughout
- **Mobile-First**: Responsive design prioritizing mobile experience
- **Clean Typography**: Outfit font family for readability
- **Intuitive UX**: User-friendly interface with clear navigation

## 🔄 State Management

The application uses React Context API for:
- **AuthContext**: User authentication and profile data
- **ChatContext**: Message handling and user selection
- **Real-time Updates**: Live message and status updates

## 📱 Responsive Features

- **Adaptive Layout**: Different layouts for mobile and desktop
- **Touch Optimization**: Mobile-friendly interactions
- **Flexible Grid**: CSS Grid for responsive chat interface
- **Conditional Rendering**: Show/hide elements based on screen size

## 🚀 Performance

- **Smooth Scrolling**: Auto-scroll to latest messages
- **Image Optimization**: Efficient image handling and display
- **Context Optimization**: Efficient state management
- **File Reading**: Browser FileReader API for image uploads

## 🔒 Security Features

- **Protected Routes**: Authentication-based navigation
- **File Validation**: Image file type checking
- **Input Sanitization**: Safe message handling
- **Secure Upload**: Base64 image encoding

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- React team for the amazing framework
- Tailwind CSS for the utility-first CSS framework
- React Hot Toast for beautiful notifications
- Google Fonts for typography

## 📞 Support

If you have any questions or need help, please:
- Open an issue on GitHub
- Check the documentation
- Contact the maintainers

---

**Made with ❤️ using React and Tailwind CSS**
