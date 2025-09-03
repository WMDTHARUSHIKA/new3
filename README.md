# Auto X Sri Lanka - Construction Platform

A comprehensive platform connecting construction professionals across Sri Lanka for vehicle rental and material supply services.

## Features

### For Service Consumers
- Browse and rent heavy construction vehicles (JCBs, excavators, lorries, etc.)
- Source quality construction materials (sand, soil, bricks, gravel, etc.)
- Direct contact with verified suppliers and vehicle owners
- Island-wide coverage across all 25 districts

### For Vehicle Owners
- List vehicles for rental with custom pricing
- Manage availability and bookings
- Connect with verified contractors
- Earn passive income from vehicle rentals

### For Material Suppliers
- List construction materials with competitive pricing
- Expand customer base across Sri Lanka
- Quality certification support
- Direct sales without middleman fees

## Technology Stack

### Frontend
- React 18 with TypeScript
- Tailwind CSS for styling
- Lucide React for icons
- Vite for development and building

### Backend (Server Directory)
- Node.js with Express
- MySQL database with Sequelize ORM
- JWT authentication
- File upload support with Multer
- Email notifications with Nodemailer

## Getting Started

### Frontend Development
```bash
npm install
npm run dev
```

### Backend Development
```bash
cd server
npm install
npm run dev
```

## Project Structure

```
src/
├── components/          # React components
├── data/               # Mock data and services
├── types/              # TypeScript type definitions
└── main.tsx           # Application entry point

server/
├── config/            # Database configuration
├── middleware/        # Express middleware
├── models/           # Database models
├── routes/           # API routes
├── scripts/          # Database scripts
└── utils/            # Utility functions
```

## Key Features

- **Multi-role Authentication**: Support for consumers, vehicle owners, material suppliers, and admins
- **Real-time Communication**: Direct contact between service providers and customers
- **Location-based Services**: Filter by district and location
- **Rating System**: Customer feedback and rating system
- **Document Management**: Upload and verify business documents
- **Responsive Design**: Mobile-friendly interface

## Demo Accounts

For testing purposes, you can use these email patterns:
- Consumer: any regular email (e.g., john@example.com)
- Vehicle Owner: emails containing "vehicle" or "owner"
- Material Supplier: emails containing "material" or "supplier"
- Admin: emails containing "admin"

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License.