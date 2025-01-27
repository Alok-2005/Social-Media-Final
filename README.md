# 📸 Social Gallery Hub

A modern, responsive web application for users to share and showcase their social media content through an intuitive gallery interface. Built with React, Node.js, and MongoDB.

![Project Preview
![Screenshot 2025-01-27 223905](https://github.com/user-attachments/assets/4ac93de0-168d-424b-a937-cac293f53d5e)![image](https://github.com/user-attachments/assets/7a590cd5-c4e4-4202-8873-af5d83f1f5bf)



## ✨ Features

- **Real-time Image Upload**: Seamless multi-image upload with preview and remove capabilities
- **Social Media Integration**: Group submissions by social media handles for organized content display
- **Responsive Gallery**: Beautiful, grid-based gallery with smooth animations and transitions
- **Dark Mode Support**: Full dark mode implementation for better user experience
- **Admin Dashboard**: Comprehensive dashboard to manage and view all submissions
- **Image Modal View**: Click to view images in full-size modal with backdrop blur effect

## 🚀 Tech Stack

### Frontend
- React.js with Hooks
- Framer Motion for animations
- Tailwind CSS for styling
- Lucide React for icons
- Axios for API requests

### Backend
- Node.js & Express
- MongoDB with Mongoose
- Multer for file uploads
- CORS support
- Environment variable configuration

## 🛠️ Installation

1. **Clone the repository**
```
git clone https://github.com/yourusername/social-gallery-hub.git
cd social-gallery-hub
```

2. **Install dependencies**
```
# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```

3. **Environment Setup**
```
# In the server directory, create a .env file
MONGODB_URI=your_mongodb_connection_string
PORT=5000
BASE_URL=http://localhost:5000
```

4. **Create upload directory**
```
# In the server directory
mkdir uploads
```

## 🚀 Running the Application

1. **Start the backend server**
```
cd server
npm start
```

2. **Start the frontend development server**
```
cd client
npm start
```

The application will be available at `http://localhost:3000`

## 📱 Usage

### Submitting Content
1. Navigate to the Submit tab
2. Fill in your name and social media handle
3. Upload up to 5 images (drag & drop supported)
4. Submit your content

### Viewing Gallery
1. Switch to the Admin Dashboard tab
2. Browse through submissions grouped by social handle
3. Click images to view them in full size
4. Use the refresh button to see new submissions

## 🔑 Key Features Explained

### Automatic Content Grouping
- Images from the same social handle are automatically grouped together
- New submissions from existing users are merged with their previous content
- Latest submission dates are tracked and displayed

### Responsive Design
- Fully responsive layout that works on all device sizes
- Grid system automatically adjusts based on screen width
- Touch-friendly interface for mobile users

### Performance Optimizations
- Lazy loading of images
- Efficient state management
- Optimized animations for smooth performance

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Framer Motion](https://www.framer.com/motion/) for amazing animations
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Lucide Icons](https://lucide.dev/) for beautiful icons
- [MongoDB](https://www.mongodb.com/) for the database


---

⭐️ If you found this project helpful, please give it a star!
