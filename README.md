# Music Shop Website

A responsive website for a music instrument shop featuring an interactive greeting system, product showcase, and dynamic content. The website includes a day/night greeting system and personalized color preferences for users.

## Features

### 1. Interactive User Experience
- Personalized greeting based on time of day
- Custom background color selection
- User name prompt on site load

### 2. Navigation
- Responsive header with logo
- Navigation menu with links to:
  - Home
  - About us
  - Products
  - Contact us

### 3. Content Sections
- **Image Slider**
  - Automatic slideshow featuring 3 banner images
  - 18-second animation cycle
  - Smooth transitions

- **USP Section**
  - Four key selling points with icons
  - Responsive grid layout
  - Features: Wide Range of Products, Multiple Stores, Happy Customers, Satisfaction Guaranteed

- **Product Showcase**
  - Three featured products
  - Product images with descriptions
  - Includes Acoustic Guitar, Drums, and Violin

- **Footer**
  - Contact information
  - Embedded YouTube video
  - Responsive two-column layout

## Technical Details

### CSS Features
- Custom font family (Copperplate)
- Responsive design with max-width container
- Float-based layouts
- Custom animations for slider
- Color scheme:
  - Background: azure
  - Header: papayawhip
  - Greeting section: #48C9B0
  - Text: darkslategrey

### JavaScript Functionality
```javascript
- User greeting system based on time:
  - Morning: before 12:00
  - Afternoon: 12:00 - 16:00
  - Evening: 16:00 - 23:00
- Interactive prompts for:
  - User name
  - Favorite color (sets page background)
```

## Customization

### To modify the greeting times:
```javascript
if (hour < 12) {
    // Morning greeting
} else if (hour > 12 && hour < 16) {
    // Afternoon greeting
} else if (hour > 16 && hour < 23) {
    // Evening greeting
}
```

### To change the color scheme:
```css
body {
    background-color: azure;
}
header {
    background-color: papayawhip;
}
.greet {
    background-color: #48C9B0;
}
```

## Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design works on mobile devices

## Connect With Me 🌐

- 💼 LinkedIn: [Aaditya Punatar](https://www.linkedin.com/in/aaditya-punatar/)
- 🐱 GitHub: [@aadi0202](https://github.com/aadi0202)
- 📧 Email: aadipunatar@gmail.com
- 🌐 Website: [aadityapunatar.me](https://aadityapunatar.me)

## License
This project is available for free use and modification.
