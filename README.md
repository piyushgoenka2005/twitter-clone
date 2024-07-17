## Twitter Clone

### Project Description

This project is a full-stack Twitter Clone that replicates key functionalities of the popular social media platform, Twitter. The project is built using modern web technologies and follows best practices for both frontend and backend development.

### Features

- **User Authentication**: Secure sign-up, login, and logout functionalities using Passport.js.
- **User Profiles**: Personal profile pages for each user, including the ability to update profile information.
- **Tweeting**: Users can create, read, and delete tweets.
- **Follow System**: Users can follow and unfollow other users, with a feed displaying tweets from followed users.
- **Likes**: Users can like on tweets.
- **Real-time Updates**: Real-time notifications and updates using WebSockets.
- **Responsive Design**: A fully responsive design implemented with Tailwind CSS and Bootstrap, ensuring usability across various devices.

### Technologies Used

- **Frontend**: React JS, Tailwind CSS, HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js,
- **Database**: MongoDB
- **APIs**: RESTful API implementation for communication between the frontend and backend
- **Authentication**: Passport.js for secure user authentication

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/piyushgoenka2005/twitter-clone.git
   cd twitter-clone
   ```

2. **Install dependencies for both frontend and backend**:
   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. **Setup environment variables**: Create a `.env` file in the backend directory and add the necessary environment variables (e.g., database connection strings, API keys).

4. **Run the application**:
   ```bash
   # Start the backend server
   cd backend
   npm start

   # Start the frontend server
   cd ../frontend
   npm start
   ```

### Usage

- Visit `http://localhost:3000` to access the frontend.
- Use the API endpoints provided in the backend for various functionalities.

### Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

### Acknowledgements

- Thanks to the developers of the various libraries and frameworks used in this project.
- Inspired by the functionality and design of the original Twitter platform.

---
