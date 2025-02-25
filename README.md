# IE_ParhamFood

## Overview

IE_ParhamFood is a project developed as part of an Industrial Engineering (IE) course. It aims to provide a comprehensive solution for managing food delivery services, encompassing both administrative and customer-facing functionalities.

## Features

- **Backend**: Developed using Go, the backend handles all server-side operations, including order processing, user authentication, and data management.
- **Frontend for Admin**: A web interface built with JavaScript, HTML, and CSS, enabling administrators to manage menus, track orders, and oversee customer interactions.
- **Frontend for Customers**: A user-friendly web application that allows customers to browse menus, place orders, and track delivery statuses.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/kimiasedighi/IE_ParhamFood.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd IE_ParhamFood
   ```

3. **Backend Setup**:
   - Ensure you have Go installed on your machine.
   - Navigate to the backend directory:
     ```bash
     cd backend
     ```
   - Install necessary dependencies:
     ```bash
     go mod tidy
     ```
   - Start the backend server:
     ```bash
     go run main.go
     ```

4. **Frontend Setup**:
   - **Admin Interface**:
     - Navigate to the admin frontend directory:
       ```bash
       cd ../frontend-admin
       ```
     - Install dependencies:
       ```bash
       yarn install
       ```
     - Start the admin frontend application:
       ```bash
       yarn start
       ```
   
   - **Customer Interface**:
     - Navigate to the customer frontend directory:
       ```bash
       cd ../frontend-customer
       ```
     - Install dependencies:
       ```bash
       yarn install
       ```
     - Start the customer frontend application:
       ```bash
       yarn start
       ```

## Usage

- **Admin Panel**: Access the admin interface at `http://localhost:3000` to manage restaurant operations.
- **Customer Application**: Customers can access the application at `http://localhost:3001` to browse menus and place orders.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request detailing your changes.

## License

This project is licensed under the MIT License.

---

For more information, visit the [IE_ParhamFood GitHub repository](https://github.com/kimiasedighi/IE_ParhamFood).
