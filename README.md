# STEPS

1. Installation
   1. create backend and frontend folder
   2. cd frontend
      1. npx create-next-app@latest 
       - Would you like to use TypeScript? Yes
       - Would you like to use ESLint? Yes
       - Would you like to use Tailwind CSS? Yes
       - Would you like to use `src/` directory? Yes
   3. cd backend
      1. npx create-strapi-app@latest .
          - Do you want to use the default database (sqlite)? No
          - Choose your default database client: postgres
          - Database name: strapi
          - Host: 127.0.0.1
          - Port: 5432
          - Username: [your database username]
          - Password: [your database password]
          - Enable SSL connection: Yes
          - Start with an example structure & data? No
          - Start with Typescript? Yes
          - Install dependencies with npm? Yes
          - Initialize a git repository? No

2. Create .env variables
   1. Frontend can be done with .env.local
   2. Backend should be done with .env
3. Install GraphQL on backend
4. Run frontend and backend
   1. Frontend: npm run dev
   2. Backend: npm run develop