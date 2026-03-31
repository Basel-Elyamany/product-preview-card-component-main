# 🛍️ Product Preview Card Component

A responsive product card built using **HTML and CSS**, based on a Frontend Mentor challenge.

LIVE URL: [HERE](https://basel-elyamany.github.io/product-preview-card-component-main/)

---

## 🚀 Features

- 📱 Fully responsive layout
- 🖼️ Responsive product image (mobile & desktop)
- 💰 Pricing section with discount styling
- 🎯 Clean and modern UI
- 🎨 Custom fonts (Montserrat & Fraunces)

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- Flexbox
- Media Queries
- Custom Fonts (`@font-face`)

---

## 🎯 Layout Overview

### 🔹 Product Image
- Displays mobile image by default
- Switches to desktop image on larger screens using:

```css
.product img {
    content: url(images/image-product-desktop.jpg);
}
```

---

### 🔹 Product Info
- Category label (Perfume)
- Product title
- Description text
- Price with:
  - Discount price
  - Strikethrough original price

---

### 🔹 Button
- "Add to Cart" button
- Includes cart icon
- Hover/active state styling

---

## 📱 Responsive Design

### 🔸 Mobile (Default)
- Single column layout
- Vertical stacking

---

### 🔸 Desktop (≥ 800px)
- Two-column layout (image + content)
- Adjusted spacing and font sizes

---

### 🔸 Large Screens (≥ 1900px)
- Increased font sizes
- Wider container for better readability

---

## 🎨 Styling Highlights

- Custom properties (`--spacing`)
- Flexbox for layout alignment
- `@font-face` for local fonts
- Color palette based on HSL
- Button interaction using `:active`
