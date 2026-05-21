# BotsNav

Welcome to the **BotsNav** project! 

BotsNav is a comprehensive, digital tourism and lifestyle guide designed to help both locals and international visitors discover the very best of Botswana. Whether you're looking for a luxury hotel, a traditional dining experience, a local sports event, or an authentic craft market, BotsNav brings it all together in one easy-to-use platform.

## What is Inside?

Our platform is divided into several key areas to make navigation simple and intuitive:
* **Sanctuaries (Hotels)**: From architectural marvels to serene wilderness retreats in the Okavango Delta.
* **Gastronomy (Dining)**: A curated list of everything from fine dining to traditional local cuisine.
* **Adventures (Sports)**: Local tournaments, athletic facilities, and outdoor recreation.
* **Artisans & Commerce (Shopping)**: Malls, markets, and boutiques showcasing contemporary Botswana style.

### Key Features
* **Interactive Filtering & Search**: We built a dynamic, JavaScript-powered search and filter system so users can instantly find what they're looking for without the page ever having to reload.
* **Detailed Overlays**: Clicking on any listing opens a beautiful pop-up modal with high-quality local images, pricing, and full descriptions.
* **Fully Responsive**: The site looks and works perfectly on mobile phones, tablets, and large desktop screens.

## How It Is Built

We wanted BotsNav to be lightning fast and accessible, so we stuck to modern web standards without relying on heavy frameworks:
* **HTML5**: Semantic and clean structure for great SEO and accessibility. 
* **CSS3 & Bootstrap 5**: Custom CSS variables for our brand colors, mixed with Bootstrap's powerful grid system to ensure perfect responsive layouts.
* **Vanilla JavaScript**: All the interactivity (modals, filtering, and dynamic content rendering) is handled with pure ES6+ JavaScript.
* **Local Asset Management**: Every image is localized and optimized inside the `dinepe/` folder to guarantee offline capability, fast load times, and absolute brand consistency.

## Project Structure

If you're looking under the hood, here is how the project is organized:

* `/` **(Root)**: The main, fully styled HTML files (`index.html`, `hotels.html`, `about.html`, etc.).
* `/structure`: This folder contains pure, semantic HTML5 skeletons of our pages. We stripped out the CSS and Bootstrap classes here to demonstrate strict structural grading compliance.
* `/css`: Home to our custom `style.css` file.
* `/dinepe`: Our centralized image and branding asset folder.

## Live Website (GitHub Pages)

The BotsNav platform is fully hosted and live on **GitHub Pages**. Because it is built with standard web technologies, there is no need to spin up a server, install dependencies, or run a build process. 

👉 **[Click Here to Visit the Live BotsNav Website](YOUR_GITHUB_PAGES_LINK_HERE)**

*(Alternatively, if exploring the code locally, simply download the repository and double-click on `index.html` to open it in your browser!)*
