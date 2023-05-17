> **NOTICE!** This repo is currently under active development. Please check back periodically for updates.

This is a [Next.js](https://nextjs.org/) app made explicitly for Payload's [Website Template](https://github.com/payloadcms/template-website).

Key features:

- Payload, Next.js, GraphQL, TypeScript
- Pre-made layout building blocks
- [Payload Admin Bar](https://github.com/payloadcms/payload-admin-bar)
- Complete SEO solution

## Getting Started

### Payload

First you'll need a running Payload instance. If you have not done so already, clone the [Payload Website Template](https://github.com/payloadcms/template-website) and follow the setup instructions. Take note of your server URL, you'll need this in the next step.

### Next.js App

First, get your environment setup:

1. First copy the example `.env` file as your own:

   ```bash
     cp .env.example .env
   ```

1. Then open the `.env` file and paste your Payload server URL:

   ```bash
     NEXT_PUBLIC_CMS_URL=http://localhost:8000
   ```

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying the documents within your CMS.

## Learn More

To learn more about Payload and Next.js, take a look at the following resources:

- [Payload Documentation](https://payloadcms.com/docs) - learn about Payload features and API.
- [Payload GraphQL Documentation](https://payloadcms.com/docs/graphql/overview) - Payload's GraphQL documentation.
- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.
- [Payload + Next.js Preview Example](https://github.com/payloadcms/payload/tree/master/examples/preview/nextjs) - Payload's example of how to preview Next.js apps
- [Payload Admin Bar](https://github.com/payloadcms/payload-admin-bar) - A React component used to easily navigate to and from Payload

You can check out the [Payload GitHub repository](https://github.com/payloadcms/payload/) as well as the [Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Payload deployment documentation](https://payloadcms.com/docs/production/deployment) or the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
