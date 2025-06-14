# Campus Connect Insight - Skill Recommender

A modern skill recommendation system with DevOps integration for educational institutions.

## Features

- User authentication and authorization
- Skill assessment and recommendations
- Real-time progress tracking
- Interactive dashboard
- Responsive design

## Tech Stack

### Frontend
- React.js
- Material-UI
- Redux for state management
- Axios for API calls

### Backend
- Node.js
- Express.js
- MongoDB
- JWT for authentication

### DevOps
- Docker for containerization
- GitHub Actions for CI/CD
- Vercel for deployment
- Prometheus for monitoring
- SonarQube for code quality
- Jest for testing

## Getting Started

### Prerequisites
- Node.js (v16 or higher)
- Docker
- MongoDB
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/campus-connect-insight.git
cd campus-connect-insight
```

2. Install dependencies:
```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Set up environment variables:
```bash
# Backend (.env)
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=5000

# Frontend (.env)
REACT_APP_API_URL=http://localhost:5000
```

4. Run the application:
```bash
# Development mode
npm run dev

# Production mode
npm run build
npm start
```

## Docker Deployment

```bash
# Build and run with Docker Compose
docker-compose up --build
```

## CI/CD Pipeline

The project uses GitHub Actions for continuous integration and deployment. The pipeline includes:
- Code quality checks with SonarQube
- Automated testing
- Docker image building
- Deployment to Vercel

## Monitoring

Prometheus metrics are available at `/metrics` endpoint. Grafana dashboards are provided for visualization.

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. # campus-connect-insight
