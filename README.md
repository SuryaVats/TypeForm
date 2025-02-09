# Dynamic Form Builder Platform

A modern, interactive form building platform inspired by Typeform that enables users to create engaging, conversational forms with a smooth user experience.

## Project Overview

Our platform allows users to create and manage dynamic forms with a conversational interface. Forms are presented one question at a time with smooth transitions, creating an engaging experience for end-users. The application focuses on simplicity and performance while maintaining a robust feature set.

## Core Features

### Form Builder Interface

The form builder provides an intuitive interface for creating and managing forms. Users can:

Create various question types including:

- Short text responses
- Long text responses
- Multiple choice questions
- Single choice questions
- Rating scales
- Date selection
- File uploads
- Payment integration

The builder supports custom styling options and conditional logic for question branching, allowing forms to adapt based on previous answers.

### Form Response Management

Users can efficiently manage and analyze form responses through:

- Real-time submission tracking
- Response analytics dashboard
- Data export functionality (CSV, Excel, JSON)

### User Management

The platform includes comprehensive user management features:

- Collaborative team workspaces
- Role-based access control
- Activity logging
- User authentication and authorization

## Technical Stack

### Frontend

- **Framework**: Next.js 14 with App Router
  - Server components for improved performance
  - Built-in API routes
  - Enhanced SEO capabilities
  - Optimized image handling
- **Styling**: Tailwind CSS
  - Utility-first CSS framework
  - Built-in responsive design
  - Custom theme configuration
- **Authentication**: NextAuth.js
  - Multiple authentication providers
  - Session management
  - Protected routes

### Backend

- **Runtime**: Node.js with Express
  - Middleware-based architecture
  - Route handling
  - Error management
  - API documentation with Swagger
- **Database**: MySQL
  -Faster for read-intensive processes.

## Development Requirements

- Node.js >= 18.x
- MongoDB >= 6.0
- Docker & Docker Compose
- npm or yarn package manager

## Getting Started

1. Clone the repository

```bash
git clone https://github.com/SuryaVats/TypeForm.git
cd TypeForm
```

2. Install dependencies

```bash
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
```

3. Set up environment variables

```bash
cp .env.example .env
# Update .env with your actual values
```

4. Start development servers

```bash
# Start backend server
cd backend
npm run dev

# Start frontend server
cd frontend
npm run dev
```
