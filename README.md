# **RBAC (Role-Based Access Control) System**

A React-based Role-Based Access Control (RBAC) application designed to streamline the management of users, roles, and permissions. This system features an interactive dashboard to display user information and provides tools to efficiently add, update, and delete users, roles, and permissions.

---

## **Key Features**

### **Dashboard**
- View detailed user information, including their assigned roles and permissions.

### **User Management**
- Easily add, update, and remove user profiles and associated details.

### **Role Management**
- Create, update, and delete roles to define access control.

### **Permission Management**
- Manage permissions by assigning them to roles or modifying existing permissions.

---

## **Technology Stack**

- **Frontend**: React.js, HTML, CSS, JavaScript
- **Styling**: Custom CSS
- **Assets**: Icons and resources stored in the `public/asset` folder


---

## **How to Use**

### **Dashboard**
- Review the list of users along with their associated roles and permissions on the dashboard.

### **User Management**
1. Open the **User Management** section.
2. Add new users using the provided form.
3. Edit or delete existing user details.

### **Role Management**
1. Navigate to the **Role Management** section.
2. Add or update roles as needed for the application.

### **Permission Management**
1. Access the **Permission Management** area.
2. Assign permissions to roles or modify current permissions to ensure proper access.

---

## **Folder Structure**

```
RBAC/
│
├── public/
│   └── asset/               # Contains icons and other assets
│       ├── icon.png         # Icon for the project
│       └── index.html       # Entry point for React
│
├── src/
│   ├── components/          # Reusable React components
│   │   └── pages/           # Main pages of the application
│   │       ├── Dashboard.js           # Dashboard to display user info
│   │       ├── PermissionManagement.js # Manage permissions
│   │       ├── RoleManagement.js       # Manage roles
│   │       ├── UserManagement.js       # Manage users
│   │       ├── UserCard.js             # Display user details
│   │       └── UserForm.js             # Form for adding/editing users
│   │
│   ├── styles/              # Styling for the application
│   │   └── index.css        # Global CSS styles
│   │
│   ├── App.js               # Main application file
│   ├── index.js             # React entry point
│
└── README.md                # Project README file
```
