🔧 Setup & Installation Guide

Follow the steps below to run the project locally on your machine.

1️⃣ Clone the Repository git clone https://github.com/your-username/travel-agent-landing-page.git

Move into the project folder:

cd travel-agent-landing-page

2️⃣ Install Dependencies

Make sure you have Node.js installed (v16+ recommended).

Install all required packages:

npm install

3️⃣ Configure Tailwind CSS

If Tailwind is included in the repo, you're good. If not, install and initialize Tailwind:

npm install -D tailwindcss postcss autoprefixer npx tailwindcss init -p

Ensure the following is added inside tailwind.config.js:

content: [ "./src/**/*.{js,jsx,ts,tsx}", ],

Add Tailwind directives to index.css or global.css:

@tailwind base; @tailwind components; @tailwind utilities;

4️⃣ Run the Development Server

Start the app:

npm start

Your app will run on:

http://localhost:3000/

5️⃣ GSAP Setup (Already Included)

If you need to install GSAP manually:

npm install gsap

You can now import GSAP anywhere:

import { gsap } from "gsap";

6️⃣ Custom Hooks

Custom hooks may be located in:

/src/hooks/

7️⃣ Build for Production

To create an optimized build:

npm run build

Output will be generated in:

/build

🌍 TravelEase — Intelligent Travel Agent Landing Page

A modern, interactive landing page designed to help users explore travel services with ease and immersion.

📌 Project Overview

TravelEase is a highly interactive and visually rich travel agent landing page built to showcase premium travel services in an engaging way. The interface is crafted to provide visitors with a seamless browsing experience, featuring smooth animations, responsive layouts, and intuitive navigation.

The goal of the project is to elevate the travel discovery experience by blending aesthetic design with fluid interaction, making users feel like they’re stepping into a world of endless travel possibilities.

✨ Key Features 🌐 Dynamic Hero Section

Eye-catching visuals with smooth transitions

Engaging headline that invites users into the journey

📍 Interactive Service Exploration

Cards, sections, or feature blocks that highlight travel packages

Smooth scroll-trigger animations powered by GSAP

💬 Smart Navigation

Sticky / animated navbar that reacts to user scroll

Navigation links smoothly transition to different sections

📱 Fully Responsive

Mobile-first design

Tailwind CSS-based layout ensures perfect scaling across devices

🎞 Motion & Immersion

GSAP animations for section reveals, text effects, parallax, and interactions

Creates a cinematic, premium feel for the landing page

🧠 Tech Stack Frontend Technologies

HTML5 (Advanced structure & semantics)

Tailwind CSS (Utility-first responsive UI)

React.js (Component architecture & state management)

React Custom Hooks (Reusable logic for animations, scroll behavior, UI interactions)

Animation & UX Enhancement

GSAP (GreenSock Animation Platform) Used for scroll animations, page transitions, staggered effects, and motion choreography.
