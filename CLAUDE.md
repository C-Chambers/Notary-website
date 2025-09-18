# Chambers Notary Website - Claude Context

## Project Overview
This is a single-page website for "Chambers Notary," a professional notary public service in Little Rock, Arkansas. The website serves as an online presence for Kaitlyn, who provides notarization services both in-office and mobile.

## Repository Structure
```
/
├── index.html              # Main website (single-page application)
├── privacy-policy.html     # Privacy policy page
├── Readme.md              # Basic readme (minimal content)
├── CNAME                  # GitHub Pages domain: www.chambersnotary.com
├── .gitignore             # Standard gitignore for web projects
└── CLAUDE.md              # This context file
```

## Website Details

### Technology Stack
- **Frontend**: Pure HTML, CSS (Tailwind CDN), minimal JavaScript
- **Styling**: Tailwind CSS v3 (CDN) with custom color theme
- **Hosting**: GitHub Pages (domain: www.chambersnotary.com)
- **No build process**: Static HTML files, no Node.js/npm dependencies

### Custom Brand Colors
- `notary-blue`: #1e40af (primary brand color)
- `notary-gold`: #f59e0b (accent color)

### Business Information
- **Business Name**: Chambers Notary
- **Notary**: Kaitlyn
- **Location**: Little Rock, Arkansas
- **Services**: Document notarization, identity verification, mobile notary
- **Hours**: Mon-Fri 8 AM - 8 PM, Weekends by appointment
- **Pricing**: $10/signature, $25 mobile service fee

### Contact Information (Currently Placeholder)
- **Phone**: (555) 555-5555
- **Email**: [Not provided in current version]
- **Service Area**: Little Rock & surrounding areas

## Website Structure (index.html)

### Sections
1. **Header/Navigation**: Sticky navigation with business name and section links
2. **Home/Hero**: Introduction, business hours, key features (Fast & Reliable, Mobile Service, Licensed & Bonded)
3. **Services**: Three main service categories with pricing
4. **About**: Personal introduction for Kaitlyn with qualifications
5. **Contact**: Contact form and business information
6. **Footer**: Business summary, quick links, contact info

### Features
- Responsive design (mobile-friendly)
- Smooth scrolling between sections
- Contact form (non-functional - frontend only)
- Professional business presentation
- SEO optimized with meta tags

## Privacy Policy
- Standalone page (privacy-policy.html)
- Compliant with notary record-keeping requirements
- Covers data collection, usage, security, and user rights
- Links back to main website

## Development Notes

### No Build Process
- Uses Tailwind CSS via CDN (not compiled)
- No package.json or Node.js dependencies
- Pure static HTML/CSS/JS files
- Suitable for GitHub Pages hosting

### Form Functionality
- Contact form is frontend-only (no backend processing)
- Form fields: name, email, phone, service type, message
- Would need backend integration for actual functionality

### Missing Elements
- Actual email address (placeholder in contact info)
- Real business photo (placeholder in About section)
- Working contact form submission
- Analytics/tracking (currently none)

## Recent Changes (Git History)
- Updated business hours to Mon-Fri 8 AM - 8 PM, weekends by appointment
- Added weekend appointment details
- Privacy policy updates
- Various content refinements

## Potential Improvements
1. Add real contact email address
2. Implement contact form backend (or use service like Formspree)
3. Add actual business photos
4. Consider adding testimonials section
5. Add Google Analytics if desired
6. Add schema markup for local SEO
7. Consider adding online appointment booking

## Maintenance Notes
- Website is completely static - any updates require direct file editing
- Domain managed through GitHub Pages CNAME file
- No automated deployments or CI/CD - direct push to main branch deploys
- Monitor contact form submissions if backend is added
- Update copyright year annually
- Review and update privacy policy as needed

## Testing Checklist
When making changes:
- [ ] Test responsive design on mobile devices
- [ ] Verify all navigation links work
- [ ] Check smooth scrolling functionality
- [ ] Validate HTML/CSS
- [ ] Test contact form fields (even if non-functional)
- [ ] Verify privacy policy links work
- [ ] Check business hours display correctly
- [ ] Ensure all placeholder content is appropriate