# Aian's Personal Website

## Project Description
This is a personal portfolio website for Ian Isaac Terrenal, a second-year Information Technology student and aspiring game designer. The portfolio showcases my skills, certifications, projects, and educational background, targeting recruiters, peers, and potential collaborators. Built with modern web technologies, it features a responsive design, a dynamic green gradient background, and glass-like section styling for a polished, professional look.

## Features
- **About Section**: Introduces my background as an IT student and passion for game design, particularly for Roblox.
- **Certifications Section**: Lists certifications (IT Specialist in Java, IC3 Digital Literacy GS6 Level 1) with verifiable links.
- **Hobbies & Projects Section**: Showcases Roblox games (The Outlets at Roblox, Taal: The Expedition) and school projects (Guidance Office App, Health First App).
- **Proficiencies Section**: Displays proficiency levels in programming languages (e.g., Lua: 85%, C++: 70%) and tools (e.g., Roblox Studio: 90%) with progress bars.
- **Contact Section**: Includes a form (Name, Email, Message) with client-side validation, logging submissions to the console, and displaying a confirmation alert.
- **Dynamic Background**: Features an animated green gradient (`#4ade80`-based) that shifts smoothly over 15 seconds.
- **Glass-Like Design**: Sections use a frosted glass effect with `backdrop-filter: blur(10px)`, semi-transparency, and subtle white borders/shadows.
- **Responsive Design**: Adapts seamlessly to desktop, tablet, mobile, and extra-small screens.
- **Interactive Navigation**: Sticky sidebar on desktop and hamburger menu on mobile for easy section access.

## Technologies Used
- **HTML5**: For semantic structure.
- **CSS3**: For custom styling, including the animated gradient and glass effect.
- **JavaScript**: For interactive features (hamburger menu, contact form submission).
- **Bootstrap 5.3**: For responsive layout and components (via CDN).
- **Font Awesome 6.0**: For icons in certifications, proficiencies, and navigation (via CDN).
- **Poppins Font**: For consistent typography (via Google Fonts).

## Project Structure
```
portfolio/
├── index.html          # Main portfolio page
├── style.css           # Custom CSS styles
└── Images/
    ├── aian.jpg        # Profile picture
    └── Projects/
        ├── outlets.png        # The Outlets at Roblox screenshot
        ├── taal.png           # Taal: The Expedition screenshot
        ├── gso-app.png        # Guidance Office App screenshot
        └── health-first.png   # Health First App screenshot
```

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/iizac21/portfolio.git
   cd portfolio
   ```
2. **Serve Locally**:
   - Option 1: Use a local server (recommended):
     ```bash
     python -m http.server 8000
     ```
     Open `http://localhost:8000` in your browser.
   - Option 2: Open `index.html` directly in a browser (note: some features may not work due to file protocol restrictions).
3. **Ensure Dependencies**:
   - No installation is required, as Bootstrap, Font Awesome, and Poppins are loaded via CDNs.
4. **Verify Images**:
   - Ensure the `Images/` folder contains `aian.jpg` and `Projects/` subfolder with all project screenshots.
5. **Update Placeholder**:
   - Replace `[Your High School]` in `index.html` (Education section) with your actual high school name.

## Usage
- **Navigation**:
  - On desktop, use the sticky sidebar to jump to sections (About, Certifications, etc.).
  - On mobile, tap the hamburger menu (top-left) to access navigation.
- **Contact Form**:
  - Fill in Name, Email, and Message fields.
  - Click "Send Message" to submit.
  - The form validates inputs (all fields required), logs data to the browser console, and shows a "Message sent!" alert.
  - For server-side integration, refer to an API service (e.g., https://x.ai/api).
- **Explore Projects**:
  - Click "Play Now" links in the Hobbies & Projects section to visit Roblox games.
  - Note: School projects are descriptive only (no live links).

## Screenshots
Screenshots of the portfolio and projects are located in the `Images/` folder. Refer to `Images/aian.jpg` for the profile picture and `Images/Projects/` for project visuals.

## Contributing
This is a personal portfolio, but feedback and suggestions are welcome! Please contact me via GitHub (see Contact section) to discuss potential contributions or improvements.

## License
© 2025 Ian Isaac Terrenal. All rights reserved.

## Contact
- **GitHub**: [iizac21](https://github.com/iizac21)
- **Twitter**: [@iizac21](https://twitter.com/iizac21)
- **LinkedIn**: [iizac21](https://linkedin.com/in/iizac21)
- **Portfolio Contact Form**: Use the Contact section to send a message.

Thank you for visiting my portfolio!
