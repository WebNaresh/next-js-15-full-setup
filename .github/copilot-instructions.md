Use snake_case for all variable names.
Use PascalCase for React component names.
Use Shadcn components as they are in the @/components/ui/component-name.
If you are fetching data in a client component, use Axios with TanStack React Query v5 and and use object syntax for the query.

If a component is using client-side hooks like useQuery, create a \_components folder, create a file for the specific component within that folder, and at the top of the file, add the 'use client' declaration to mark it as a client component. Then, fetch data using the client-side hooks within that component.
