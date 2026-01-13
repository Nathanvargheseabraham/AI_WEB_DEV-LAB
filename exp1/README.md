
# AI
lab exp2

Event Registration & Promotional Portal
Project Overview
This project is a simple HTML5-based Event Registration and Promotional Portal designed for showcasing an event and collecting participant registrations. It demonstrates the use of media elements, form inputs, and basic validation aligned with common web application test cases.

Event Name: Tech-Innovate 2025
Purpose: Promote an event and allow users to register online

Features
HTML5-compliant structure
Responsive layout using viewport meta tag
Promotional media support (Image, Video, Audio)
User-friendly registration form
Client-side input validation
File upload support
**Enhanced layout and alignment using CSS3 Flexbox and an external stylesheet**

Technologies Used
HTML5
**CSS3 (external stylesheet for styling, Flexbox for alignment)**
HTML5 Media Elements (Image, Video, Audio)

Page Structure
Header – Event title and tagline
Promotion Section
Event banner image with alternate text
Promotional video with controls
Audio introduction (centered using CSS `margin: auto`)
Registration Section
User input form with validation
Footer – Copyright information
**Main content is wrapped in a `.container` `div` and centered using CSS Flexbox on the `body` element.**

Test Case Mapping
TC01: Page Structure & Load
Uses `<!DOCTYPE html>` for HTML5 compliance
Page loads correctly in modern browsers
TC02: Image Media
Banner image displayed using `<img>`
`alt` attribute included for accessibility
TC03: Video Media
Promotional video embedded using `<video>`
Supports playback controls and fallback text
TC04: Audio Media
Audio introduction included using `<audio>`
Playback controls enabled and element is centered
TC05 & TC06: Basic Inputs & Validation
Text, email, and date inputs
Required field validation using HTML5 attributes
TC07: Selection Inputs
Radio buttons for attendee type
Dropdown selection for workshop choice
TC08: Textarea & File Upload
Textarea for participant motivation
File upload for ID proof (PDF/Image)
TC09: Form Submission
Submit button provided for registration

For further details on the CSS implementation, refer to the project's `style.css` file and the **HTML structure** in `main.html`.
