# V0.App Frontend

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app), enhanced with comprehensive CI/CD and testing capabilities.

## 🚀 Features

- Automated builds and deployments
- Comprehensive testing suite
- TypeScript support
- Monaco Editor integration
- Automated code formatting
- Multiple deployment targets (Vercel, GitHub Pages)

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

## 🔄 CI/CD Pipeline

This project uses GitHub Actions for automated CI/CD. The pipeline includes:

- Automated builds on push/PR
- Jest testing suite
- TypeScript type checking
- ESLint code quality checks
- Automated deployments to:
  - Vercel (Production)
  - GitHub Pages (Preview)

### Available Scripts

```bash
# Development
npm run dev        # Start development server
npm run typecheck  # Run type checking
npm run lint      # Run linting
npm run format    # Format code

# Testing
npm test         # Run tests
npm test:watch   # Run tests in watch mode
npm test:coverage # Run tests with coverage

# Production
npm run build    # Build for production
npm run start    # Start production server
npm run export   # Export static site
```

## 📦 Project Structure

```
frontend/
├── src/
│   ├── app/           # Next.js app directory
│   │   ├── components/  # React components
│   │   ├── editor/     # Code editor components
│   │   └── projects/   # Project-related pages
│   └── lib/          # Utility functions
├── public/           # Static assets
└── tests/           # Test files
```

## 🚀 Deployment

### Vercel (Primary Deployment)

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

- Automatic deployments on push to main
- Preview deployments for pull requests
- Analytics and performance monitoring

### GitHub Pages (Secondary Deployment)

The app is also automatically deployed to GitHub Pages:
- Static export generated automatically
- Accessible through GitHub Pages URL
- Useful for documentation and demos

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
