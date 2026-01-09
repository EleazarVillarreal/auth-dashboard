# Auth Dashboard

A [Next.js](https://nextjs.org) application demonstrating how to use [Supabase](https://supabase.com) for authentication, CRUD operations, and image uploads.

## About This Project

This project showcases modern authentication and data management patterns using:

- **Supabase Authentication** - User signup, login, and session management
- **CRUD Operations** - Create, read, update, and delete data with Supabase
- **Image Uploads** - Handle file uploads using Supabase Storage

> **Note:** This project is currently under development. The README will be updated with detailed implementation instructions as Supabase features are integrated.

## Getting Started

### Prerequisites

- Node.js 24+ installed on your machine
- A Supabase account and project (create one at [supabase.com](https://supabase.com))

### Installation

1. Clone this repository:

```bash
git clone <repository-url>
cd auth-dashboard
```

2. Install dependencies:

```bash
npm install
```

3. Set up your environment variables:

```bash
cp .env.example .env.local
```

Add your Supabase credentials to `.env.local`:

```
NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
```

4. Run the development server:

```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Tech Stack

- **Framework:** Next.js 16 (App Router)
- **Database & Auth:** Supabase
- **Styling:** Tailwind CSS
- **Language:** TypeScript

## Features (Coming Soon)

- User authentication (signup, login, logout)
- Protected routes and middleware
- CRUD operations with real-time updates
- Image upload and management
- User dashboard

---

Built with Next.js and Supabase
