# BookEase - Hotel Management System

BookEase is a comprehensive Hotel Management System designed to streamline hotel operations and enhance guest experience. Built with a modern technology stack, BookEase provides robust features for managing rooms, guests, bookings, billing, staff, and more.

## Table of Contents

- Features
- Technologies Used
- Project Structure
- Installation
- Usage
- Contributing
- License
- Contact

## Features

- **Manage Rooms:** Add, edit, and remove room details, including room types, availability, and pricing.
- **Manage Guests:** Handle guest information, check-in, and check-out processes efficiently.
- **Manage Staff:** Manage staff details, roles, and assignments.
- **Manage Room Service Types:** Define and manage different types of room services offered.
- **Manage Room Services Ordered:** Track room services ordered by guests and their statuses.
- **Staff Assignment:** Assign staff to specific tasks or rooms.
- **Manage Booking:** Handle room bookings, cancellations, and modifications seamlessly.
- **Manage Billing:** Generate and manage bills for guest stays and services.
- **Manage Invoices:** Create and manage invoices for guests and services provided.
- **Manage Payments:** Record and track payments made by guests.

## Technologies Used

### Frontend
- **React:** JavaScript library for building user interfaces
- **TypeScript:** Typed superset of JavaScript
- **Tailwind CSS:** Utility-first CSS framework

### Backend
- **Spring Boot:** Java-based framework for building web applications
- **MySQL:** Relational database management system

## Project Structure

```
BookEase/
├── HMS Frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.tsx
│   │   ├── index.tsx
│   ├── .env
│   ├── .gitignore
│   ├── package.json
│   ├── tailwind.config.js
│   ├── README.md
├── backend/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   ├── resources/
│   │   ├── test/
│   ├── .gitignore
│   ├── pom.xml
│   ├── README.md
└── LICENSE
```

## Installation

### Prerequisites
- **Node.js** (for frontend)
- **Java Spring Boot** (for backend)
- **MySQL** (for database)

### Frontend Setup

1. Navigate to the HMS Frontend directory:
   ```sh
   cd BookEase/HMS Frontend
   ```
2. Create and configure the `.env` file in the HMS Frontend directory.
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the development server:
   ```sh
   npm run dev
   ```

### Backend Setup

1. Navigate to the HMS Backend directory:
   ```sh
   cd BookEase/backend
   ```
2. Configure the `application.properties` file in `src/main/resources/` with your MySQL database details.
3. Build the project with Maven:
   ```sh
   mvn clean install
   ```
4. Run the Spring Boot application:
   ```sh
   mvn spring-boot:run
   ```

## Usage

1. Ensure the backend server is running.
2. Open a browser and navigate to `http://localhost:5173` to access the frontend application.
3. Use a REST client or integrate with the frontend to interact with backend services.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```sh
   git commit -am 'Add your feature'
   ```
4. Push to the branch:
   ```sh
   git push origin feature/your-feature
   ```
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, please contact:

- **Name:** Abdul Moiz 
- **Email:** [abdulmoiz8895@gmail.com](mailto:abdulmoiz8895@gmail.com)  
- **GitHub:** [AbdulMoiz2493](https://github.com/AbdulMoiz2493)

