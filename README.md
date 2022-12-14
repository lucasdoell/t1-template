This is a [Next.js](https://nextjs.org/) template project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

This template is a JavaScript version of my [T2 Template](https://github.com/lucasdoell/t2-template), inspired by [create-t3-app](https://github.com/t3-oss/create-t3-app). If you don't want the extra complexity with TypeScript, this template may be the right choice for you. It includes:
- Tailwind CSS
  - [Prettier for Tailwind](https://github.com/tailwindlabs/prettier-plugin-tailwindcss) support
- An SEO component for easy meta tags
- Custom `_document.js` and `_app.js` files
- Recommended extensions for better DX

Feel free to add node modules as the project needs. This template is meant to be a starting point for your project, not a finished product. 
Therefore, modules such as tRPC and Prisma are not included, as they may not be necessary for simple websites. If you would like to create a project 
with those configured by default, check out [create-t3-app](https://github.com/t3-oss/create-t3-app). 

## Getting Started

Run the following command to create a new project:

```bash
npx create-next-app [project-name] -e https://github.com/lucasdoell/t1-template
# or
yarn create next-app [project-name] -e https://github.com/lucasdoell/t1-template
```

Then, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
