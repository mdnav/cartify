<div align="center">

# Cartify

**A shopping storefront concept built with HTML, CSS, and JavaScript.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Local Storage](https://img.shields.io/badge/Browser-Local%20Storage-6B7280?style=flat-square)](#)

[Source Code](https://github.com/mdnav/cartify) · [Portfolio](https://portfolio1701.vercel.app/)

</div>

---

## Project Overview

Cartify is a frontend e-commerce storefront concept inspired by familiar online shopping experiences. It brings together a multi-section shopping homepage, category and product imagery, a search filter, and a lightweight cart interaction.

Built with **HTML5, CSS3, and vanilla JavaScript**, the project demonstrates how common storefront interactions can be implemented without a frontend framework or backend service.

## Project Experience

The interface is organized around a shopping-style navigation bar, promotional content, category/product sections, and a footer. Users can filter visible sections through the search field, add items to a demo cart, view cart contents, and return to the top of the page.

## Key Features

- **Storefront layout:** Header, navigation panel, shopping sections, and footer.
- **Product/category browsing:** Image-led sections for home, fashion, gaming, school, and other shopping themes.
- **Live search filtering:** Filters displayed product sections based on their text content.
- **Demo add-to-cart interaction:** Adds selected section items to a cart and increments quantities for repeated selections.
- **Cart persistence:** Stores cart items in browser Local Storage.
- **Cart summary:** Displays the current cart contents through a simple browser alert.
- **Responsive navigation interaction:** Toggles the navigation panel.
- **Back-to-top control:** Scrolls the page to the top.

## Technology Stack

| Technology | Role |
|---|---|
| HTML5 | Storefront structure and content |
| CSS3 | Layout, styling, and responsive presentation |
| JavaScript (ES6) | Search, cart interactions, and navigation behavior |
| Browser Local Storage | Saves demo cart data between page visits |
| Font Awesome | Interface icons |
| Git & GitHub | Version control and source hosting |

## Interaction Flow

```text
Browse Storefront
      |
      +---- Search ----> Filter Visible Sections
      |
      +---- Add Item --> Update Cart Data
      |                       |
      |                       v
      |                 Save to Local Storage
      |
      +---- Open Cart --> Display Cart Summary
      |
      +---- Back to Top -> Scroll to Page Start
```

## Run Locally

```bash
git clone https://github.com/mdnav/cartify.git
cd cartify
```

Open `index.html` in a modern web browser. The project loads Font Awesome from a CDN, so an internet connection is needed for the icon library.

## Project Structure

```text
cartify/
├── index.html       # Storefront markup and content sections
├── style.css        # Layout, styling, and responsive rules
├── app.js           # Search, cart, navigation, and scroll behavior
├── images/          # Product, category, and visual assets
└── README.md        # Project documentation
```

## Scope and Limitations

Cartify is a **frontend demonstration**, not a production commerce platform. The cart is a browser-side demonstration and is not connected to a server or inventory system. The project does not implement user authentication, order processing, checkout, or payment processing. Several storefront links are illustrative interface elements rather than live commerce destinations.

## Engineering Concepts

- DOM selection and event handling
- Filtering content from user input
- Managing arrays of cart items and quantities
- Browser Local Storage and JSON serialization
- Dynamic element creation
- Responsive navigation behavior
- Organizing a multi-section frontend page

## Roadmap

- Dedicated product detail views
- Improved cart interface with item removal and quantity controls
- More complete category filtering and search behavior
- Accessibility and keyboard interaction improvements
- Backend API and database integration
- Authentication, orders, and secure checkout as future full-stack features

## About the Developer

**Mohammad Naveed**  
B.Tech ECE student focused on software development, Java full-stack engineering, and building practical web applications.

- **Portfolio:** [portfolio1701.vercel.app](https://portfolio1701.vercel.app/)
- **GitHub:** [github.com/mdnav](https://github.com/mdnav)
- **LinkedIn:** [linkedin.com/in/mdnav](https://www.linkedin.com/in/mdnav/)

## Contributing

Suggestions and improvements are welcome. Fork the repository, create a feature branch, commit your changes, and open a pull request.

If you find this project useful, consider giving it a ⭐.

<div align="center">

**Designed and developed by Mohammad Naveed**

</div>
