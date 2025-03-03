# Real Estate Review System

## Overview
This project is a web and mobile application for writing and reading real estate reviews. Users can share their experiences, rate properties, and interact with other users.

## Tech Stack
- **Frontend (Web)**: React
- **Frontend (Mobile)**: React Native
- **Backend**: Express.js / Next.js
- **Database**: MySQL (managed with Prisma ORM)
- **Deployment**: Self-hosted on Oracle Cloud (ARM)
- **CI/CD**: GitHub Actions (planned)

## Features
- User authentication & authorization
- Posting and viewing property reviews
- Search and filter reviews
- Responsive web UI & mobile app
- API for managing reviews and user data

## Setup & Installation
### Prerequisites
- Node.js & npm
- MySQL database

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/real-estate-review.git
   cd real-estate-review
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Configure environment variables (`.env` file):
   ```env
   DATABASE_URL=mysql://user:password@host:port/database
   ```
4. Run Prisma migrations:
   ```sh
   npx prisma migrate dev
   ```
5. Start the development server:
   ```sh
   npm run dev
   ```

## API Endpoints (Planned)
| Method | Endpoint          | Description |
|--------|------------------|-------------|
| GET    | /reviews         | Get all reviews |
| POST   | /reviews         | Create a new review |
| GET    | /reviews/:id     | Get a review by ID |
| PUT    | /reviews/:id     | Update a review |
| DELETE | /reviews/:id     | Delete a review |

## Roadmap / TODO
- [ ] Set up CI/CD pipeline with GitHub Actions
- [ ] Develop initial React web UI
- [ ] Implement React Native mobile app
- [ ] Enhance API with authentication
- [ ] Deploy to Oracle Cloud

## License
MIT License

