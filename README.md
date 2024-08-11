# Property Management System

A comprehensive property management system for commercial and residential leases.

## Overview

The Property Management System is a full-stack web application designed to streamline the management of lease agreements for both commercial and residential properties. It provides an efficient solution for handling multiple lease agreements, tracking payments, and managing property details.

## Features

- Multi-tenant lease management
- Commercial and residential property support
- Customizable lease terms and conditions
- Payment tracking and reminders
- Reporting and analytics
- User role management (Admin, Property Manager, Tenant)

## Technology Stack

- Frontend: React with TypeScript
- Backend: Node.js with Express.js
- Database: SQLite (with planned migration path to more scalable DBMS)
- ORM: Sequelize/TypeORM for database abstraction

## Documentation

Detailed documentation can be found in the `docs/` directory:

- `docs/requirements/`: Functional and non-functional requirements
- `docs/design/`: System architecture, database schema, and UI mockups
- `docs/api/`: API documentation
- `docs/user_guides/`: Admin and tenant user guides
- `docs/development/`: Setup guide, coding standards, and testing strategy
- `docs/deployment/`: Deployment guide and maintenance procedures

## Getting Started

1. Clone the repository
   ```
   git clone https://github.com/yourusername/property-management-system.git
   cd property-management-system
   ```

2. Install dependencies
   ```
   npm install
   ```

3. Set up the database
   ```
   npm run db:setup
   ```

4. Start the development server
   ```
   npm run dev
   ```

For more detailed setup instructions, please refer to `docs/development/setup_guide.md`.

## Contributing

We welcome contributions to the Property Management System! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) file for details on our code of conduct, development process, and how to submit pull requests.

## License

This project is licensed under the [GNU Affero General Public License v3.0 (AGPL-3.0)](LICENSE).

## Contact

For any inquiries, please open an issue in this repository.