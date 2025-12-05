# SocialX

SocialX is a modern social media platform built with **Next.js**, **Prisma**, and **Clerk**. It allows users to create profiles, follow other users, and discover new connections in a sleek, responsive interface.

## Features

- **User Authentication** via Clerk
- **User Profiles** with custom usernames, images, and posts
- **Follow System** to connect with other users
- **Random User Suggestions** to explore new connections
- **Notifications** for new followers
- **Server-side Actions** using Next.js server functions for optimized performance

## Tech Stack

- **Frontend:** Next.js, React, Tailwind CSS  
- **Backend:** Next.js API routes, Prisma ORM  
- **Database:** PostgreSQL  
- **Authentication:** Clerk  
- **File Uploads:** UploadThing  
- **Deployment:** Vercel (optional)  

## Environment Variables

Create a `.env` file in the root of the project and add the following variables:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
UPLOADTHING_TOKEN=your_uploadthing_token
DATABASE_URL=your_postgresql_database_url
