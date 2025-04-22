# Next.js Blog with PostgreSQL Database Integration

This repository contains the database integration files for a modern blog website built with Next.js, Tailwind CSS, and PostgreSQL using Drizzle ORM.

## Overview

This integration adds PostgreSQL database support to a Next.js blog application. The implementation uses Drizzle ORM for database operations and includes models for users, posts, and comments.

## Key Files

- `server/db.ts`: Database connection setup
- `shared/schema.ts`: Database schema definitions
- `server/storage.ts`: Storage implementation for database operations

## Database Structure

The application uses a PostgreSQL database with the following tables:

- **Users**: Stores user information (username, email, password, etc.)
- **Posts**: Stores blog post content (title, content, slug, category, etc.)
- **Comments**: Stores comments on blog posts

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Set up environment variables (see below)
4. Run the development server: `npm run dev`

## Environment Variables

Create a `.env` file in the root directory with the following variables:

```
DATABASE_URL=postgresql://username:password@host:port/database
```