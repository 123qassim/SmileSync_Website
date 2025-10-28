SmileSync - Modern Dental Clinic Website

This project is a complete, production-ready frontend for SmileSync, a modern, responsive website for a dental clinic. It is built using only vanilla HTML5, CSS3, and JavaScript, with a strong focus on performance, SEO, and accessibility.

This implementation is a Single Page Application (SPA), where all "pages," styling, and logic are contained within a single index.html file. JavaScript is used to dynamically show and hide page sections, simulating a multi-page user experience while maintaining the simplicity of a single file.

✨ Key Features

Single Page Application (SPA): All 9 sections (Home, About, Services, Doctors, Testimonials, Gallery, Appointments, Blog, Contact) are dynamically rendered from one index.html file.

Fully Responsive: The layout seamlessly adapts to all screen sizes, from mobile phones to desktops.

Dark/Light Mode: A theme toggle allows users to switch between a light and dark color scheme, with their preference saved (if system preference is available).

SEO Optimized:

Page titles and meta descriptions update dynamically on navigation.

Includes Schema.org (JSON-LD) markup for a "Dentist" local business.

Open Graph and Twitter Card tags for rich social media previews.

Interactive Components:

Testimonial Carousel: A pure JavaScript-powered slider for patient reviews.

Gallery Lightbox: Click on gallery images to open them in a full-screen modal.

Animated Counters: Numbers for stats (like "Happy Patients") animate on scroll.

Scroll Animations: Subtle "fade-in" effects as the user scrolls down the page.

Form Validation: Client-side validation for the Appointment and Contact forms.

Utility UI: Includes a "Scroll to Top" button and floating WhatsApp/Call buttons.

Modern Stack: Built with semantic HTML5, modern CSS (flexbox, grid, custom properties), and vanilla JavaScript (ES6+).

🚀 How to Run

Since this is a self-contained static website, there is no build step required.

Simply open the index.html file in any modern web browser (like Chrome, Firefox, Safari, or Edge) to view and interact with the website.

🔧 Customization

All content, images, and contact information can be edited directly within the index.html file:

Branding & Contact: Update the clinic name, Kenyan address, otahacharles@gmail.com email, and +254746373477 phone number in the HTML body (especially the #contact section and the footer). The Schema.org script in the <head> should also be updated.

Images: All images are loaded via HTTPS links (from Pexels). To change them, simply replace the src="..." URLs in the <img> tags for the hero, services, gallery, and doctors sections.

Services & Doctors: Add, edit, or remove HTML blocks in the #services and #doctors sections to update clinic offerings and staff profiles.

Social & Links: Update the social media links in the footer and the GitHub link in the copyright section.

🌐 Original Inspiration

This project was inspired by the design and structure of the GentleSmiles repository and adapted into a modern, single-file SPA with unique branding and features.
