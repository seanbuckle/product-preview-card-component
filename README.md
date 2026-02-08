# Product Preview | E-commerce UI Component 🛍️

A high-fidelity, responsive product preview card designed for modern e-commerce environments. This component demonstrates advanced Art Direction techniques, ensuring optimal asset delivery across device types, while maintaining a pixel-perfect aesthetic.

## 📸 Preview

![Professional product preview card featuring a split-screen design with elegant typography and a dark-green CTA button.](./images/Screenshot.png)

## 🚀 Technical Highlights

- **Art Direction:** Utilises the HTML5 `<picture>` element to serve optimised, context-specific images for mobile and desktop viewports.
- **Markup Architecture:** Pure HTML5 using semantic elements for SEO-friendly and accessible content structure.
- **Styling Architecture:** Modular SCSS following the BEM (Block Element Modifier) methodology for component-level encapsulation.
- **Hybrid Layout:** Leverages a combination of CSS Grid for the primary card split and Flexbox for internal content alignment.
- **Responsive Design:** Mobile-first workflow using relative units (`rem`, `em`) to ensure fluid scaling and high-density display support.

## 🏗️ Architectural Overview

### 1. Responsive Art Direction

A key challenge of this component is handling the transition from a vertical mobile layout to a horizontal desktop card:
- **Image Optimisation:** Rather than just resizing a single image, I implemented a strategy to swap assets based on media queries, ensuring the product is always the focal point without unnecessary bandwidth consumption.
- **Aspect Ratio Management:** CSS Grid is utilised to maintain a perfect 50/50 split on desktop, while collapsing into a single-column flow on smaller screens.

### 2. Scalable Style System (BEM + SCSS)

The visual architecture follows your suite's standard for long-term maintainability:
- **Thematic Variables:** Defined SCSS variables for the "Montserrat" and "Fraunces" typography systems, alongside the specialised color palette (Deep Aquamarine and Cream).
- **Encapsulation:** The `.product-card` block is entirely self-contained, allowing for easy integration into a larger marketplace or cart page without style collisions.
- **Interactive Affordance:** Custom-engineered hover and focus states for the "Add to Cart" button provide immediate visual feedback and meet accessibility standards.

### 3. Structural Precision & A11y

- **Semantic Hierarchy:** Uses `<del>` and `<span>` with screen-reader-only labels to clearly communicate "Current Price" vs "Original Price" to assistive technology.
- **Layout Engine:** High-precision spacing managed through a unified scale, ensuring visual balance between text content and product imagery.

## 🛠️ Built With
![SASS](https://img.shields.io/badge/SASS-CC6699?style=for-the-badge&logo=SASS&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white)


## 🔗 Live Implementation

- **Live Site:** [https://product-preview-card-component.seanbuckle.com](https://github.com/seanbuckle/product-preview-card-component)

- **Source Code:** [https://github.com/seanbuckle/product-preview-card-component](https://github.com/seanbuckle/product-preview-card-component)

## 🏁 Installation & Development
To run this project locally:

1. **Clone the repository:**
```bash
git clone https://github.com/seanbuckle/product-preview-card-component.git
```

2. Navigate to the directory:
```bash
cd Product-preview-card-component
```

3. **Open the project:** Simply open `index.html` in your preferred browser.

## 👨‍💻 Author

**Sean Buckle**

[Frontend Mentor Profile](https://www.frontendmentor.io/profile/seanbuckle)

[LinkedIn](https://www.linkedin.com/in/seanbuckle)

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/seanbuckle/product-preview-card-component/blob/main/LICENSE) file for details.

---

****Note: This project was built as a solution to a Frontend Mentor challenge.***
