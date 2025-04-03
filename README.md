# Books-For-My-University

Books4MU is an e-commerce website designed for engineering students, particularly those from My University. It offers a wide range of books with discounts up to 75%, free shipping on orders over $100, secure payments, easy returns, and 24/7 support. The website features a clean and modern design with a responsive layout, built using HTML, CSS, and JavaScript, and integrates the Swiper library for sliders.

## Features

- **Header with Search and Navigation**: Includes a logo, search bar, cart, and user login options.
- **Home Section**: Highlights discounts up to 75% with a book slider showcasing featured titles.
- **Icons Section**: Displays key benefits like free shipping, secure payments, easy returns, and 24/7 support.
- **Featured Books**: A slider showcasing books with prices, discounts, and "Add to Cart" buttons.
- **Newsletter Subscription**: Allows users to subscribe for updates.
- **Categories**: Organized by semesters (1-8) for easy navigation.
- **Deal of the Day**: Promotes time-sensitive offers (e.g., up to 50% off).
- **Client Reviews**: Displays testimonials with star ratings.
- **Feedback Form**: Links to a feedback page for user input.
- **Footer**: Includes quick links, contact info, social media links, and credits.
- **Responsive Design**: Works seamlessly on desktop and mobile devices.

## Technologies Used

- **HTML5**: Structure of the website.
- **CSS3**: Styling (via `styles.css`).
- **JavaScript**: Interactivity (via `script.js`).
- **Swiper.js**: For sliders (version 7, loaded via CDN).
- **Font Awesome**: Icons (version 5.15.4, loaded via CDN).
- **Favicon**: Custom icons for various devices.

## Project Structure

```
Books4MU/
├── favicon_io/               # Favicon files
│   ├── apple-touch-icon.png
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   └── site.webmanifest
├── image/                    # Images for books and other assets
│   ├── book-1.png
│   ├── book-2.png
│   ├── ... (up to book-10.png)
│   ├── deal-img.jpg
│   ├── loader-img.gif
│   ├── pic-1.png
│   ├── ... (up to pic-6.png)
│   ├── stand.png
│   └── worldmap.png
├── main/                     # Additional images directory
│   └── image/
│       └── book-6.png
├── cart.html                 # Shopping cart page (not included in code)
├── feedback.html             # Feedback page (not included in code)
├── index.html                # Main homepage
├── product.html              # Product detail page (not included in code)
├── script.js                 # Custom JavaScript file
├── styles.css                # Custom CSS file
└── README.md                 # This file
```

## Setup Instructions

To run this project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Books4MU.git
   cd Books4MU
   ```

2. **Open the Project**:
   - Open `index.html` in a web browser (e.g., Chrome, Firefox) to view the website.
   - No server is required as this is a static site, but you can use a local server for better testing (see below).

3. **Optional: Use a Local Server**:
   - Install a simple server like `live-server` via npm:
     ```bash
     npm install -g live-server
     live-server
     ```
   - This will open the site in your default browser with live reloading.

4. **Dependencies**:
   - Ensure an internet connection is available, as the project uses CDN links for Swiper.js and Font Awesome.
   - Alternatively, download these libraries and update the paths in `index.html` for offline use.

## Usage

- **Navigation**: Use the top or bottom navbar to explore sections like Home, Featured, Categories, Reviews, and Feedback.
- **Search**: Enter keywords in the search bar to find books (functionality requires JavaScript implementation in `script.js`).
- **Login**: Click the user icon to access the sign-in form (currently static; backend integration needed for functionality).
- **Cart**: Add books to the cart via the "Add to Cart" buttons (links to `cart.html`, which is not provided).
- **Feedback**: Submit feedback via the linked `feedback.html` page (not provided).

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m "Add your message"`).
4. Push to your branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

## Credits

- **Created by**: Anivesh Gupta
- **Copyright**: © 2022 All Rights Reserved

## Contact

For inquiries, reach out to:
- Email: aniveshgupta@gmail.com, deveshgupta@gmail.com
- Phone: 6289028044, 7439529860
- Social Media: [Facebook](https://www.facebook.com/Anivesh.GuptaJi) | [Instagram](https://www.instagram.com/_its_me_aniveshgupta_official) | [LinkedIn](https://www.linkedin.com/in/anivesh-gupta-40897a28a)
