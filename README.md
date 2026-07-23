# Resume

A professional, ATS-friendly HTML/CSS resume template for Senior Java Backend Developers.

## Overview

This resume is built with semantic HTML and clean CSS to ensure:

- ✅ **ATS-Friendly**: Real text, standard headings, semantic structure
- ✅ **Black & White**: Professional pure B/W color scheme (#000000, #FFFFFF)
- ✅ **Print-Perfect**: Exports to A4 PDF in one page with proper formatting
- ✅ **Version Control**: Can be tracked in Git
- ✅ **Easy to Customize**: Simple HTML and CSS, no frameworks
- ✅ **Clickable Links**: Company names and LinkedIn links are fully functional hyperlinks

## Files

```
resume/
│
├── index.html          # Resume content (main file - edit this)
├── style.css           # Main styling (colors, layout, typography)
├── print.css           # Print/PDF styling (link colors, page breaks)
├── README.md           # This file
└── assets/
    └── profile.jpg     # Optional: your profile photo
```

## How to Use

### 1. Edit Your Content

Open `index.html` and update:

- **Header**: Name, title, email, phone, location, LinkedIn, GitHub
- **Summary**: Professional summary with key technologies and accomplishments
- **Skills**: Organized by category (Languages, Frameworks, Databases, DevOps, etc.)
- **Experience**: Your job roles with quantified achievements and impact metrics
- **Projects**: Key projects with technologies and actual developer contributions
- **Education**: Degree, institution, graduation year

### 2. View in Browser

1. Open `index.html` in your browser (Chrome, Edge, Firefox)
2. You'll see the resume formatted and ready to view

### 3. Export to PDF

**Chrome/Edge (Recommended):**

1. Open `index.html` in Chrome or Edge
2. Press `Ctrl + P` (or File → Print)
3. Set the following options:
   - **Destination**: Save as PDF
   - **Paper size**: A4
   - **Margins**: None / Minimal
   - **Background graphics**: ✓ Enabled (important for B/W text)
   - **Scale**: 100%
4. Click **Save**

**macOS (Safari/Chrome):**

1. Press `Cmd + P`
2. Click "Show Details" (if needed)
3. Set options same as above
4. Click **Save as PDF**

**Firefox:**

1. Press `Ctrl + P`
2. Select "Print to File" or use "Save as PDF"
3. Enable "Background graphics"
4. Set margins to minimal
5. Save as PDF

### 4. Result

A professional, one-page A4 PDF resume with:

- Pure black text for professional appearance
- Clickable company hyperlinks
- Clean B/W formatting
- ATS-optimized structure

## Design Highlights

### Colors

- **Primary Text**: #000000 (Pure Black)
- **Background**: #FFFFFF (Pure White)
- **Borders/Dividers**: #CCCCCC (Light Gray)
- **Professional**: B/W theme for corporate, academic, and ATS compatibility

### Typography

- Font Stack: System fonts (-apple-system, BlinkMacSystemFont, 'Segoe UI', 'Roboto', 'Oxygen', 'Ubuntu', 'Cantarell', 'Source Sans Pro')
- Body text: 13px for optimal readability
- Section titles: 15px (uppercase, bold)
- Name: 33px (bold)
- Professional and clean appearance

### Layout

- Single-column design (ATS-optimal)
- Compact spacing to fit one A4 page
- Page height: 11.5 inches with optimized padding
- Organized sections with dividers
- Skill grid: 3 columns (responsive to 1 column on mobile)
- Achievement bullets: 2-column grid layout
- One A4 page guaranteed

## Tips for Best Results

1. **Keep it concise**: One page only - use action verbs, focus on impact
2. **Tailor for each job**: Update skills and experience for each application
3. **Use keywords**: Include technologies and skills from job descriptions
4. **Verify ATS compatibility**: Test with online ATS checkers
5. **Print settings**: Always use "Background Graphics" enabled in print settings

## Experience Format

Focus on YOUR achievements, not just job duties:

❌ **Wrong**: "Responsible for developing REST APIs"

✅ **Right**: "Developed REST APIs using Spring Boot, handling 1M+ requests daily"

Use action verbs: Designed, Built, Developed, Implemented, Optimized, Led, Mentored

## Skill Organization

Group related skills for better space usage:

```
Languages:        Java 17, SQL
Frameworks:       Spring Boot, JPA, Hibernate
Databases:        PostgreSQL, MySQL
Messaging:        RabbitMQ, Kafka
DevOps:           Docker, Kubernetes, Jenkins
Testing:          JUnit, Selenium, Mockito
```

## Customization

### CSS Variables (style.css)

All colors are defined as CSS variables for easy customization:

```css
:root {
  --primary: #000000; /* Main text color */
  --accent: #000000; /* Accent color */
  --text: #000000; /* Body text */
  --white: #ffffff; /* Background */
  --border-color: #cccccc; /* Dividers */
}
```

### Change Font Size

Modify font sizes in `style.css`:

```css
/* Body text - currently 13px */
body {
  font-size: 13px;
}

/* Section titles - currently 15px */
.section-title {
  font-size: 15px;
}

/* Name - currently 33px */
.name-title h1 {
  font-size: 33px;
}
```

### Adjust Page Height

Modify the page height in `style.css`:

```css
.page {
  height: 11.5in; /* Adjust to fit more content */
}
```

Also update `print.css`:

```css
@page {
  height: 297mm; /* A4 height */
}
```

### Add Profile Photo

1. Place image in `assets/` folder
2. Update HTML to include image in header section with appropriate width/height

## Best Practices

✅ **Do:**

- Use semantic HTML
- Keep one-page format
- Use action verbs and quantifiable metrics
- Focus on impact and measurable results
- Include relevant keywords from job descriptions
- Update regularly with recent accomplishments
- Use hyperlinks for company websites and LinkedIn
- Enable "Background graphics" when printing to PDF
- Test with ATS checkers to verify compatibility

❌ **Don't:**

- Add images or graphics that break ATS parsing
- Use colored backgrounds or complex layouts
- Include personal information (age, photo, marital status)
- Use multiple fonts or inconsistent formatting
- Leave large gaps or wasted space
- Use abbreviations without explaining them first

## Company Links

The resume includes clickable hyperlinks for:

- **Kairos Technologies**: https://kairostech.com/
- **Zyrix AI Labs**: https://zyrix.ai/
- **VM MiningTech Pvt Ltd**: https://vmminingtech.com/
- **Vasantha Tool Crafts Pvt Ltd**: https://www.vasantha.com/
- **LinkedIn**: linkedin.com/in/mohan-bandlapalli-626011168

When printed to PDF, all links remain functional and appear in black for professional appearance.

## Experience Format

Focus on YOUR achievements, not just job duties:

❌ **Wrong**: "Responsible for developing REST APIs"

✅ **Right**: "Developed REST APIs using Spring Boot, handling 10,000+ requests daily with 99.5% uptime"

Use action verbs: Designed, Built, Developed, Implemented, Optimized, Led, Mentored, Architected, Engineered

## Tips for Best Results

1. **Keep it concise**: One page only - use action verbs, focus on impact
2. **Tailor for each job**: Update skills and experience for each application
3. **Use keywords**: Include technologies and skills from job descriptions
4. **Verify ATS compatibility**: Test with online ATS checkers (jobscan.co, etc.)
5. **Print settings**: Always use "Background Graphics" enabled in print settings
6. **PDF export**: Use Chrome or Edge for best PDF quality
7. **Mobile responsive**: Skills section uses 3-column grid (desktop) to 1-column (mobile)

## Version Control

This is a perfect candidate for Git tracking:

```bash
git init
git add .
git commit -m "Initial resume commit"
```

Track changes to your resume over time:

```bash
git log
git diff <commit1> <commit2>
```

## Browser Compatibility

Works in all modern browsers:

- Chrome/Chromium ✓
- Edge ✓
- Firefox ✓
- Safari ✓

## Need Help?

1. Check if your content matches the design
2. Ensure print settings are correct (A4, None margins, Background graphics enabled)
3. Test PDF on different devices
4. Verify ATS compatibility using online tools

---

**Last Updated**: July 2026

Enjoy your professional resume! 🚀
