# apoorv-dhaygude-portfolio-v0

## Portfolio Link: https://v0-apoorv-dhaygude-portfolio-3omaze.vercel.app/

## Prompts to create Portfolio:


Prompt 1:
Create a responsive personal portfolio website using Tailwind CSS and ShadCN components.
Sections:
1. Hero Section: Full screen background with my name "Apoorv Pratap Dhaygude", title "Data Engineer | MS in Information Systems @ Northeastern University", and a call-to-action button labeled "Get in Touch".
2. Projects Section: Title "Projects". Show three cards with titles, technologies used, and bullet points. Projects:
  - Food Inspection Analysis | Azure Data Factory, ETL/ELT: 
    • Integrated 10+ data sources improving accuracy by 25%
    • Reduced integration time by 60% using Azure Data Factory
    • Built 7+ calculated transformations for real-time insights
  - Medical Device Sales Performance | Snowflake, Apache Spark, Tableau: 
    • Consolidated 100M+ records using Snowflake
    • Ingested 50GB+ data with Spark
    • Created 15+ Tableau dashboards, increasing insights by 30%
  - Hospital Management System | PostgreSQL, Python, SQL:
    • Managed 500K+ records with relational database
    • Improved queries by 40% using partitioning and indexing
    • Generated 20+ SQL queries for treatment/billing insights
3. Contact Section: Include email (dhaygude.a@northeastern.edu), LinkedIn (linkedin.com/in/apoorv-dhaygude), location (Boston, MA).


Prompt 2: (Iteration)
Make the hero section full height and center all text vertically. Use a dark background (#1a1a1a) with white text. Add a white border and soft shadow to each project card. On desktop, use a two-column layout for projects. On mobile, use a single column.


Prompt 3: 
Ensure all layout and styling is done with Tailwind CSS utility classes. Use ShadCN components where appropriate: Button for the call-to-action, Card for project cards, and Input/Link elements in the contact section.


Prompt 4:
Break this UI into reusable components:
- HeroSection
- ProjectsSection
- ProjectCard (used in ProjectsSection)
- ContactSection
Ensure each component is self-contained and uses Tailwind CSS + ShadCN components.


Prompt 5: (Iteration)
Add smooth fade-in and slide-in animations to all major sections (Hero, Projects, Contact) when they scroll into view. Use Framer Motion for the animations and integrate it with Tailwind CSS.


Prompt 6:
Add hover effects to the call-to-action button and project cards. On hover, buttons should scale up slightly with a shadow. Project cards should slightly lift and show a subtle border glow.


Prompt 7:
Add a dark/light theme toggle button in the top-right corner using ShadCN's Switch component or a toggle icon. Connect it to Tailwind's dark mode classes and persist the preference using localStorage.


Prompt 8:
Add this one more project Movie Recommendation System | Python (Scikit-learn, Pandas), Tableau Oct 2023 – Dec 2023
• Built a KNN-based collaborative filtering recommendation system using user ratings and metadata for 1M+ movies
• Preprocessed and cleaned 1M+ rows of data with advanced data preprocessing techniques to ensure high-quality inputs
• Trained and evaluated the model with 85% accuracy in predicting user preferences, reducing errors by 20%
Food Inspection Analysis | Azure Data Factory, ETL/ELT
• Visualized user preference patterns and rating trends in Tableau, creating 10+ interactive dashboards for insights


Prompt 9:
Add a dark/light theme toggle button in the top-right corner using ShadCN's Switch component or a toggle icon. Connect it to Tailwind's dark mode classes and persist the preference using localStorage.
Add a sticky top navigation bar with links: Home, Projects, Contact. When clicked, the page should smoothly scroll to the corresponding section. Highlight the active section in the navbar.
In the hero or contact section, add a "Download Resume" button that links to a hosted PDF file (Resume_APD_2025.pdf). Use ShadCN's Button component and a download icon.
For each project card, add logos or icons representing the tech stack (like Python, Spark, Tableau, PostgreSQL). Use Lucide-react or Heroicons, or import logos from a CDN. Display them in a row at the bottom of each card.
Ensure all layout elements are mobile-first with proper padding and touch targets. Increase spacing between buttons on small screens. Stack project card content vertically for better readability on mobile.
Ensure all layout elements are mobile-first with proper padding and touch targets. Increase spacing between buttons on small screens. Stack project card content vertically for better readability on mobile.
Reorder the layout to the following:
1. Hero
2. About/Timeline
3. Projects
4. Contact
Add section headings with large text and underlines to separate them visually.
Add a clean footer at the bottom of the page with your name, copyright year, and links to LinkedIn and email.


Prompt 10:
Polish the overall design:
- Use consistent padding, font sizes, and spacing across all sections (Hero, About, Projects, Contact).
- Add max-width to all content containers for better layout control.
- Center-align text on mobile screens, left-align on desktop.
- Use text-neutral-300 for secondary/descriptive text, and bold, large headings (text-4xl or text-5xl).
- Ensure good vertical spacing between sections (at least py-16).
- Apply smooth transitions to hover states and clickable elements.
Also add a crazy, eye-catching homepage animation:
- When the Hero section loads, animate the text (name and title) with a 3D zoom-in or typewriter effect using Framer Motion or custom CSS animation.
- Add a subtle animated background (like a gradient swirl, particle animation, or floating shapes) behind the Hero section that doesn't distract from the content.
- Ensure animation works smoothly on both mobile and desktop.


Prompt 11:
change font of my name and above that add animation of hello in 5-6 languages


Prompt 12:
Add asthetic background black and red theme


Prompt 13:
Upload this resume in dowload resume section Resume_APD_2025.pdf


Prompt 14:
- Add a subtle **glowing particle background** (similar to Vanta.js or Three.js)
![image](https://github.com/user-attachments/assets/1a8e0cb5-b52d-4541-b730-6966c0acffd8)



