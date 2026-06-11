# Portfolio Website - Rayan Nibir

## PART 1: CONTENT

### 1. What is your full name as you want it displayed professionally?
Rayan Nibir

### 2. What is the purpose of your portfolio website?
To showcase my software development skills, projects, and creative world-building work to potential employers and clients. The site serves as both a professional portfolio and a platform to display my passion for creating fictional worlds with deep lore.

### 3. Who is the target audience (employers, clients, peers, etc.)?
Primary: Employers in software development and technology companies
Secondary: Clients seeking freelance development work
Tertiary: Peers and collaborators interested in both technical skills and creative world-building

### 4. What skills do you want to highlight?
- Python
- JavaScript
- Systems-level Programming
- HTML/CSS
- Socket Programming
- Network Security
- Creative writing and world-building

### 5. What projects or work will you showcase?
- **System Resource Analyzer**: A program that analyzes system resource usage and generates reports on applications and resource consumption
- **Web Task Manager**: A responsive web application for managing daily tasks with modern UI, including GitHub directory links and functional task pages
- **Network Packet Sniffer**: A low-level network monitoring tool that captures and analyzes TCP/IP packets in real-time, with matplotlib usage charts

### 6. How will you describe yourself in a short professional bio?
I am a student completing my computer science degree this summer. I'm passionate about building software and solving problems through code. My academic journey has given me a strong foundation in computer science principles, and I'm eager to apply my skills to real-world projects. Though, my main passion lies in creating fictional worlds with deep lore and very enriched characters.

### 7. What pages will your site include (Home, About, Projects, Contact, etc.)?
- Home (Hero section)
- About Me
- Projects
- Contact
- World (Fantasy world overview)
- Characters (Notable characters from fictional world)
- Locations (Major locations in fictional world)
- Factions (Major factions in fictional world)

### 8. What is your career goal or desired role?
Software Developer with focus on systems programming, network security, or full-stack development. Open to roles that allow both technical problem-solving and creative expression.

### 9. What technologies or tools do you have experience with?
- Python (systems programming, network tools, data visualization)
- JavaScript (web development)
- HTML/CSS (responsive design, theming)
- Systems-level Programming
- Socket Programming
- Network security tools
- Matplotlib (data visualization)

### 10. What achievements or experiences are worth highlighting?
- Completing computer science degree
- Building functional network monitoring tools
- Creating comprehensive fantasy world with detailed lore, characters, and political systems
- Developing responsive web applications with modern UI

### 11. What call-to-action should visitors take (contact you, view projects, download resume)?
Primary: View my projects on GitHub
Secondary: Contact me through the contact form
Tertiary: Connect via LinkedIn or GitHub

### 12. Will you include a resume? In what format?
Not currently included in the website, but can be provided upon request in PDF format.

### 13. What social or professional links will you include (GitHub, LinkedIn, etc.)?
- GitHub: https://github.com/RN730
- LinkedIn: https://www.linkedin.com/in/rayan-nibir-3656b4275

---

## PART 2: DESIGN

### 1. What overall style will best represent you (minimalist, creative, professional, etc.)?
Creative Gothic/Fantasy aesthetic with professional undertones. The design balances a dark, immersive fantasy theme with clean, readable professional content.

### 2. What color scheme will you use and why?
**Dark Mode (Default)**: Black and dark red gradients with gold accents
- Background: #000000 to #2d0a0a gradients
- Text: #e0e0e0 (primary), #c0c0c0 (secondary)
- Accents: Gold gradients (#ffd700 to #daa520) and crimson (#8b0000 to #dc143c)

**Light Mode**: Silver and blue metallic theme
- Background: #f0f0f0 with silver gradients
- Text: #1a1a1a (primary), #333333 (secondary)
- Accents: Steel blue (#4682b4 to #5f9ea0)

The dual theme system allows users to choose between immersive dark mode for the fantasy elements and clean light mode for professional readability.

### 3. What fonts will you use for headings and body text?
- Body text: Segoe UI, Tahoma, Geneva, Verdana (sans-serif)
- Fantasy section headings: Georgia (serif) for more dramatic, ancient feel
- This combination provides readability for professional content while adding character to fantasy sections

### 4. How will your design reflect your personality or field?
The Gothic/fantasy aesthetic reflects my passion for world-building and creative writing, while the clean technical implementation demonstrates software development skills. The dual theme system shows attention to user experience and accessibility.

### 5. What layout will your homepage follow?
Single-page scrolling layout with distinct sections:
- Hero section with centered welcome message
- Grid-based layouts for projects, characters, locations, and factions
- Sticky navigation bar for easy section access
- Responsive design that adapts to different screen sizes

### 6. How will you organize project sections visually?
Projects displayed in a 3-column grid with cards featuring:
- Project title
- Description
- Technology tags
- "View on GitHub" buttons
Hover effects with elevation and border color changes

### 7. Will the site be mobile-friendly? How will you ensure responsiveness?
Yes, fully responsive with:
- CSS Grid and Flexbox layouts
- Media queries for tablet (1024px) and mobile (768px) breakpoints
- Grid columns reduce from 4/3 to 2/1 on smaller screens
- Navigation wraps on mobile
- Images scale appropriately with object-fit: cover

### 8. What visual hierarchy will guide visitors?
- Large hero section with white text for immediate impact
- Gold-colored headings for section identification
- Card-based layouts for content organization
- Progressive disclosure: professional content first, fantasy content second
- Clear visual separation between sections with gold borders

### 9. How will consistency be maintained across pages?
- Consistent color scheme using CSS custom properties (variables)
- Unified card design language across projects, characters, locations, factions
- Reusable CSS classes for buttons, forms, navigation
- Consistent spacing and typography scales
- Theme toggle affects all sections uniformly

### 10. How will accessibility be considered (contrast, font size, readability)?
- High contrast ratios in both dark and light modes
- Minimum font size of 0.85rem for body text
- Clear visual hierarchy with size differences
- Focus states for interactive elements
- Semantic HTML structure
- Light mode option for users who prefer higher contrast

### 11. Will you use icons, images, or illustrations? Why?
- Emoji symbols for faction identifiers (⚔️, 🔮, 🛡️, 🌙, ✨, ☀️)
- Character images with consistent sizing and object-fit
- Location images with borders and hover effects
- World map image for geographical context
- Rune border decorations (✦) for fantasy section headings
Images and icons enhance the immersive fantasy experience while maintaining professional presentation.

### 12. What portfolio websites inspired your design?
- Dark theme inspiration from gaming and fantasy websites
- Card-based layouts from modern portfolio templates
- Dual theme system from accessibility-focused design patterns
- Grid layouts from responsive design best practices

---

## PART 3: INTERACTIVITY

### 1. What interactive elements will your site include (navigation menus, buttons, forms)?
- Sticky navigation bar with smooth scrolling to sections
- Theme toggle button (Light/Dark mode switch)
- "View on GitHub" buttons for projects (open in new tabs)
- Contact form with name, email, and message fields
- Hover effects on cards (elevation, border color changes, transforms)
- Responsive navigation that wraps on smaller screens

### 2. Will your site include a contact form? How will it work?
Yes, a contact form is included with:
- Name input field
- Email input field  
- Message textarea
- Submit button
Currently the form is visual only. To make it functional, Formspree integration is recommended (requires email address to set up form action URL).

### 3. What JavaScript features will you implement?
- Theme toggle functionality (switching between dark and light modes)
- Smooth scrolling for navigation links
- Form submission handling (when backend is integrated)
- Potential future features: Image galleries, modal popups, dynamic content loading

### 4. How will users receive feedback from interactions?
- Hover effects on cards provide visual feedback (elevation, border color)
- Theme toggle button shows current state (☀ Light / 🌙 Dark)
- Button hover states with color changes
- Form validation feedback (when implemented)
- Navigation links highlight current section (potential future enhancement)

### 5. How does interactivity improve the user experience?
- Theme toggle allows users to choose preferred viewing mode (accessibility)
- Smooth scrolling navigation makes section navigation intuitive
- Hover effects provide clear indication of interactive elements
- Card-based layouts with hover states encourage exploration
- Responsive design ensures consistent experience across devices
- Contact form provides direct communication channel

---

## Technical Implementation

### File Structure
```
Project1/
├── index.html          # Main HTML file
├── css/
│   └── style.css      # All styling with theme variables
├── js/
│   └── main.js        # JavaScript for theme toggle and interactions
├── images/
│   ├── background2.png
│   ├── map/
│   │   └── map.png
│   ├── characters/
│   │   ├── my-possession-became-a-ghost-story-this-work-got-the-best-v0-2vauskn36gog1.webp
│   │   ├── alan_palatio.webp
│   │   ├── 3h.webp
│   │   └── YW.webp
│   └── locations/
│       ├── melmoor.png
│       ├── empire.png
│       └── theorcracy.png
└── README.md          # This file
```

### CSS Architecture
- CSS Custom Properties (variables) for theming
- Mobile-first responsive design
- BEM-like naming convention for classes
- Gradient backgrounds for depth
- Consistent spacing and typography scales

### JavaScript Features
- Theme persistence using localStorage
- Event listeners for theme toggle
- Smooth scroll behavior (CSS-based)
- Form submission handling (placeholder)

### Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- CSS Grid and Flexbox support required
- ES6+ JavaScript features

---

## Future Enhancements

### Planned Features
- Formspree integration for contact form
- Image lightbox for character/location images
- Search functionality for characters/locations
- Filter system for projects by technology
- Animated transitions between sections
- Loading animations
- Blog section for technical writing
- Downloadable resume in PDF format

### Potential Additions
- Character relationship diagrams
- Interactive world map
- Timeline of world history
- Faction alliance/relationship visualizer
- Dark mode customization options
- Accessibility improvements (ARIA labels, keyboard navigation)

---

## Contact Information

- **GitHub**: https://github.com/RN730
- **LinkedIn**: https://www.linkedin.com/in/rayan-nibir-3656b4275
- **Email**: [To be added via Formspree integration]

---

## License

This portfolio website and its content are © 2026 Rayan Nibir. All rights reserved.

The fantasy world of Acheronia, its characters, locations, and factions are original creative works.
