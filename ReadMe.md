# **TechNotes for 888Nexta**  

A streamlined, secure note-taking application designed to replace traditional sticky notes, improve team collaboration, and enforce effective role-based access control.  

---

## **Backend Overview**  

The backend of this MERN stack project is built with modern web technologies for seamless and secure operation.  

### **Key Features**  
- **RESTful API Design**: Modular and reusable architecture for enhanced maintainability.  
- **Authentication & Authorization**: Secure login system using **JWT** with role-based access control.  
- **Password Security**: Passwords are hashed using **bcrypt** for data protection.  
- **Error Handling**: Managed through **express-async-errors** for cleaner and centralized error management.  
- **Security Enhancements**:  
  - **CORS middleware** for secure cross-origin requests.  
  - Environment variables managed with **dotenv**.  
- **Clean Code Principles**: Maintains modularity and readability, following best practices.  
- **Asynchronous Operations**: Efficient handling through **Express middleware**.  

---

## **Application Access**  

### **Live Links**  
- **Backend**: [Access Backend](https://technotesfor88nextabackend-production.up.railway.app)  
- **Frontend**: [Access Frontend](https://technotesfor88nextafrontend-production.up.railway.app)  

### **Test Login Credentials**  
- **Username**: `EthanD`  
- **Password**: `asdASD`  

> ⚠️ **Note**: Admin and Manager credentials are not shared for security reasons.  

---

### User Stories for techNotes
1. [x] Replace current sticky note system
2. [x] Add a public facing page with basic contact info 
3. [x] Add an employee login to the notes app
4. [x] Provide a welcome page after login
5. [x] Provide easy navigation
6. [x] Display current user and assigned role
7. [x] Provide a logout option
8. [x] Require users to login at least once per week
9. [x] Provide a way to remove employee access asap if needed
10. [x] Notes are assigned to specific users
11. [x] Notes have a ticket, title, note body, created & updated dates
12. [x] Notes are either OPEN or COMPLETED
13. [x] Users can be Employees, Managers, or Admins
14. [x] Notes can only be deleted by Managers or Admins
15. [x] Anyone can create a note (when customer checks-in)
16. [x] Employees can only view and edit their assigned notes 
17. [x] Managers and Admins can view, edit, and delete all notes 
18. [x] Only Managers and Admins can access User Settings
19. [x] Only Managers and Admins can create new users
20. [x] Desktop mode is most important but should be available in mobile

---

## **Screenshots**  

| **Login Page** | **Dashboard** | **Note Creation** |  
|----------------|--------------|-------------------|  
| ![Login](https://github.com/user-attachments/assets/bc82ad89-dd79-41de-a1fc-e7acc749e299) | ![Dashboard](https://github.com/user-attachments/assets/4d39a10d-37e7-4d27-82d7-dd5b9e79c009) | ![Note Creation](https://github.com/user-attachments/assets/841116ef-0c21-4027-ae4b-367eff26bcfd) |  

| **Notes List** | **Role Management** | **User Settings** |  
|----------------|---------------------|-------------------|  
| ![Notes List](https://github.com/user-attachments/assets/9fe61ac9-fca9-487b-a1c8-2f92ff0f3e92) | ![Role Management](https://github.com/user-attachments/assets/07decd88-2baf-4755-80a9-868453e5e759) | ![User Settings](https://github.com/user-attachments/assets/cfcbc042-b4e8-44dd-ad07-ec376e82ece5) |  

---

## **Technologies Used**  

### **Backend**  
- **Node.js** & **Express.js**: Server setup and REST API development.  
- **MongoDB** & **Mongoose**: NoSQL database and ORM for flexible data modeling.  
- **JWT Authentication**: For secure user authentication and role management.  
- **bcrypt**: Ensures robust password hashing.  
- **CORS Middleware**: Enables secure communication between frontend and backend.  
- **dotenv**: Manages sensitive environment variables.  

### **Frontend**  
- **React**: Component-based UI development.  
- **Redux**: State management for application-wide data consistency.  
- **CSS Modules**: Scoped and maintainable styling.  

---

## **How to Get Started**  

1. **Clone the Repositories**:  
   - Backend: [Backend Repository](https://github.com/sandarudivyantha/tech_notes_for_88nexta_backend)  
   - Frontend: [Frontend Repository](https://github.com/sandarudivyantha/tech_notes_for_88nexta_frontend)  

2. **Install Dependencies**:  
   Run `npm install` in both backend and frontend directories.  

3. **Setup Environment Variables**:  
   Configure `.env` files in both repositories based on example files.  

4. **Run the Application**:  
   - For the backend: `npm run dev`  
   - For the frontend: `npm start`  

5. **Explore Features**:  
   Use the provided login credentials to test the app's functionality.  

---
