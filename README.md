# Calendar Scheduling

This project is from this [YouTube video](https://www.youtube.com/watch?v=3CMgznBdl-M) by [Jan Marshal](https://www.youtube.com/@janmarshalcoding).

Next.js v14.2.33 \
Node v18.17.1

Packages Used:

NextAuth \
Nylas \
Postgres Database with Prisma ORM \
Tailwind CSS and Shadcn UI

## Workflow

1. Create Next.js project
2. Create a Dashboard layout
3. Onboarding Route
  a. Authenticate user using Authjs + Nylas to connect with our Calendar
  b. Nylas creates the connection to our calendar, and we get a grand ID and email in return to authenticate all API requests
4. Create settings route
  a. Change profile image and change name
5. Create Availability route
6. Create Events route
  a. Create/Update/Delete
7. Create Booking form
  a. Unique URL with username
  b. Get data from our Availability page and get data from Nylas to display the correct date and available timeframes
  c. Use the Nylas API to book the event in the Calendar (in our calendar + calendar of the attendee)
8. Create the meetings route
  a. See when, with whom and the meeting call provider
9. Create a Landing page

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
