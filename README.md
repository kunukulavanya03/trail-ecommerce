# trail-ecommerce

Backend API for trail-ecommerce

## Tech Stack

- **Frontend**: React
- **Backend**: FastAPI + SQLAlchemy
- **Frontend Source**: GitHub ([Repository](https://github.com/Malleswar-249/E-COMMERCE-WEBSITE))

## Project Structure

```
trail-ecommerce/
├── frontend/          # Frontend application
├── backend/           # Backend API
├── README.md          # This file
└── docker-compose.yml # Docker configuration (if applicable)
```

## Getting Started

### Prerequisites

- Node.js 18+ (for frontend)
- Python 3.11+ (for Python backends)
- Docker (optional, for containerized setup)

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
# Follow backend-specific setup instructions in backend/README.md
```

## Features

- User registration and login
- Product management
- Cart and checkout functionality
- Order management
- Sales reports and analytics

## API Endpoints

- `POST /api/register` - Register a new user
- `POST /api/login` - Log in an existing user
- `GET /api/products` - Get a list of all available products
- `GET /api/products/{product_id}` - Get the details of a specific product
- `POST /api/cart` - Add a product to the user's cart
- `GET /api/cart` - Get the contents of the user's cart
- `POST /api/checkout` - Complete the user's purchase
- `GET /api/orders` - Get a list of all orders
- `GET /api/reports` - Get sales reports and analytics

## License

MIT
