Eco-KITAR: Malaysia's Smart Recycling Ecosystem

Eco-KITAR is a revolutionary twin-app platform designed to digitize waste management in Malaysia, connecting households, collectors, and government agencies to drive verifiable carbon reduction and establish a profitable circular economy.

Our motto: Smartest Recycling Ecosystem in the world.

🚀 Key Platform Components

Eco-KITAR is built on a dual-app structure tailored to specific user roles:

Component

Target User

Primary Functionality

Eco-Rakyat App

Households / Users

Snap-and-list items, AI Recycling Coach, instant rewards, and fraud reporting.

Eco-Rider App / Dashboard

Collectors / Logistics

AI Route Planner, dedicated dashboard for tracking collections, payouts, and efficiency metrics.

Jabatan Dashboard

Government / Admin

Real-time tracking of waste collected, trends, and verifiable ESG metrics (CO₂ saved).

🛠️ Technologies & Frameworks

Our solution uses a modern, scalable stack to handle high volumes of data, real-time logistics, and complex AI inferences.

1. Frontend

Next.js / React: Used for building the web interfaces for the EcoRakyat, Eco-Rider, and Jabatan dashboards, ensuring a fast, modern, and responsive user experience.

2. Backend

Node.js + Express: Serves as the robust API layer, handling all critical functions including: API endpoints, processing AI requests, managing database communication, and secure image uploads.

3. Database

PostgreSQL (with Drizzle ORM): Chosen for its reliability and scalability. Stores all core platform data: recyclable item records, dynamic rider routes, user rewards, AI classification results, and system logs.

4. Storage / Hosting

Replit: Utilized for rapid development, testing, and deployment, integrating the frontend, backend, and database within a unified environment.

🧠 Artificial Intelligence Services

Eco-KITAR’s intelligence is powered by two distinct services, ensuring specialized and powerful functionality:

A. HuggingFace API (Image Recognition)

Purpose: Rapid, initial classification of user-uploaded images (e.g., bottle, can, paper).

Function: Classifies items and maps labels to standard recyclable categories (plastic, paper, glass, metal).

Used In: The initial "snap a pic" feature in the Eco-Rakyat app.

B. Google Gemini API 2.5 Flash (Advanced Reasoning, Text & Maps)

Purpose: Powers all advanced conversational AI and predictive logistics.

Key Assistants:

AI Recycling Coach: Explains item recyclability and teaches proper disposal behavior to users (Eco-Rakyat).

AI Rider Assistant: Helps Eco-Riders with fieldwork questions, route issues, and item clarifications.

AI Route Planner: Analyzes real-time data and provides suggestions for faster or more efficient collection paths.

✨ What Makes Eco-KITAR's AI Unique

Our AI is specifically engineered for the waste management context, making it superior to general-purpose solutions:

Recycling-Specific, Not Transport: The AI is trained and prompted specifically for the waste management context, focusing on material compatibility and CO₂ reduction, not just basic transport logistics.

Bilingual Conversational AI: Provides full, culturally relevant support in both English and Malay (Bahasa Malaysia), ensuring accessibility for all Malaysian users.

Multi-Turn Image Analysis: The Gemini API moves beyond simple classification. It can analyze images and ask follow-up questions to ensure data quality (e.g., prompting the user to confirm a specific recycling number).

Category-Aware Route Optimization: The AI considers material types when planning routes to prevent cross-contamination (e.g., keeping batteries separate from organic waste) while calculating verifiable fuel savings and CO₂ reduction metrics.

Role-Based AI Assistants: Each user persona gets a specialized AI: the Eco-Rakyat gets a friendly "Recycling Coach," while the Eco-Rider gets a practical "Rider Assistant" tailored for fieldwork challenges.
