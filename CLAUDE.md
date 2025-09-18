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

### Contact Information
- **Email**: contact@chambersnotary.com
- **Service Area**: Conway & surrounding areas

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
- Contact form integrated with Formspree (https://formspree.io/f/mjkeqzvw)
- Form fields: name, email, phone, service type, message with honeypot spam protection
- Enhanced client-side validation with input sanitization
- Rate limiting (30-second cooldown between submissions)
- Professional error handling with user-friendly messages

### Security Features (Implemented 2025)
- **Content Security Policy (CSP)**: Comprehensive XSS protection
- **Security Headers**: X-Frame-Options, X-Content-Type-Options, X-XSS-Protection, Referrer-Policy
- **Input Validation**: Multi-layer form sanitization and validation
- **Email Obfuscation**: Base64 encoding to prevent spam harvesting
- **Rate Limiting**: Client-side form submission throttling
- **Professional Error Handling**: User-friendly error messages with auto-dismiss

### Missing Elements
- Real business photo (placeholder in About section)
- Analytics/tracking (currently none)
- Subresource Integrity (SRI) for Tailwind CDN (optional enhancement)

## Recent Changes (Git History)
### Security Audit and Improvements (January 2025)
- Comprehensive security audit conducted with specialized security agent
- Implemented Content Security Policy (CSP) across all pages
- Added complete security header suite (X-Frame-Options, X-Content-Type-Options, etc.)
- Enhanced form validation with input sanitization and rate limiting
- Implemented email address obfuscation using Base64 encoding
- Added professional error handling system
- Security risk level reduced from High to Medium-Low (75% improvement)
- Security score improved from 3/10 to 8.5/10

### Previous Updates
- Updated business hours to Mon-Fri 8 AM - 8 PM, weekends by appointment
- Added weekend appointment details
- Privacy policy updates
- Various content refinements
- Integrated Formspree contact form functionality

## Potential Improvements
1. Add actual business photos
2. Consider adding testimonials section
3. Add Google Analytics if desired
4. Add schema markup for local SEO
5. Consider adding online appointment booking
6. Implement Subresource Integrity (SRI) for Tailwind CDN
7. Add CSP reporting for enhanced security monitoring
8. Consider server-side rate limiting (when moving away from Formspree)

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
- [ ] Test contact form functionality and validation
- [ ] Test email obfuscation (click-to-reveal functionality)
- [ ] Verify form rate limiting works (30-second cooldown)
- [ ] Test error message display and auto-dismiss
- [ ] Verify security headers are present
- [ ] Check CSP compliance (no console errors)
- [ ] Verify privacy policy links work
- [ ] Check business hours display correctly
- [ ] Ensure all placeholder content is appropriate
- [ ] Test form submission to Formspree
- [ ] Verify honeypot spam protection

## Development Workflow
- When creating new features or modifying existing ones, always do so on a new branch
- Commit and push changes, but do not merge without approval
- Run security testing after any significant changes
- Monitor form submissions and security logs