# Digital Resume Builder

A modern, responsive web application for creating professional resumes with real-time preview and PDF export functionality.

## Screenshots

![image](https://github.com/user-attachments/assets/7f8dcbb8-bdb7-4bfe-8e48-f3313d858821)

![image](https://github.com/user-attachments/assets/169f315f-f195-4598-ba52-6addb1687b67)

![image](https://github.com/user-attachments/assets/6efbd626-55ba-4bda-b8fc-2eb39931bdd5)

![image](https://github.com/user-attachments/assets/521247b6-02d3-4f3e-a350-4002bdc327a0)

![image](https://github.com/user-attachments/assets/e81d7d4e-08e8-4e79-8496-dd1d3caca279)

![image](https://github.com/user-attachments/assets/bf202000-383f-4c6b-a09f-469c0e5a2a2d)

##ATS Score

![image](https://github.com/user-attachments/assets/a19fae1e-027d-4fe6-b41c-fdcb81cbddf6)

## Features

### ✨ Core Features
- *Real-time Preview*: See your resume update instantly as you type
- *Professional Design*: Clean, modern resume template optimized for ATS systems
- *PDF Export*: Download your resume as a professionally formatted PDF
- *Responsive Layout*: Works seamlessly on desktop, tablet, and mobile devices
- *Form Validation*: Ensures all required fields are properly filled

### 📋 Resume Sections
- *Personal Information*: Name, email, phone, address, LinkedIn profile
- *Professional Summary*: Brief overview of your background and objectives
- *Education*: Multiple degrees with institution, year, and GPA
- *Work Experience*: Job titles, companies, duration, and detailed descriptions
- *Skills*: Comma-separated list displayed as professional tags
- *Projects*: Project names, technologies used, descriptions, and URLs

### 🎨 Design Features
- *Modern UI*: Gradient backgrounds and contemporary styling
- *Interactive Elements*: Hover effects and smooth transitions
- *Split Layout*: Form on the left, live preview on the right
- *Print Optimization*: Clean layout when printing or converting to PDF

## Quick Start

### Option 1: Direct Usage
1. Save the HTML file to your computer
2. Open it in any modern web browser
3. Start filling out your information
4. Click "Download Resume as PDF" when ready

### Option 2: Local Development
bash
# Clone or download the file
# No installation required - pure HTML/CSS/JavaScript

# Open in browser
open resume-builder.html
# or
python -m http.server 8000  # For local server


## How to Use

### 1. Fill Personal Information
- Enter your full name (required)
- Add your email address (required)
- Include phone number, address, and LinkedIn profile
- Write a professional summary

### 2. Add Education
- Click "Add Education" to add multiple degrees
- Fill in degree type, institution, graduation year, and GPA
- Use the "Remove" button to delete entries

### 3. Add Work Experience
- Click "Add Experience" for multiple positions
- Include job title, company, duration, and detailed descriptions
- Describe your responsibilities and achievements

### 4. List Skills
- Enter skills separated by commas
- Skills will appear as professional tags in the preview
- Example: "JavaScript, Python, React, Node.js, SQL"

### 5. Add Projects
- Click "Add Project" for multiple projects
- Include project name, technologies used, description, and URL
- Great for showcasing your portfolio

### 6. Download PDF
- Click "Download Resume as PDF" button
- PDF will be automatically generated and downloaded
- Filename includes your name for easy identification

## Technical Details

### Technologies Used
- *HTML5*: Semantic markup and structure
- *CSS3*: Modern styling with gradients, flexbox, and grid
- *JavaScript*: Dynamic form handling and real-time updates
- *jsPDF*: Client-side PDF generation

### Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

### Dependencies
- *jsPDF*: Loaded from CDN for PDF generation
- No other external dependencies required

## Customization

### Styling
The application uses CSS custom properties and can be easily customized:

css
/* Main color scheme */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Button colors */
.add-btn {
    background: linear-gradient(135deg, #667eea, #764ba2);
}

.download-btn {
    background: linear-gradient(135deg, #2ed573, #1e90ff);
}


### Layout
- Responsive grid layout automatically adjusts for mobile devices
- Form and preview sections stack vertically on smaller screens
- Print styles hide the form and show only the resume

## File Structure


resume-builder.html
├── HTML Structure
│   ├── Form Section (left panel)
│   └── Preview Section (right panel)
├── CSS Styles
│   ├── Layout and grid
│   ├── Form styling
│   ├── Preview styling
│   └── Responsive design
└── JavaScript
    ├── Form handling
    ├── Real-time preview updates
    ├── Dynamic section management
    └── PDF generation


## Form Validation

### Required Fields
- Full Name
- Email Address

### Validation Rules
- Email format validation
- Real-time error messages
- Visual feedback with red borders
- Prevents PDF generation if validation fails

## PDF Generation Features

### Layout
- Professional header with centered contact information
- Section titles with underlines
- Proper spacing and typography
- Optimized for ATS systems

### Content Organization
- Contact information at the top
- Professional summary (if provided)
- Education section
- Work experience with detailed descriptions
- Skills section
- Projects section

## Browser Storage

The application does not use any persistent storage - all data is temporary and exists only during the current session. This ensures privacy and prevents data persistence issues.

## Responsive Design

### Desktop (1024px+)
- Side-by-side layout with form and preview
- Full-width sections
- Optimal user experience

### Tablet (768px - 1023px)
- Maintained side-by-side layout
- Adjusted spacing and font sizes
- Touch-friendly interface

### Mobile (< 768px)
- Stacked layout (form above preview)
- Optimized for touch interaction
- Maintained functionality

## Performance

### Optimization Features
- Minimal external dependencies
- Efficient DOM manipulation
- Lightweight CSS and JavaScript
- Fast real-time updates

### Loading
- Single HTML file - no additional requests
- CDN-hosted jsPDF library
- Instant startup time

## Accessibility

### Features
- Semantic HTML structure
- Proper form labels and fieldsets
- Keyboard navigation support
- Screen reader compatible
- High contrast color scheme

## Troubleshooting

### Common Issues

*PDF not downloading:*
- Check if browser blocks pop-ups
- Ensure JavaScript is enabled
- Try a different browser

*Preview not updating:*
- Refresh the page
- Check browser console for errors
- Ensure all required fields are filled

*Mobile display issues:*
- Use landscape orientation for better experience
- Zoom out if content appears cramped
- Try different mobile browsers

## Contributing

To contribute to this project:
1. Fork the repository
2. Make your changes
3. Test across different browsers
4. Submit a pull request

## License

This project is open source and available under the MIT License.

## Support

For issues or questions:
- Check the browser console for error messages
- Ensure you're using a modern browser
- Try clearing browser cache and cookies

---

*Made with ❤ for job seekers worldwide*
