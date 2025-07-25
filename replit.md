# Women's Health Platform

## Overview
This is a comprehensive women's health platform featuring period tracking, health metrics monitoring, doctor consultations, educational resources, and community features. The application is built with React + TypeScript frontend and Express backend, using PostgreSQL for data persistence.

## Project Architecture
- **Frontend**: React 18 + TypeScript with Wouter for routing
- **Backend**: Express.js with TypeScript
- **Database**: PostgreSQL with Drizzle ORM
- **UI Framework**: Tailwind CSS + Radix UI (shadcn/ui)
- **State Management**: TanStack Query for server state
- **Authentication**: Custom authentication system
- **Build Tool**: Vite

## Recent Changes
- **July 25, 2025**: Migrated project from Replit Agent to Replit environment
- **July 25, 2025**: Implemented "Ask Sakhii" AI assistant with Gemini API integration
- **July 25, 2025**: Enhanced multilingual support (Hindi, Tamil, Telugu, Bengali, etc.)
- **July 25, 2025**: Added comprehensive SEO optimization with structured data
- **July 25, 2025**: Created e-commerce shop for health & hygiene products
- **July 25, 2025**: Organized file structure with dedicated AI and health components
- **July 25, 2025**: Set up favicon and Open Graph meta tags for social sharing
- Project structure validated and confirmed working
- All dependencies properly installed and configured

## Features
- **Health Tracking**: Period tracking, health metrics (BMI, sleep, water intake, exercise)
- **Doctor Directory**: Browse and book consultations with healthcare providers  
- **Educational Resources**: Health education content by category
- **Community**: User interaction and support features
- **Voice Assistant**: AI-powered voice interactions
- **Chatbot**: Intelligent chat support
- **Games**: Interactive health education games
- **Multi-language Support**: i18next integration

## User Preferences
- Project uses modern React patterns with TypeScript
- Follows fullstack JS development guidelines
- Uses in-memory storage initially, can be upgraded to PostgreSQL
- Implements proper client/server separation for security

## Development Setup
- Uses Node.js 20 with Express server on port 5000
- Vite dev server integrated with Express for unified development
- Hot reload enabled for both frontend and backend changes
- Database schema defined in `shared/schema.ts` with Drizzle ORM

## Security Features
- Password-based authentication
- Input validation with Zod schemas
- Proper error handling and status codes
- Environment variable configuration support

## Migration Status
✅ Project successfully migrated from Replit Agent to Replit environment
✅ All dependencies installed and working
✅ Server running on port 5000 with proper configuration
✅ Frontend and backend integrated correctly