# MENAC (Mentorship Engagement Network and Communication)

## Overview

MENAC is a sophisticated mentorship platform that leverages AI and modern web technologies to create meaningful connections between mentors and mentees. Built with Next.js 13 and TypeScript, it provides a seamless experience for both mentors and mentees to find their perfect match and engage in productive mentorship relationships.

## Key Features

### 🤝 Smart Matching System
- AI-powered matching algorithm based on skills, interests, and career goals
- Compatibility scoring system to ensure quality matches
- Advanced filtering options for specific expertise areas
- Experience level matching to ensure appropriate mentor-mentee pairing

### 💬 Interactive Chat System
- Real-time messaging functionality
- Support for code snippets and markdown formatting
- File sharing capabilities
- Message history and search functionality
- Read receipts and typing indicators

### 📊 Dynamic Dashboard
- Personalized dashboard for both mentors and mentees
- Progress tracking and milestone management
- Upcoming sessions overview
- Recent activity feed
- Resource sharing section

### 👤 Profile Management
- Detailed profile customization
- Skills and expertise tagging
- Availability calendar integration
- Portfolio and project showcase
- Professional background section
- Testimonials and reviews

### 🎯 Mentorship Tools
- Goal setting and tracking
- Session scheduling system
- Meeting notes and action items
- Progress reporting
- Resource library access

## Technical Architecture

### Frontend
- **Framework**: Next.js 13 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS for responsive design
- **State Management**: React Context API
- **UI Components**: Custom components with shadcn/ui

### Backend Features
- **API Routes**: Next.js API routes with TypeScript
- **AI Integration**: Vercel AI SDK for intelligent matching
- **Real-time**: WebSocket integration for live chat
- **Authentication**: Secure user authentication system
- **Data Storage**: Scalable database architecture

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/hrideymarwah15/Menac_X_DCode.git
cd Menac_X_DCode
```

2. Install dependencies:
```bash
npm install
# or
pnpm install
```

3. Set up environment variables:
```bash
cp .env.example .env.local
# Edit .env.local with your configuration
```

4. Run the development server:
```bash
npm run dev
# or
pnpm dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Project Structure
```
├── app/                # Next.js 13 app directory
│   ├── ai/            # AI-related features
│   ├── api/           # API routes
│   ├── chat/          # Chat functionality
│   ├── dashboard/     # Dashboard views
│   ├── match/         # Matching system
│   └── onboarding/    # User onboarding
├── components/        # Reusable components
├── lib/              # Utility functions
├── public/           # Static assets
└── styles/           # Global styles
```

## Tech Stack

- **Framework**: Next.js 13
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **AI Integration**: Vercel AI SDK
- **UI Library**: shadcn/ui
- **Development Tools**: ESLint, Prettier
- **Version Control**: Git

## Live Demo

Visit MENAC at: [menac.vercel.app](https://menac.vercel.app)



Presentation Link:https://www.canva.com/design/DAG04mDFh40/6GR0uKqV37m6VI0aKML7vw/edit?utm_content=DAG04mDFh40&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton




Documentation: https://docs.google.com/document/d/1OzczKL9OkmQPSBKfZjG0tX7XO6F1FPre6k4cNzQpql4/edit?usp=sharing
