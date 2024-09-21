# Fruits Website

This project is a simple static website that showcases various fruits with a focus on fresh, healthy eating. It includes an interactive section where users can switch between different fruits and dynamically change the background color.

## Features

- **Interactive Fruit Display**: Users can click on thumbnails of different fruits to change the main fruit image and the background color.
- **Responsive Design**: The layout adjusts to different screen sizes.
- **Social Media Links**: Links to social media pages such as Facebook, Instagram, and Twitter.
- **Smooth UI Transitions**: Using JavaScript, the website provides a smooth transition between fruit images and background colors.

## Technologies Used

- **HTML5**: Structure of the website.
- **CSS3**: Styling for layout, fonts, colors, and responsive design.
- **JavaScript**: For image switching and background color change.
- **Images**: PNG images used for fruits and social media icons.

## Folder Structure

```
Fruits-Website/
├── img/
│   ├── apple.png
│   ├── mango.png
│   ├── watermelon.png
│   ├── dragonFruits.png
│   ├── pineApple.png
│   ├── facebook.png
│   ├── instagram.png
│   └── twitter.png
├── style.css            # Styles for the website
├── script.js            # JavaScript for interactive functionality
├── index.html           # Main HTML file for the project
└── README.md            # Project documentation
```

## How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/fruits-website.git
   ```

2. **Open `index.html`**:
   Navigate to the project folder and open the `index.html` file in a web browser to view the website.

## JavaScript Functionality

- **Image Slider**: Clicking on the fruit thumbnails changes the main fruit image.
- **Background Color Change**: The background color of the website changes dynamically based on the selected fruit.

```javascript
function imgSlider(imgSrc) {
  document.querySelector('.fruits').src = imgSrc;
}

function changeBgcolor(color) {
  document.querySelector('.bg').style.background = color;
}
```

## Future Improvements

- **Backend Integration**: Implement backend functionality for storing fruit-related data or allowing users to place orders.
- **Additional Pages**: Expand the website to include pages for "Menu", "What's New", and "Contact".
- **Animations**: Add more interactive animations to make the website more engaging.

## License

This project is licensed under the MIT License.
