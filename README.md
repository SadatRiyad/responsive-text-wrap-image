# Responsive Text Wrap Around Image

This project demonstrates how to create a **responsive layout** where text wraps around an image using **HTML** and **CSS**. It showcases a classic design pattern, perfect for blogs, articles, or profile pages.

## Live Demo

View the live project here: [Responsive Text Wrap Around Image](https://sadatriyad.github.io/responsive-text-wrap-image/)

## Features

- **Text Wrapping:** The image is floated to the right, and the text flows around it.
- **Responsive Design:** 
  - On smaller screens, the image is centered above the text for better readability.
  - Uses media queries to adapt to different screen sizes.
- **Clean and Modern Styling:**
  - Includes rounded corners, shadow effects, and justified text for a professional look.
- **Reusable Layout:** Ideal for blogs, "about us" pages, or articles.

## Screenshot

Here’s an example of the project:

![Responsive Text Wrap Example](./Opera%20Snapshot_2025-01-01_031110_sadatriyad.github.io.png)

## Technologies Used

- **HTML**
- **CSS**
  - Float for layout positioning.
  - Media queries for responsive design.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/sadatriyad/responsive-text-wrap-image.git
   ```

2. Navigate to the project folder:
   ```bash
   cd responsive-text-wrap-image
   ```

3. Open `index.html` in your browser to view the project.

## Code Highlights

### Image Float
The image is floated to the right to allow text wrapping:
```css
.content img {
    float: right;
    margin: 0 0 20px 20px;
}
```

### Responsive Adjustments
Media queries ensure the layout works on smaller screens:
```css
@media (max-width: 768px) {
    .content img {
        float: none;
        display: block;
        margin: 20px auto;
    }
}
```

## Use Cases

This project is perfect for:
- Blog posts
- Articles
- Profile pages
- Documentation

## Author

**Sadat Riyad**  
- [GitHub](https://github.com/sadatriyad)  
- [Live Demo](https://sadatriyad.github.io/responsive-text-wrap-image/)

## License

This project is open-source and available under the [MIT License](LICENSE).
