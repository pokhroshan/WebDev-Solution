# Confederation College Programs - Junior Web Developer Test

A static one-page site displaying programs from Confederation College, built with Astro and Tailwind CSS.

## Features

- Displays program names, mission statements (with fallback), and links to Confederation College program pages
- Responsive grid layout for desktop and mobile
- Clean, accessible UI
- Client-side pagination for improved navigation

## Tech Stack

- [Astro](https://astro.build/) - Static site framework
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS
- Vanilla JavaScript for client-side pagination

## Data

- Uses the provided `program-data.json` file
- Each card shows:
  - Program name
  - Mission statement (or fallback `"No description yet."`)
  - Program link constructed from `slug.current`

## Running Locally

1. Clone this repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open `http://localhost:4321` in your browser

## Deployment

- Deployed on Netlify: [Live Site](https://legendary-cuchufli-058582.netlify.app/)
- GitHub Repository: [Github Repo](https://github.com/pokhroshan/WebDev-Solution)

## Time Spent

- Setup: 15 minutes
- Development: 45 minutes
- Testing and deployment: 15 minutes  
    Total: ~75 minutes

## Design Choices

- Used the provided Astro starter template for consistent CC branding
- Implemented responsive grid layout for optimal display on all devices
- Added clear fallback text for missing mission statements
- Ensured external links open in new tabs for improved UX
- Utilized Tailwind CSS for a clean, accessible UI