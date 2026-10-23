1. Introduction
Discover SL is a front-end tourism website designed to help visitors explore Sierra Leone. It presents destination information, travel guidance, information about the project, and a contact form. The website uses HTML, CSS, JavaScript, and local image assets.
2. Website Pages
⦁	Home (index.html) – Introduces Discover SL and highlights destinations and experiences in Sierra Leone.
⦁	Destinations (destinations.html) – Displays destination cards with images and categories. Visitors can search by text and filter destinations by category.
⦁	Travel Guide (travel-guide.html) – Presents travel-related services and helpful information for people planning a visit.
⦁	About Us (about.html) – Explains the website's mission and vision and showcases Sierra Leone's natural and cultural attractions.
⦁	Contact Us (contact.html) – Shows contact details and provides a form for visitors to enter their name, email address, and message.
3. How the Website Works
3.1 Navigation
The header menu links to the five main pages. Clicking a menu item opens the corresponding HTML file. On smaller screens, the menu button opens and closes the navigation menu.
3.2 Destination Search
1.	Click the search icon in the header.
2.	Enter a destination name or keyword.
3.	Submit the search.
4.	The website opens the Destinations page and passes the search term in the URL.
5.	The Destinations page uses the term to filter the destination cards.
Visitors can also type directly into the destination search field and use category buttons to filter the cards. A message appears when no destinations match the selected search and category.
3.3 Destination Cards
Each destination card includes an image, a location or category description, and a button. The images are loaded from the assets/images/ folder. The card buttons currently lead to the Contact Us page rather than to separate destination-detail pages.
3.4 Contact Form
1.	Open the Contact Us page.
2.	Enter a full name, a valid email address, and a message of at least 10 characters.
3.	Select Send Message.
4.	JavaScript checks the fields and displays an error beside any invalid field.
5.	If all fields are valid, a confirmation message appears and the form resets.
Important: This is a demonstration form. It does not send or store messages on a server; the confirmation only appears in the browser.
4. Technologies Used
⦁	HTML5 – Provides the structure and content of the pages.
⦁	CSS3 – Controls layout, colours, typography, responsive design, cards, buttons, and page styling.
⦁	JavaScript – Controls the mobile navigation, header search, destination search and filtering, and contact-form validation.
⦁	Local assets – The assets/ directory contains the logo, favicon, and destination photographs.
⦁	Google Fonts – The pages request the Poppins font from Google Fonts when an internet connection is available.
5. Project Structure
DiscoverSL-website/
├── index.html
├── destinations.html
├── travel-guide.html
├── about.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── assets/
    ├── logo.png
    ├── favicon.png
    └── images/
        ├── hero.jpg
        ├── about.jpg
        ├── loma-mountain.jpg
        ├── jojoma-beach.jpg
        ├── tacugama.jpg
        ├── bonthe-island.jpg
        ├── tokeh-beach.jpg
        └── south-sierra.jpg
6. How to Run the Website
1.	Download and extract DiscoverSL-website.zip.
2.	Keep the HTML files, css folder, js folder, and assets folder together in the same project directory.
3.	Open index.html in a modern web browser.
4.	Use the navigation menu to visit the other pages and test the search, filters, and contact form.
For a more consistent local development setup, open the extracted project folder in a code editor such as Visual Studio Code and use a local web-server extension. No build step or package installation is required for the current static website.
7. Limitations and Future Improvements
⦁	The website is currently a static front-end project; it has no database or server-side application.
⦁	The contact form does not actually send messages. It would need a backend or a form service to deliver enquiries.
⦁	Destination cards link to the Contact Us page rather than dedicated destination-detail pages.
⦁	Social media links should be connected to the project's real profiles.
⦁	Accommodation, transport, and other travel services are informational sections, not booking systems.
⦁	Destination information, contact details, and images should be reviewed and updated before the website is published.
8. Summary
Discover SL provides a simple way to browse information about Sierra Leone's destinations and travel experiences. Visitors can move between pages, search and filter destination cards, read about the project, and test the contact form. The current version is a static website intended as an informational front-end demonstration.﻿# DCOMP114_IBRAHIM_KAI_BANGURA_905005999
# DCOMP114_IBRAHIM_KAI_BANGURA_905005999
