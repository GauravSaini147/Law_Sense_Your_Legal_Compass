# -Law-Sense-Your-Legal-Compass

## Overview
The **Legal Awareness Web App** is designed to empower citizens with accessible legal knowledge and resources. It provides a secure platform for users to register, log in, and explore legal rights, governance policies, and awareness materials. Built with a robust backend and a clean, modular frontend, the app ensures both resilience and usability.

## Features
-  **Secure Authentication**  
  - User registration & login  
  - Password hashing with bcrypt  
  - JWT-based session management  

-  **Database Integration**  
  - MongoDB for user management and content storage  
  - Reliable connection handling  

-  **Frontend**  
  - React-based forms for registration & login  
  - Conditional rendering based on authentication state  
  - Styled navigation bar with Material-UI/TailwindCSS  

-  **Backend**  
  - Modular project structure for scalability  
  - RESTful APIs for authentication and data access  

## Tech Stack
| Layer        | Technology |
|--------------|------------|
| Frontend     | React, React Router, Material-UI/TailwindCSS |
| Backend      | Node.js, Express.js |
| Database     | MongoDB |
| Authentication | bcrypt, JWT |

## Installation
1. **Clone the repository**
   ```bash
   

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Setup environment variables**  
   Create a `.env` file in the root directory:
   ```
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_secret_key
   ```

4. **Run the backend**
   ```bash
   npm run server
   ```

5. **Run the frontend**
   ```bash
   npm start
   ```

## Usage
- Register a new account or log in with existing credentials.  
- Access legal awareness resources and governance information.  
- Navigate securely with authentication-based routing.  

## Project Goals
- Promote **Smart Governance** through accessible legal awareness.  
- Provide a **secure, resilient platform** for user empowerment.  
- Ensure **scalability and maintainability** with modular design.  

## Future Enhancements
- Interactive legal guides  
- Multi-language support  
- Mobile-friendly UI
