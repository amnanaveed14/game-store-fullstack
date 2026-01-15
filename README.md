# game-store-fullstack
Full-stack game store web application with SQL database and JavaScript frontend
# GameStore 🎮

A full-stack Game Store simulation with features like user management, inventory, orders, and payments.  
Built with **Node.js**, **Express**, and **SQL Server**, this project demonstrates CRUD operations, database integration, and backend API development.

---

## Features

- **User Management**: Register, login, and manage user accounts  
- **Inventory Management**: Add, update, and delete games from the store  
- **Order Management**: Place and track orders with multiple items  
- **Payments**: Process and record payments  
- **Database Integration**: Fully connected with SQL Server using relational tables  
- **RESTful API**: Backend endpoints for all operations  

---

## Tech Stack

- **Backend:** Node.js, Express.js  
- **Database:** Microsoft SQL Server  
- **Languages:** JavaScript (Node.js), SQL  
- **Tools:** Postman (for API testing), Git & GitHub  

---

## Database Structure

The database (`GAMESTOREDB`) contains the following tables:

- `Users` – store user information  
- `Games` – game details and inventory  
- `Inventory` – track available stock  
- `Orders` – user orders  
- `Order_Items` – details of each order  
- `Payments` – payment records  

Additional features include **views** and **triggers** to maintain data integrity.

---

## Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/GameStore.git
   cd GameStore
