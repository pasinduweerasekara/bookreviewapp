# BookRevieApp 📚✨  

**BookRevieApp** is a web application for book enthusiasts to discover, review, and share their favorite books. 
---

## Features  
- **User Registration & Authentication**: Secure login and signup functionality.  
- **Write & Read Reviews**: Share your thoughts on books and read reviews from other users.  
- **Ratings**: Rate books and view average ratings.  
---

## Installation  

1. Clone the repository:  
   ```bash
   git clone https://github.com/pasinduweerasekara/BookRevieApp.git
   cd BookRevieApp
2. Install dependencies:
  ```bash
cd ./backend
npm install
  ```

3. Set up environment variables:
Create a .env file in the root directory and add the following:

  ```env
MONGO_URI=mongodb+srv://wmpmweerasekara:RU6iQE9HWZEZLqTs@cluster0.247h7.mongodb.net/BookReviewApp
PORT=5000NODE_ENV=development
JWT_SECRET=SECRET
  ```

4. Run the application:
   ```bash
   nodemon server.js
   ```
5. Open un another Terminal in the base rirectory and run following commands

   ```bash
   cd ./frontend
   npm install
    ```
6. Set up environment variables:
Create a .env file in the root directory and add the following:

```env
VITE_BASE_URL=http://localhost:5000
```

7. Start the Application

   ```bash
   
       npm run dev
   ```
8. use following credentials to login to the application
   email : test@test.com
   password : qwerty

10. When Creating a user, Password mustbe atleast 6 characters long, Currently the application not providing any validations errors in UI

## Tech Stack
Frontend: React.js with Vite
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JWT-based Authentication





