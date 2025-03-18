# Real Estate App

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

A modern, full-stack real estate application built with Next.js, MongoDB, and Tailwind CSS. This application allows users to browse, search, and list properties for sale or rent.

## 📋 Features

- **Property Listings**: Browse and search for properties with detailed information
- **User Authentication**: Secure user registration and login system
- **Property Management**: Add, edit, and delete your property listings
- **Search Functionality**: Find properties by location, price range, and more
- **Responsive Design**: Beautiful UI that works on desktop and mobile devices
- **Image Uploads**: Support for property image uploads

## 🚀 Live Demo

Check out the live demo of the application [here](#) (Replace with your live demo link)

## 📺 Tutorial

This project was built following the comprehensive tutorial by [masynctech](https://www.youtube.com/@masynctech):

[![Real Estate App Tutorial](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/watch?v=KstreYjn1N0)

## 🛠️ Technologies Used

- **Frontend**:
  - Next.js (App Router)
  - React
  - Tailwind CSS
  - Bricolage Grotesque Font
  - React Icons

- **Backend**:
  - MongoDB
  - Next.js API Routes
  - JWT Authentication

- **Deployment**:
  - Vercel (optional)

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/real-estate-app.git
   cd real-estate-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env.local` file in the root directory with the following variables:
   ```
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   NEXT_PUBLIC_SITE_URL=http://localhost:3000
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application

## 📁 Project Structure

```
/
├── app/                # Next.js app directory
│   ├── api/            # API routes
│   ├── components/     # React components
│   ├── properties/     # Property-related pages
│   ├── globals.css     # Global styles
│   └── layout.js       # Root layout
├── components/         # Shared components
├── lib/                # Utility functions and libraries
├── models/             # MongoDB models
├── public/             # Static assets
└── styles/             # Additional CSS styles
```

## 🔐 Authentication

The application uses JWT (JSON Web Tokens) for authentication. Users can:
- Register a new account
- Log in with existing credentials
- Access protected routes like adding properties

## 📱 Responsive Design

The application is fully responsive and optimized for:
- Mobile devices
- Tablets
- Desktop browsers

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- [masynctech](https://www.youtube.com/@masynctech) for the amazing tutorial
- [Next.js](https://nextjs.org/) for the React framework
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [MongoDB](https://www.mongodb.com/) for the database
- All the open-source libraries used in this project

---

Built with ❤️ following [masynctech's tutorial](https://www.youtube.com/watch?v=KstreYjn1N0)
