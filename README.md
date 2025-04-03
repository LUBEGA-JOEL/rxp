# eCommerce Website

This project is a full-stack eCommerce website that includes both a backend and a frontend application. The backend is built with TypeScript and Express, while the frontend is developed using React.

## Project Structure

```
ecommerce-website
├── backend
│   ├── src
│   │   ├── app.ts
│   │   ├── controllers
│   │   │   └── index.ts
│   │   ├── models
│   │   │   └── index.ts
│   │   ├── routes
│   │   │   └── index.ts
│   │   └── services
│   │       └── index.ts
│   ├── package.json
│   ├── tsconfig.json
│   └── README.md
├── frontend
│   ├── src
│   │   ├── components
│   │   │   └── App.tsx
│   │   ├── pages
│   │   │   └── Home.tsx
│   │   ├── styles
│   │   │   └── index.css
│   │   └── index.tsx
│   ├── public
│   │   └── index.html
│   ├── package.json
│   ├── tsconfig.json
│   └── README.md
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm (Node Package Manager)

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd ecommerce-website
   ```

2. Install backend dependencies:
   ```
   cd backend
   npm install
   ```

3. Install frontend dependencies:
   ```
   cd frontend
   npm install
   ```

### Running the Application

#### Backend

1. Navigate to the backend directory:
   ```
   cd backend
   ```

2. Start the backend server:
   ```
   npm start
   ```

#### Frontend

1. Navigate to the frontend directory:
   ```
   cd frontend
   ```

2. Start the frontend application:
   ```
   npm start
   ```

### API Endpoints

The backend provides the following API endpoints:

- `GET /api/products` - Fetch all products
- `POST /api/products` - Create a new product

### Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features.

### License

This project is licensed under the MIT License. See the LICENSE file for details.