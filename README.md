# Elorm's Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Features smooth animations, mobile-responsive design, and a professional layout.

## 🚀 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: AOS (Animate On Scroll) library integration for engaging animations
- **Typewriter Effect**: Dynamic text animation showcasing different roles
- **Modern UI**: Clean, professional design with gradient background
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Social Media Integration**: Links to GitHub, Facebook, LinkedIn, and Twitter
- **Download CV**: Call-to-action button for resume download

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # CSS styles and animations
├── jj.png             # Profile image
└── README.md          # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: 
  - Flexbox for layout
  - CSS Grid for responsive design
  - Custom animations and transitions
  - Media queries for mobile responsiveness
- **JavaScript**: 
  - DOM manipulation
  - Mobile navigation functionality
- **External Libraries**:
  - Font Awesome (Icons)
  - AOS (Animate On Scroll)
  - Google Fonts (Poppins)

## 🎨 Design Features

### Color Scheme
- Primary: `rgb(109,67,0)` (Brown)
- Background: Linear gradient from white to peach
- Text: Black with brown accents

### Typography
- Font Family: Poppins (Google Fonts)
- Responsive font sizing using `clamp()`

### Animations
- Zoom-in effects on logo and image
- Fade animations for navigation links
- Typewriter effect for role descriptions
- Hover effects on buttons and social links

## 📱 Responsive Breakpoints

- **Desktop**: Full layout with side-by-side content
- **Mobile/Tablet** (`max-width: 884px`):
  - Stacked layout
  - Hamburger menu navigation
  - Adjusted font sizes and spacing

## 🚀 Getting Started

1. **Clone or Download** the project files
2. **Open** `index.html` in your web browser
3. **Customize** the content:
   - Replace `jj.png` with your profile image
   - Update personal information in the HTML
   - Modify colors in `style.css`
   - Add your social media links

## 📝 Customization

### Personal Information
Edit the following in `index.html`:
- Name: Update "Elorm" to your name
- Profile image: Replace `jj.png` with your photo
- Description: Update the Lorem ipsum text
- Social media links: Add your actual URLs

### Styling
Modify `style.css` to change:
- Colors: Update the brown `rgb(109,67,0)` values
- Fonts: Change the Google Fonts import
- Animations: Adjust AOS settings and CSS transitions

### Typewriter Effect
The typewriter animation cycles through:
- "Developer"
- "Designer" 
- "Student"

Edit the `@keyframes words` in `style.css` to customize these roles.

## 🌟 Key Features Explained

### Mobile Navigation
The hamburger menu (`hamburg()`) and close function (`cancel()`) handle mobile navigation with smooth transitions.

### AOS Animations
- `data-aos="zoom-in"`: Logo animation
- `data-aos="fade-up"`: Navigation links
- `data-aos="zoom-in-right"`: Profile image
- `data-aos="fade-left/right"`: Content sections

### CSS Custom Properties
The design uses consistent color values and responsive units for maintainability.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements.

## 📞 Contact

For questions or suggestions, please open an issue on the repository.

---

**Built with ❤️ by Elorm** 