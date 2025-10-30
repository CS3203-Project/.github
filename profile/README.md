# Zia - Online Marketplace for Services

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/CS3203-Project/Deployed/releases)
[![Node.js](https://img.shields.io/badge/Node.js-18+-green.svg)](https://nodejs.org/)
[![React](https://img.shields.io/badge/React-19+-blue.svg)](https://reactjs.org/)
[![NestJS](https://img.shields.io/badge/NestJS-11+-red.svg)](https://nestjs.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13+-blue.svg)](https://www.postgresql.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5+-blue.svg)](https://www.typescriptlang.org/)
[![Prisma](https://img.shields.io/badge/Prisma-6+-green.svg)](https://www.prisma.io/)
[![Stripe](https://img.shields.io/badge/Stripe-19+-purple.svg)](https://stripe.com/)
[![Socket.io](https://img.shields.io/badge/Socket.io-4+-black.svg)](https://socket.io/)
[![AWS](https://img.shields.io/badge/AWS-S3%20%26%20SES-orange.svg)](https://aws.amazon.com/)
[![Google Maps](https://img.shields.io/badge/Google%20Maps-API-red.svg)](https://developers.google.com/maps)
[![License](https://img.shields.io/badge/License-ISC-yellow.svg)](https://opensource.org/licenses/ISC)
[![GitHub stars](https://img.shields.io/github/stars/CS3203-Project/Deployed_backend.svg)](https://github.com/CS3203-Project/Deployed_backend/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/CS3203-Project/Deployed_backend.svg)](https://github.com/CS3203-Project/Deployed_backend/network)
[![GitHub issues](https://img.shields.io/github/issues/CS3203-Project/Deployed_backend.svg)](https://github.com/CS3203-Project/Deployed_backend/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/CS3203-Project/Deployed_backend.svg)](https://github.com/CS3203-Project/Deployed_backend/pulls)
[![GitHub last commit](https://img.shields.io/github/last-commit/CS3203-Project/Deployed_backend.svg)](https://github.com/CS3203-Project/Deployed_backend/commits/main)

## Overview of the Project

An online platform designed to bridge the gap between service providers and customers in Sri Lanka. We are developing a SaaS application aiming to provide a selling platform for any kind of service (Printing services, Household works, sewing, tutoring, etc).

**Input to the system:** service provider details, service listings, booking requests, payments, and user communications.

**Output to the system:** booking confirmations, notifications, and a searchable catalog of services tailored to customer needs and geo location.

## Objectives of the Project

- Design and implement a robust web platform allowing service providers to market and manage their services and allowing customers to select reliable service providers according to their geo-location.
- Provide a seamless booking, secure payment process, rating system for both customers and service providers, notification and communication system.
- Develop a fully functional dashboard to manage several kinds of service categories dynamically.

## The Need for the Project

Currently in Sri Lanka, there's no dedicated online marketplace for services. Talented and skillful service providers still have no idea about the possibilities of online marketing. So as a SaaS platform, Zia is aimed at filling those gaps.

## Scope of the Project

The system will support three main user roles:

- **Service Providers:** Create profiles, list and manage services, set prices and availability, communicate with customers, respond to reviews, rate customers.
- **Customers:** Search and browse service listings, book and pay for services, communicate with providers, and rate their experiences and service providers.
- **Administrators:** Manage users, service categories, monitor transactions, and maintain system integrity through a dedicated dashboard.

## Deliverables

The primary deliverable is a responsive web application. This platform will feature:

- User-friendly GUI for all user roles (Simple GUI since we are aiming for normal people).
- Integration with Google Maps API for location-based service searches.
- Secure payment gateway for handling transactions.
- A comprehensive admin dashboard for system oversight.

## Project Structure

This repository contains three main components:

- **Deployed_backend**: The backend service built with Node.js, Express, Prisma, and PostgreSQL.
- **Deployed_Frontend**: The frontend application built with React, Vite, and TypeScript.
- **Deployed_Com**: The communication service built with NestJS for handling messaging and notifications.

## Prerequisites

- Node.js (>=18.0.0)
- PostgreSQL
- pnpm (for backend and frontend)
- npm (for communication)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/CS3203-Project/Deployed.git
   cd Deployed
   ```

2. Set up the backend:
   ```bash
   cd Deployed_backend
   pnpm install
   # Configure environment variables in .env file
   pnpm run build
   ```

3. Set up the frontend:
   ```bash
   cd ../Deployed_Frontend
   pnpm install
   ```

4. Set up the communication service:
   ```bash
   cd ../Deployed_Com
   npm install
   ```

## Running the Application

### Run Backend (Development)
```bash
cd Deployed_backend
pnpm run dev
```

### Run Frontend (Development)
```bash
cd Deployed_Frontend
pnpm run dev
```

### Run Communication (Development)
```bash
cd Deployed_Com
npm run start
```

## Building the Application

### Build Backend
```bash
cd Deployed_backend
pnpm run build
```

### Build Frontend
```bash
cd Deployed_Frontend
pnpm run build
```

### Build Communication
```bash
cd Deployed_Com
npm run build
```

## Testing

### Test Backend
```bash
cd Deployed_backend
pnpm run test
```

### Test Frontend
```bash
cd Deployed_Frontend
pnpm run test
```

### Test Communication
```bash
cd Deployed_Com
npm run test
```

## Technologies Used

- **Backend:** Node.js, Express, TypeScript, Prisma, PostgreSQL, Socket.io, Stripe, AWS S3/SES
- **Frontend:** React, TypeScript, Vite, Tailwind CSS, Google Maps API, Stripe
- **Communication:** NestJS, Socket.io, RabbitMQ, TypeORM
- **Deployment:** (Add deployment details if applicable)

## Contributing

Please read the contributing guidelines before making contributions.

## License

This project is licensed under the ISC License.

## Contact

For any questions or support, please contact the development team:

### Developers
- **Umesha Jayakody**  
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue.svg)](https://lk.linkedin.com/in/umesha-jayakody)  
  LinkedIn Profile: [umesha-jayakody](https://lk.linkedin.com/in/umesha-jayakody)

- **Yasith Imalka**  
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue.svg)](https://lk.linkedin.com/in/yasith-imalka-31b6a32a1)  
  LinkedIn Profile: [yasith-imalka-31b6a32a1](https://lk.linkedin.com/in/yasith-imalka-31b6a32a1)

- **Kavisha Indunil**  

