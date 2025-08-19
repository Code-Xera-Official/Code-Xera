# Tech Stack and Coding Guidelines

## Tech Stack:
* React application
* TypeScript as the programming language
* React Router for client-side routing
* Tailwind CSS for styling components
* shadcn/ui library for prebuilt UI components
* Lucide-react for icons
* Radix UI components for advanced UI elements

## Coding Guidelines:
* Use TypeScript for all JavaScript files
* Keep routes in `src/App.tsx`
* Put pages into `src/pages/`
* Put components into `src/components/`
* The main page is `src/pages/Index.tsx`
* Always update the main page to include new components
* Use Tailwind CSS classes for layout, spacing, colors, and other design aspects
* Utilize prebuilt components from the shadcn/ui library when possible
* Use lucide-react for icons

## Library Usage Rules:
* For routing, use React Router
* For styling, use Tailwind CSS
* For icons, use lucide-react
* For prebuilt UI components, use shadcn/ui library
* For advanced UI elements, use Radix UI components

## Best Practices:
* Keep components small and focused (100 lines of code or less)
* Create a new file for every new component or hook
* Avoid overengineering the code; focus on the user's request and make the minimum amount of changes needed
* Use toasts to inform the user about important events
* Do not catch errors with try/catch blocks unless specifically requested by the user