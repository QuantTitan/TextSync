# TextSync

A collaborative document editor built for the Software Data Engineering course.

## Contributors
- Aansh Dubey (B22AI058)
- Banoth Sri Kowshika Raj (B22CS018)
- Mukund Gupta (B22CS086)

## Overview
TextSync is a real-time collaborative document editor designed to help users create, edit, and share documents seamlessly. Multiple users can work together on the same document, see live changes, and communicate through comments.

## Features
- Secure user authentication
- Real-time collaborative editing
- Document creation, sharing, and management
- Inline and threaded comments
- Presence indicators for active collaborators
- Responsive design for all devices

## Tech Stack
- Next.js
- TypeScript
- Tailwind CSS
- Liveblocks
- Lexical Editor

## Getting Started

### Prerequisites
- Git
- Node.js
- npm

### Installation
1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd textsync
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables in a `.env` file:
   ```env
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
   LIVEBLOCKS_SECRET_KEY=
   ```
   Fill in your credentials from Clerk and Liveblocks.

4. Start the development server:
   ```bash
   npm run dev
   ```
   Visit [http://localhost:3000](http://localhost:3000) in your browser.

## License
This project is for educational purposes as part of the Software Data Engineering course.