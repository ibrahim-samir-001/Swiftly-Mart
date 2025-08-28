## Swiftly-Mart

A simple e-commerce web app demo using HTML, CSS, and JavaScript.

### Technology Stack
- **HTML5, CSS3, JavaScript (Vanilla):** Core web technologies for structure, styling, and interactivity without frameworks.
- **Bootstrap:** Used for building a responsive and mobile-friendly UI layout.
- **Google Fonts:** Provides custom web fonts for improved typography and design consistency.
- **Font Awesome:** Supplies scalable vector icons for UI elements and buttons.
- **No JavaScript frameworks or build tools:** The project is kept lightweight and simple, using only native browser features.

### Project Structure
```
├── index.html                # Main entry point
├── README.md                 # Project documentation
├── pages/                    # HTML pages
│   ├── cart.html
│   ├── home.html
│   ├── product-info.html
│   ├── register.html
│   └── thank-you.html
├── scripts/                  # JavaScript utilities and logic
│   ├── auth-utilities.js
│   ├── auth.js
│   ├── cart-utilities.js
│   ├── cart.js
│   ├── global-utility.js
│   ├── home-utilities.js
│   ├── home.js
│   ├── product-utilities.js
│   └── product.js
├── styles/                   # CSS files
│   ├── auth-pages.css
│   ├── cart.css
│   ├── font.css
│   ├── home.css
│   ├── modal.css
│   └── product-info.css
└── images/                   # Static assets
```

### Products API
- Uses [Fake Store API](https://fakestoreapi.com/products) to fetch product data
- Example usage:
	```js
	fetch('https://fakestoreapi.com/products')
		.then(res => res.json())
		.then(products => {
			// Use products array
		});
	```
- Product data includes: id, title, price, description, category, image, rating

---
For demo purposes only. No real transactions.
  
---
**Designed by:** Ibrahim Samir Jibril  
**Email:** ibrahimjibril2000@gmail.com  
**Lab Num:** 07

