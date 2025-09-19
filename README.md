The Oneironaut - An AI-Powered Instrument for Dream Analysis
Project Overview
The Oneironaut is a sophisticated, immersive web application designed to facilitate deep self-reflection through the analysis of dreams. It serves as a bridge between the user's subconscious and their conscious mind, leveraging a powerful generative AI to translate dream narratives into structured, thematic insights.

The application's core is its unique persona—The Oneironaut—an AI guide that engages the user in a dialogue to uncover the symbolic and psychological wisdom embedded in their dreams. The user interface is intentionally dark, atmospheric, and mystical, featuring a dynamic particle background to create a focused and contemplative space for introspection.

This project was conceived and developed by Anthony Perry.

Core Features
AI-Powered Dream Analysis: Utilizes the Google AI API (Gemini) to perform a deep, thematic analysis of the user's dream narrative and its emotional core.

Interactive Dialogue System: After the initial analysis, the user can engage in a follow-up conversation with The Oneironaut to explore specific symbols, feelings, or themes in greater depth.

Dynamic & Immersive UI: Features a generative background animation created with the HTML Canvas API, and a "glassmorphism" aesthetic to create a focused, otherworldly user experience.

Structured, Insight-First Output: The AI's analysis is presented in an interactive accordion format, allowing the user to explore different facets of the interpretation at their own pace.

Security-First Design: Implemented with a strict Content-Security-Policy (CSP) and Permissions-Policy to protect against common web vulnerabilities like Cross-Site Scripting (XSS) and clickjacking.

Responsive Layout: The interface is fully responsive, ensuring a seamless experience on both desktop and mobile devices.

How It Works
User Input: The user provides two key pieces of information: the narrative of their dream and the "emotional core" they felt upon waking.

AI Analysis: This input is synthesized into a detailed prompt and sent to the AI, which is instructed to return a structured JSON object containing multiple thematic insights and an actionable "integration" step.

Interactive Display: The application parses the AI's response and displays it in a clean, interactive accordion interface.

Deepen Dialogue: The user can then ask follow-up questions in a chat interface, continuing the conversation with the AI to gain further clarity.

Technologies Used
Frontend: HTML5, CSS3, JavaScript (ES6+)

Styling: Tailwind CSS for utility-first styling.

AI Integration: Google AI Generative Language API (Gemini).

Graphics: HTML Canvas API for the dynamic background animation.

Setup and Usage
To run this project locally, clone the repository and open the index.html file in any modern web browser. No special build steps or dependencies are required.

*This project is intended as a portfolio piece and a demonstration of advanced frontend development, AI integration,
