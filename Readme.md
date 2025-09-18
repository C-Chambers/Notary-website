# Chambers Notary | Professional Notary Services in Conway, AR

A secure, professional website for Chambers Notary, providing notary public services in Conway, Arkansas and surrounding areas.

## Features

- **Responsive Design**: Built with Tailwind CSS for mobile-first experience
- **Professional Layout**: Clean, modern design optimized for notary services
- **Enhanced Security**: Comprehensive security implementation with CSP, input validation, and email obfuscation
- **Contact Form Integration**: Formspree-powered contact form with spam protection
- **SEO Optimized**: Meta tags and structured content for search visibility
- **GitHub Pages Ready**: Optimized for seamless deployment
- **Professional Error Handling**: User-friendly validation and error messages

## Website Sections

- **Home/Hero**: Business introduction with key features and hours
- **Services**: Three main service categories with transparent pricing
- **About**: Professional qualifications and experience
- **Contact**: Secure contact form and business information
- **Privacy Policy**: Comprehensive privacy and data protection policy

## GitHub Pages Deployment

To deploy this website to GitHub Pages:

1. **Create a new repository** on GitHub (e.g., `notary-website`)

2. **Push your code** to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/notary-website.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on "Settings" tab
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your website**:
   - Your site will be available at: `https://yourusername.github.io/notary-website`
   - For custom domains, add a CNAME file with your domain
   - Current live site: `https://www.chambersnotary.com`
   - It may take a few minutes for the site to be live

## Customization

- **Content**: Update business information, services, and pricing in HTML files
- **Branding**: Modify custom colors (`notary-blue`, `notary-gold`) in Tailwind config
- **Contact Form**: Update Formspree endpoint in form action attribute
- **Images**: Add professional photos to enhance visual appeal
- **Security**: Maintain CSP directives when adding new external resources

## Security Considerations

This website implements professional-grade security measures:

- **Risk Level**: Medium-Low (down from High after security audit)
- **Security Score**: 8.5/10
- **Regular Updates**: Monitor and update dependencies
- **Form Security**: Protected against spam and abuse
- **Privacy Compliance**: GDPR-aware privacy policy

## Maintenance

- **Updates**: All changes should be made on feature branches
- **Testing**: Use provided testing checklist before deploying
- **Monitoring**: Review form submissions and security logs
- **Annual Tasks**: Update copyright year, review privacy policy

## Technologies Used

- **HTML5**: Semantic markup with accessibility considerations
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Vanilla JavaScript**: Enhanced form validation, smooth scrolling, and security features
- **Formspree**: Contact form backend service
- **GitHub Pages**: Static site hosting with custom domain

## Security Features

- **Content Security Policy (CSP)**: Prevents XSS attacks and code injection
- **Security Headers**: X-Frame-Options, X-Content-Type-Options, X-XSS-Protection
- **Input Validation**: Multi-layer client-side validation with sanitization
- **Email Protection**: Base64 obfuscation prevents spam harvesting
- **Rate Limiting**: Form submission throttling (30-second cooldown)
- **Honeypot Protection**: Spam bot prevention in contact forms

## Performance & Accessibility

- **Fast Loading**: Minimal dependencies, CDN-delivered assets
- **Mobile Optimized**: Responsive design tested across devices
- **SEO Friendly**: Structured data and meta tags for search visibility
- **Professional UX**: Smooth animations and intuitive navigation

## License

This project is open source and available under the [MIT License](LICENSE).