# WebApp React Project 🚀

**WebApp React Project** is a modern web application that combines client-side functionality with API calls to a server. It serves as a comprehensive example of building an application that manages user authentication, content display, and administrative operations—all within a clean, modular, and responsive React interface.

> **Note:** The REST API integrated in this project was provided as part of the course materials.

---

## 📚 Introduction & Objectives

In this project you will gain hands-on experience with:
- **Developing a Full-Featured Web Application:** Building a responsive React app that integrates with a REST API.
- **Client-Server Communication:** Using Axios to perform HTTP requests and handle API responses.
- **User & Content Management:** Allowing business users to register, log in, update profiles, and manage content (create, update, delete).
- **Advanced UI/UX Features:** Implementing a dynamic navigation menu, search functionality, light/dark mode toggling, and more.

> **Objective:** Master the art of developing a robust, user-friendly web application using React. This project is a key part of your portfolio, showcasing modern web development best practices and design aesthetics.

---

## 🔧 Technologies & Tools

- **React** – A JavaScript library for building user interfaces.
- **React Router** – For managing in-app navigation.
- **Axios** – For handling HTTP requests to the REST API.
- **Bootstrap / Material-UI** – For responsive design and pre-built UI components.
- **SCSS** – For modular and maintainable styling (if using SCSS, styles are split into multiple files).
- **Font Awesome / Material Icons** – For icons used in the application.
- **JWT (JSON Web Tokens)** – For managing user authentication on the client side (token stored in localStorage).

---

## 📁 Project Structure

The project is organized into clear, modular directories to ensure maintainability and scalability:

- **public/**  
  - Contains the static assets, including `index.html`, the favicon, and other public files.

- **src/**  
  - **components/** – Reusable UI components (e.g., Navigation, Footer, Card, Form elements).
  - **pages/** – Main application pages (e.g., Home, Login, Register, Dashboard, About, Favorites).
  - **services/** – API service files using Axios to handle HTTP requests.
  - **styles/** – SCSS/CSS files, organized by components or themes.
  - `App.js` – Main app component handling routing.
  - `index.js` – Application entry point.

- **Postman Collection:**  
  A Postman export file (e.g., `WebAppReact.postman_collection.json`) is included for testing API endpoints.

---

## 🚀 Installation & Running the Project

### Prerequisites
- **Node.js & npm:** Ensure you have the latest stable versions installed.
- **A REST API backend:** The client app communicates with an API server for user and content management. *(Note: The API was provided as part of the course.)*

### Setup Steps

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/YourUsername/WebAppReactProject.git
   cd WebAppReactProject
Install Dependencies:

bash
Copy
npm install
Configure Environment Variables (if required):
If your app requires environment variables (e.g., API base URL), create a .env file in the root directory:

ini
Copy
REACT_APP_API_BASE_URL=https://api.example.com
Run the Application:

bash
Copy
npm start
This will start the development server and open the application in your default browser at http://localhost:3000.

🎨 Main Features
User Authentication:

Registration & Login: Secure forms for user registration and login.
Token Management: After a successful login, a JWT is stored in localStorage for subsequent authenticated requests.
Dynamic Navigation & UI:

Responsive Navigation Menu: Links adjust dynamically based on user roles.
Search Functionality: A search field that filters content on the home page.
Light/Dark Mode Toggle: Switch between light and dark themes for enhanced usability.
Content Management:

Dashboard: Business users can add, edit, or delete content.
Card Display: The home page displays at least three content cards with icons, which link to detailed pages.
Favorites: Users can mark content as favorite and view a dedicated Favorites page.
Additional Pages:

About Page: Provides an in-depth explanation of the application and its usage.
Responsive Design: Ensures a seamless experience across different devices and screen sizes.
Accessibility: The app includes proper meta tags, alt attributes for images, and a favicon.
HTTP Requests:

Using Axios for API calls with proper error handling using async/await with try/catch or then/catch patterns.
📝 Testing & Manual Checks
User Actions:
Test registration and login via the provided forms.
Verify that authenticated routes are accessible only after a successful login.
Content Operations:
Create, update, and delete content as a business user.
Use the search field to filter displayed content.
Toggle between light and dark modes and observe the UI change.
API Testing:
Use the provided Postman collection (WebAppReact.postman_collection.json) to test all API endpoints.
📫 Contact
For any questions or feedback, please contact me at:
Email: galdvash59@gmail.com

WebApp React Project is developed by Gal Dvash. Thank you for your interest and happy coding!
