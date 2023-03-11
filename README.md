# Docker Compose & Next.js & MongoDB

## Getting Started

First, run the development server:

```bash
docker compose up
# or
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## API

### GET /api/posts

```
curl http://localhost:3000/api/posts
```

### POST /api/posts

```
curl -X POST -d "title=awesome" http://localhost:3000/api/posts

curl -X POST -H 'Content-Type: application/json' -d '{"title": "awesome"}' http://localhost:3000/api/posts
```

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
