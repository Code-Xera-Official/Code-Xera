# Tech Stack and Coding Guidelines

## Tech Stack:
* Next.js 14 (App Router) for the frontend
* Supabase for the backend and database
* TypeScript as the programming language
* ShadCN (Skiper) UI for all UI components and styling
* Supabase Auth for authentication
* React Query (TanStack) for global state management and data fetching
* Supabase Realtime for real-time updates
* INNGEST webhooks for background event handling
* ImageKit or Supabase Storage for media uploads with CDN support

## Coding Guidelines:
* Use TypeScript for all JavaScript files
* Configure ESLint, Prettier, and Tailwind CSS for code quality and consistent styling
* Keep pages in `src/app/` (Next.js 14 App Router structure)
* Put components into `src/components/`
* Use ShadCN UI components for all UI elements
* Utilize Supabase Auth for authentication and authorization
* Use React Query for data fetching and global state management
* Implement responsive design using ShadCN UI components

## Library Usage Rules:
* For frontend framework, use Next.js 14 (App Router)
* For backend and database, use Supabase
* For UI components and styling, use ShadCN (Skiper) UI
* For authentication, use Supabase Auth
* For global state management and data fetching, use React Query (TanStack)
* For real-time updates, use Supabase Realtime
* For background event handling, use INNGEST webhooks
* For media uploads, use ImageKit or Supabase Storage

## Best Practices:
* Keep components small and focused (100 lines of code or less)
* Create a new file for every new component or hook
* Avoid overengineering the code; focus on the user's request and make the minimum amount of changes needed
* Use toasts or alert components to inform the user about important events
* Sanitize all user input to prevent XSS, SQL injection, and other attacks
* Enforce password security and prevent leaked/compromised passwords
* Ensure responsive design across desktop, tablet, and mobile

## Security Measures:
* Use Supabase Auth for authentication and authorization
* Enforce strong password policies and prevent the use of leaked/compromised passwords
* Implement rate-limiting and brute-force protections if performance allows
* Sanitize all user input to prevent XSS, SQL injection, and other attacks

## Deployment:
* Deploy frontend to Vercel
* Deploy backend to Supabase Cloud using the provided project URL and keys
* Ensure environment variables are configured securely
* Optimize build for performance, caching, and SEO