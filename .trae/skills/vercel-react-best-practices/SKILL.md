---
name: "vercel-react-best-practices"
description: "Provides guidance and implementation of best practices for Vercel deployment and React development. Invoke when setting up, optimizing, or troubleshooting Vercel projects or React code."
---

# Vercel & React Best Practices

This skill helps ensure your project follows the latest industry standards for Vercel and React.

## When to Use

Invoke this skill when:
- Setting up a new project for Vercel deployment.
- Optimizing React component performance or structure.
- Troubleshooting deployment issues on Vercel.
- Implementing Vercel-specific features like Serverless Functions, Edge Middleware, or Analytics.
- Ensuring React code follows modern patterns (Hooks, Composition, etc.).

## Core Guidelines

### Vercel Deployment
1. **Configuration**: Use `vercel.json` for custom routing, headers, and redirects.
2. **Environment Variables**: Always use `.env.local` for local development and manage production secrets via the Vercel Dashboard.
3. **Build Optimization**: Ensure build scripts are efficient and avoid unnecessary dependencies.
4. **Edge Functions**: Use Edge Middleware for low-latency tasks like authentication or A/B testing.

### React Development
1. **Component Structure**: Prefer functional components with Hooks. Keep components small and focused.
2. **State Management**: Use local state (`useState`) where possible; elevate state only when necessary. Use Context API or libraries like Zustand/Redux for global state.
3. **Performance**: Use `useMemo` and `useCallback` to prevent unnecessary re-renders in performance-critical areas.
4. **Data Fetching**: Use libraries like SWR or React Query for efficient data fetching and caching.

## Usage Example

"Help me optimize my React components for Vercel deployment" -> Trigger this skill to review structure, config, and performance.
