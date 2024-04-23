# [Instagram Clone - MERN Stack](https://www.youtube.com/playlist?list=PLB97yPrFwo5g0FQr4rqImKa55F_aPiQWk)

> This is a full-stack Instagram clone built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It replicates the core features of Instagram, allowing users to sign up, upload photos, follow other users, like and comment on posts, and explore a feed of posts from users they follow.

## Features

- **User Authentication**: Users can sign up, log in, and log out securely.
- **Profile Management**: Users can edit their profile information, including their username, bio, and profile picture.
- **Post Creation**: Users can upload photos with captions and post them to their profile.
- **Follow System**: Users can follow and unfollow other users to see their posts in their feed.
- **Like and Comment**: Users can like and comment on posts.
- **Feed Exploration**: Users can explore a feed of posts from users they follow.

## Technologies Used

- **MongoDB**: NoSQL database used for storing user data, posts, and other information.
- **Express.js**: Web application framework for building APIs and handling HTTP requests.
- **React.js**: Frontend library for building user interfaces.
- **Node.js**: JavaScript runtime environment used for server-side logic.
- **Mongoose**: MongoDB object modeling tool for Node.js.
- **JWT (JSON Web Tokens)**: Used for user authentication and authorization.
- **Multer**: Middleware for handling file uploads.
- **Cloudinary**: Cloud-based image and video management service used for image uploads.
- **React Router**: Client-side routing library for navigating between pages.
- **Redux**: State management library for managing application state.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/mukeshphulwani66/Instagram-clone-MERN-Stack.git
   ```

2. Navigate to the root directory:

   ```bash
   cd Instagram-clone-MERN-Stack
   ```

3. Install dependencies for both the server and client:

   ```bash
   npm install
   cd ../client && npm install
   ```

4. Set up environment variables:

   - Create a `dev.js` file in the `/config` directory.
   - Add the following environment variables:

     ```
     module.exports={
     MONGOURI="your_mongodb_uri",
     JWT_SECRET="your_jwt_secret",
     SENDGRID_API="your_sendgrid_api_key",
     EMAIL="http://localhost:3000"
     }
     ```

5. Start the server:

   ```bash
   npm start
   ```

6. Start the client:

   ```bash
   cd ../client && npm start
   ```

7. Open your browser and navigate to `http://localhost:3000` to view the application.

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues if you find any bugs or have suggestions for improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README to include any additional information specific to your project!
