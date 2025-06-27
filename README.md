# Niobi Challenge 2 - Treasury Management App

A modern treasury management application built with React, TypeScript, and Vite. This app provides functionality for managing accounts and tracking financial transactions across multiple currencies.

## 🚀 Live Demo

[**View Live Application**](https://niobi-challenge-2.vercel.app/)

## ✨ Features

- **Account Management**: Create and manage accounts in multiple currencies (KES, USD, NGN)
- **Transaction Tracking**: Record and view transfer logs between accounts
- **Multi-Currency Support**: Handle transactions with automatic currency conversion
- **Responsive Design**: Mobile-friendly interface with bottom navigation
- **Real-time Updates**: Live transaction monitoring and account balance updates

## 🛠️ Tech Stack

- **React 19** - UI library
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **React Router DOM** - Client-side routing
- **Styled Components** - CSS-in-JS styling
- **ESLint** - Code linting

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── bottom-nav/     # Bottom navigation
│   ├── buttons/        # Button components
│   ├── cards/          # Account cards
│   ├── forms/          # Transfer forms
│   └── tables/         # Transaction tables
├── pages/              # Application pages
│   ├── accounts/       # Account management page
│   └── tansfer-logs/   # Transaction history page
├── types/              # TypeScript type definitions
├── context/            # React context providers
└── utils/              # Utility functions
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone <innocentmayemuhavi/niobi_challenge_2>
cd niobi_challenge_2
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser

### Available Scripts

- `npm run dev` - Start development server with HMR
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint

## 🔧 Development Setup

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
