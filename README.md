# Trello-like_AI-Project-Tracker - Next.js

A modern project management tool inspired by Trello, built with Next.js, Supabase, and Clerk. This full-stack application provides a comprehensive board experience with drag-and-drop functionality, real-time collaboration, and subscription-based features.

<img width="1655" height="929" alt="image" src="https://github.com/user-attachments/assets/62a33327-ef66-4577-9d5f-845960af3095" />

## Demo

- Live Preview: soon will be here a vercel link

## Features

### Core Functionality
- **Kanban Board Management**: Create, edit, and organize boards with customizable colors and titles
- **Drag & Drop Interface**: Intuitive task management with smooth drag-and-drop using @dnd-kit
- **Column Management**: Create, edit, and delete columns to organize your workflow
- **Task Management**: Add tasks with titles, descriptions, assignees, priorities, and due dates
- **Real-time Updates**: Live synchronization of board changes across sessions

### Security & Data Protection
- **Row Level Security (RLS)**: Database-level security ensuring users can only access their own data
- **User Isolation**: Complete data separation between different user accounts

### User Experience
- **Modern Authentication**: Secure sign-in/sign-up with Clerk integration
- **Responsive Design**: Beautiful UI built with Tailwind CSS and Shadcn UI components
- **Dashboard Overview**: Centralized view of all your boards with statistics
- **Advanced Filtering**: Filter tasks by priority, assignee, and due dates
- **Search Functionality**: Quick search across boards and tasks

### Subscription Features
- **Free Tier**: Limited to 1 board for free users
- **Premium Plans**: Unlimited boards and advanced features via Clerk's pricing integration
- **Upgrade Prompts**: Seamless upgrade flow for free users

### Technical Features
- **TypeScript**: Full type safety throughout the application
- **Server-Side Rendering**: Optimized performance with Next.js 15
- **Database Integration**: Supabase for real-time data management
- **Component Architecture**: Modular, reusable components with feature-based organization

## Run Locally

Go to the project directory

```bash
cd trello-clone
```

Install dependencies

```bash
npm install
```

Setup Environment Variables

Create a `.env` file in the root folder and add the following variables:

```env
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

# Supabase Database
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

Start the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Tech Stack

### Frontend
- **[Next.js 15](https://nextjs.org/)** - React framework with App Router
- **[TypeScript](https://www.typescriptlang.org/)** - Type-safe JavaScript
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[Shadcn UI](https://ui.shadcn.com/)** - Beautiful, accessible components
- **[Lucide React](https://lucide.dev/)** - Icon library

### Backend & Database
- **[Supabase](https://supabase.com/)** - Backend-as-a-Service with PostgreSQL
- **[Clerk](https://clerk.com/)** - Authentication and user management

### Drag & Drop
- **[@dnd-kit](https://dndkit.com/)** - Modern drag-and-drop toolkit for React

### Development Tools
- **[ESLint](https://eslint.org/)** - Code linting
- **[PostCSS](https://postcss.org/)** - CSS processing

## Deployment

The application will be deployed on Vercel.

## Contributing

Contributions are always welcome!
