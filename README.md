# medicalwebsite

Overall Purpose
This is a responsive single-page health care website for a center called HealthHive, designed to introduce users to their services, allow online appointment booking, and provide contact details.

🖼️ Header Section
html
Copy
Edit
<header>
  <h1>HEALTH HIVE CENTER</h1>
  <nav>...</nav>
</header>
Displays the site title ("Health Hive Center").

Includes a navigation bar with smooth-scrolling links to each section of the page.

Has a background image (pic.jpg) and changes color on hover for interactivity.

🏠 Home Section
html
Copy
Edit
<section id="home">...</section>
Welcomes visitors.

Brief description of what HealthHive offers: digital healthcare, expert care, and telehealth services.

Background image: home.jpg.

🧾 About Section
html
Copy
Edit
<section id="about">...</section>
Explains the mission, team, services, and commitment of HealthHive.

Describes:

Who they are (healthcare professionals).

What they offer (services, telemedicine, wellness advice).

Their commitment to personalized care.

Background image: about.jpg.

💼 Services Section
html
Copy
Edit
<section id="services">...</section>
Displays individual services in styled service boxes with hover effects and icons/images.

Services include:

Consulting

Hospitals

Nurse & Home Nursing

Medicine

Ayurvedic

Psychiatry

Each has an image (e.g., checkup.png, consultation.png).

📅 Bookings Section
html
Copy
Edit
<section id="bookings">...</section>
Includes a form to let users book an appointment.

Fields: Name, Email, Date, Time, Optional Message.

On submit, it prevents page reload and shows an alert: “Your appointment has been booked!”

Background image: bookings.jpg.

☎️ Contact Section
html
Copy
Edit
<section id="contact">...</section>
Provides contact info:

Email: healthhive@gmail.com

Phone: +1234567890

Background image: contact.jpg.

Styled with white text and blue background.

🖥️ Styling (CSS)
All styles are written in a <style> tag inside <head>.

Responsive, clean layout using Flexbox and transitions.

Smooth scroll behavior.

Fade-in effect for each section as it scrolls into view (.visible class added with JS).

Buttons and links have hover effects for a modern, interactive feel.

🔧 JavaScript Features
js
Copy
Edit
document.getElementById("booking-form").addEventListener("submit", ...);
Handles form submission for booking: shows a confirmation alert.

js
Copy
Edit
document.addEventListener("scroll", ...);
Adds a class (.visible) to each section as it scrolls into the viewport for a fade-in animation.
