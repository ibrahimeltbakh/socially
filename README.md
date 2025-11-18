# Socially – Full Stack Social Media Platform

[Live Demo](https://socially-six-khaki.vercel.app/) • [GitHub Repository](https://github.com/ibrahimeltbakh/socially)

Socially is a full-stack social media platform built with Next.js and Tailwind CSS, featuring server-side rendering, authentication, and database integration. Users can create accounts, post content, follow others, and interact with posts through likes and comments.

## Features

### User Features
- **Authentication**: Sign up, login, and secure authentication using Clerk.
- **User Profiles**: Edit profile, upload avatar, and view other users’ profiles.
- **Posts & Interactions**: Create, like, comment, and share posts.
- **Follow System**: Follow/unfollow other users.
- **Notifications**: Receive updates on post interactions.
- **Responsive Design**: Fully responsive UI for mobile and desktop.
- **Dark & Light Modes**: Switch between themes.


## Tech Stack
- **Frontend**: Next.js, Tailwind CSS, Next Themes
- **Backend & Database**: Prisma, Neon DB
- **Authentication**: Clerk
- **File Uploads**: UploadThing
- **UI Components**: Radix UI, Lucide React
- **State & Utilities**: Tailwind Merge, Class Variance Authority
- **Notifications**: React Hot Toast
- **Type Safety**: TypeScript

## Installation

1. Clone the repository:
   ```bash
      git clone https://github.com/ibrahimeltbakh/socially
2.Install dependencies:
  npm install
3.Run the development server
  npm run dev
Open http://localhost:3000
 to view the app.

Project Structure

Home / Feed – Main feed with posts from followed users.

Profile – User profile management.

Post Management – Create, edit, delete posts.

Follow System – Manage following/followers.

Admin Panel – User and content moderation.

Notes

Project marked as private repository.

Environment variables are required for Clerk authentication and Prisma/Neon DB connection.

Fully server-side rendered for better performance and SEO.

   ```bash
   git clone https://github.com/ibrahimeltbakh/socially
