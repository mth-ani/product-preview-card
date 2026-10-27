Frontend Mentor - Product Preview Card Component

This is my solution to the "Product Preview Card Component challenge" (https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa) on Frontend Mentor.

I built this project to practice creating responsive layouts with HTML and CSS while matching a provided design across mobile and desktop screens.

Table of Contents

- "Overview" (#overview)
  - "The Challenge" (#the-challenge)
  - "Screenshot" (#screenshot)
  - "Links" (#links)
- "My Process" (#my-process)
  - "Built With" (#built-with)
  - "What I Learned" (#what-i-learned)
  - "Continued Development" (#continued-development)
  - "Useful Resources" (#useful-resources)
  - "AI Collaboration" (#ai-collaboration)
- "Author" (#author)

Overview

The Challenge

Users should be able to:

- View an optimal layout depending on their device's screen size.
- See hover and focus states for interactive elements.


My Process

Built With

- Semantic HTML5
- CSS3
- Flexbox
- CSS media queries
- Responsive images using the "<picture>" element
- Mobile-first workflow

What I Learned

This project helped me understand how to create a responsive layout by starting with the mobile design and adapting it for larger screens.

I practiced using Flexbox to position the product image and product information side by side on desktop. I also learned how media queries can change a layout at specific screen widths and how the "<picture>" element allows the browser to select an appropriate image for different devices.

For example, I used this HTML pattern to display different product images depending on the viewport width:

<picture>
  <source
    media="(min-width: 600px)"
    srcset="images/image-product-desktop.jpg"
  >
  <img
    src="images/image-product-mobile.jpg"
    alt="Gabrielle Chanel Essence perfume bottle"
  >
</picture>

This helped me understand how responsive images work without needing separate HTML markup for mobile and desktop.

Continued Development

I want to continue improving my CSS skills, especially responsive layouts, Flexbox, media queries, and accessibility. I also want to become more confident in writing clean CSS independently and testing my projects across different screen sizes.

Useful Resources

- "MDN Web Docs — CSS Flexbox" (https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout) — helped me understand how to arrange elements using Flexbox.
- "MDN Web Docs — CSS Media Queries" (https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries) — useful for building responsive layouts.
- "MDN Web Docs — The "<picture>" element" (https://developer.mozilla.org/en-US/docs/Web/HTML/Element/picture) — explains how to provide different images for different screen conditions.

AI Collaboration

I used ChatGPT as a learning assistant throughout this project. It helped me understand HTML structure, CSS properties, responsive design, and Git workflow.

Rather than relying only on complete solutions, I worked through concepts step by step to understand why certain properties were needed and how they affected the layout.

Author

- GitHub: "@mth-ani" (https://github.com/mth-ani)
- Frontend Mentor: "@mth-ani" (https://www.frontendmentor.io/profile/mth-ani)