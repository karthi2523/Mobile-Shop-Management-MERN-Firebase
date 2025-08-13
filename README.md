<img width="1909" height="909" alt="Screenshot 2025-08-13 104651" src="https://github.com/user-attachments/assets/6d83ec8a-6f4c-46c3-8ee5-b07b384405a2" />
<img width="589" height="918" alt="Screenshot 2025-08-13 104851" src="https://github.com/user-attachments/assets/28fd949f-3617-45be-a70a-a4fd300a271c" />
# Mobile Shop Management System

## Overview
The Mobile Shop Management System is a web-based platform designed specifically for mobile shops to efficiently manage stock, sales, and service records. The system provides separate dashboards for **Manager**, **Employees**, and **Service Technicians** to streamline daily operations.

## Features
- **Role-based Dashboards**:
  - **Manager**: View stock-in, stock-out, service details, and retail reports.
  - **Employees**: Add mobiles to stock-in, process stock-out by generating bills, and register mobile service requests.
  - **Service Technicians**: Update and track repair/service status.

- **Inventory Management**: Track stock-in and stock-out in real-time.
- **Billing System**: Generate invoices for customers.
- **Service Tracking**: Log and monitor repair/service details.
- **Database**: Firebase for authentication, data storage, and hosting.

## Live Demo
- **Manager / Employee / Service Login**: [https://mobile-shop-management-c72c6.web.app/login](https://mobile-shop-management-c72c6.web.app/login)  
- **Customer Service Status Check**: [https://mobile-shop-management-c72c6.web.app/check-service-status?serviceId=](https://mobile-shop-management-c72c6.web.app/check-service-status?serviceId=)

## Tech Stack
- **Frontend**: HTML, CSS, JavaScript, Bootstrap, Material UI
- **Backend**: Firebase (Firestore Database, Authentication)
- **Hosting**: Firebase Hosting

## How It Works
1. **Manager Dashboard**: Access full reports on inventory, sales, and services.
2. **Employee Dashboard**: Add new stock, make sales, register services.
3. **Service Technician Dashboard**: View assigned service tasks, update status.
4. **Customer Service Portal**: Customers can check repair/service status using their Service ID.

## Setup Instructions
1. Clone the repository.
2. Install dependencies:  
   ```
   npm install
   ```
3. Set up Firebase configuration in `.env` file.
4. Run the project locally:  
   ```
   npm start
   ```
5. Build for production:  
   ```
   npm run build
   ```

## License
This project is licensed under the MIT License.
