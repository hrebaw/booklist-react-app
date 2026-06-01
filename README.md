# Booklist React App

A full-stack React application for managing and browsing a book list. This project features a TypeScript-based client and server architecture.

## Project Structure

```
booklist-react-app/
├── client/                 # React frontend application
│   ├── public/            # Static assets
│   ├── src/
│   │   ├── components/    # React components
│   │   ├── api/           # API integration
│   │   ├── App.tsx        # Main app component
│   │   └── index.tsx      # Entry point
│   ├── package.json
│   └── tsconfig.json
│
└── server/                # Backend server
    ├── index.ts          # Server entry point
    ├── package.json
    └── tsconfig.json
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/hrebaw/booklist-react-app.git
cd booklist-react-app
```

2. Install dependencies for both client and server:

**Client:**
```bash
cd client
npm install
```

**Server:**
```bash
cd ../server
npm install
```

### Running the Application

**Start the client (from the `client` directory):**
```bash
npm start
```
The app will open in your browser at [http://localhost:3000](http://localhost:3000)

**Start the server (from the `server` directory):**
```bash
npm start
```
The server will run on a configured port.

## Available Scripts

### Client Scripts

- `npm start` - Run the development server
- `npm test` - Run tests
- `npm run build` - Build for production
- `npm run eject` - Eject from Create React App (one-way operation)

### Server Scripts

Refer to [server/package.json](server/package.json) for available scripts.

## Technologies

- **Frontend:** React, TypeScript, CSS
- **Backend:** Node.js, TypeScript
- **Build Tools:** Create React App, TSC

## Features

- Browse and manage books
- Responsive UI with custom components
- Type-safe codebase with TypeScript
- RESTful API integration

## License

See LICENSE file for details.
