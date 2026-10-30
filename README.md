# CampusDesk Student Management Frontend

A small React + Vite frontend for deployment practice. It has sample student records and working search, add, and delete interactions.

## Run locally
1. Extract the ZIP and open this folder in VS Code.
2. Open a terminal in this folder.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL shown in the terminal, usually http://localhost:5173.

## Deploy on Vercel
1. Push this folder to a GitHub repository.
2. In Vercel, choose Add New → Project and import the repository.
3. Framework preset: Vite
4. Build command: `npm run build`
5. Output directory: `dist`
6. Click Deploy.

## Deploy on Netlify
Import the GitHub repository in Netlify. Set build command to `npm run build` and publish directory to `dist`.

## Note
This is a frontend-only demo. Data is held in React state and resets after refreshing. It does not include an Express backend or MongoDB database, so it is suitable for practicing frontend deployment, not a complete MERN deployment.
