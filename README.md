# CuriousHeads - Premium Education Social Platform

A beautiful, Instagram-style education social platform built with React, TypeScript, and modern web technologies.

## 🚀 Features

### Core Pages
- *Landing Page* - Marketing hero with features showcase
- *Authentication* - Login/Register with validation
- *Dashboard* - Smart feed with AI-suggested content
- *Explore* - Question discovery with search and filters
- *Ask Question* - Rich text editor with file attachments
- *Question Detail* - Answers, upvoting, comments system
- *Notes* - Study materials sharing platform
- *Contests* - Competitive challenges and leaderboards
- *Profile* - XP system, badges, skills tracking
- *Notifications* - Real-time activity updates

### Design System
- *Premium Gradients* - Royal blue → Violet → Teal palette
- *Glassmorphism* - Modern glass card effects
- *Responsive Design* - Desktop sidebar, mobile bottom nav
- *Dark/Light Mode* - Theme switching with persistence
- *Animations* - Framer Motion micro-interactions

### Technical Features
- *TypeScript* - Full type safety
- *Zustand* - State management
- *Mock API* - Complete data layer simulation
- *Responsive* - Mobile-first design approach
- *Accessibility* - ARIA attributes and keyboard navigation

## 🛠 Tech Stack

- *Frontend*: React 18, TypeScript, Vite
- *Styling*: TailwindCSS, Custom design system
- *Animations*: Framer Motion
- *Routing*: React Router v6
- *State*: Zustand
- *UI Components*: Shadcn/ui + Custom components
- *Icons*: Lucide React

## 📦 Installation

bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview


## 🔧 Development

The app runs on http://localhost:5173 in development mode.

### Mock Authentication
- Email: demo@curiousheads.com
- Password: demo123

## 🎨 Design System

The app uses a comprehensive design system with:
- *Colors*: HSL-based color tokens in src/index.css
- *Components*: Customized Shadcn components
- *Gradients*: Premium royal blue to teal gradients
- *Glass Effects*: Backdrop blur with transparency
- *Typography*: Inter font family

## 🔀 API Integration

Currently uses mock APIs in src/lib/api-mocks.ts. To integrate with a real backend:

1. Replace mock functions with actual API calls
2. Update the base URL in API client
3. Handle authentication tokens
4. Update data types if needed

## 📱 Responsive Design

- *Desktop*: Sidebar navigation, multi-column layouts
- *Tablet*: Adapted layouts with collapsible elements  
- *Mobile*: Bottom navigation, single-column stacks

## ⚡ Performance

- *Code Splitting*: Pages are lazy-loaded
- *Optimized Images*: Responsive image loading
- *Efficient Rendering*: React best practices
- *Bundle Size*: Tree-shaking enabled

## 🚀 Deployment

The app is ready for deployment to any static hosting service:

bash
npm run build
# Deploy the `dist` folder
