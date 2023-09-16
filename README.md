# [AI Chatbot Platform](https://ai-dashboard-senz.vercel.app)
Inspired by [Character.AI](https://character.ai)

![Project Logo](/resources/banner.png)

## Overview

An [AI Chatbot Platform](https://ai-dashboard-senz.vercel.app), that allows users to create and interact with AI chatbots. Users can easily design, and deploy chatbots for various purposes, and also use chatbots created by others. This project is built using React, Next.js, and a variety of other technologies.

## Features

- **Create Your Own Chatbots**: Users can design and customize their AI chatbots.

- **Explore Community Bots**: Discover and use chatbots created by other users in the platform's community.

- **Integration with Stripe**: Monetize your chatbots by offering premium features or content through Stripe payments.

- **User Authentication**: Utilizes Clerk for user authentication.

- **Data Storage**: Prisma, MongoDB, Pinecone, and Upstash are used for data storage and retrieval.

## Technologies Used
- **Frontend**: React, Next.js 13, Tailwind CSS (Shadcn UI)
- **Backend**: Prisma, MongoDB
- **Payment Processing**: Stripe
- **User Authentication**: Clerk
- **Data Storage**: Pinecone (Vector DB), Upstash (Redis DB)

## Getting Started

To get a copy of this project up and running on your local machine for development and testing purposes, follow these steps:

1. Clone the repository:
```
git clone https://github.com/svxf/ai-dashboard
cd ai-dashboard
```

2. Install dependencies:

```npm install```

Configure Environment Variables: Create a .env file and add your environment variables:
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=key
CLERK_SECRET_KEY=key

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

DATABASE_URL="mongodb+srv://username:<password>@host/DATABASE"

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=name

PINECONE_INDEX = "companion"
PINECONE_ENVIRONMENT="gcp-starter"
PINECONE_API_KEY=api_key

UPSTASH_REDIS_REST_URL=url
UPSTASH_REDIS_REST_TOKEN=token

OPENAI_API_KEY=key

REPLICATE_API_TOKEN=token

STRIPE_API_KEY=key

STRIPE_WEBHOOK_SECRET=secret

NEXT_PUBLIC_APP_URL=http://localhost:3000
```

3. Start the development server:

```npm run dev```
