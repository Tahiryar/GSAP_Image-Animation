# GSAP_Image-Animation
# GSAP Image Animation Example

This project demonstrates a simple web animation using GSAP (GreenSock Animation Platform). The animation triggers when the user moves their mouse over a central red div element.

## Overview

When the mouse moves over the central red div (`#center`), a new image element (`.imagediv`) is created at the mouse position. The image slides into view from the bottom and then slides back out, creating a visually appealing effect.

## Features

- **Central Red Div**: A fixed-size red div is centered in the viewport.
- **Image Animation**: Images appear and slide up from below the mouse position when hovered.
- **Throttle Function**: Limits the rate of event handling to improve performance.

## Technologies Used

- **HTML**: For the structure of the web page.
- **CSS**: For styling the divs and positioning the elements.
- **JavaScript**: For handling mouse events and animating the images.
- **GSAP**: For smooth and performant animations.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/your-repository-name.git
    cd your-repository-name
    ```

2. **Open the `index.html` file**:
    Simply open the `index.html` file in your web browser to view the animation.

## Usage

1. **Run Locally**:
    Open the `index.html` file in any web browser. Move your mouse over the central red div to see the animation effect.

2. **Customizing the Animation**:
    - You can adjust the CSS in the `<style>` tag to change the size, position, or appearance of the div and images.
    - Modify the GSAP animation parameters in the `<script>` tag to tweak the animation duration, easing, or other properties.

## Code Explanation

### HTML

- **`#center`**: A div that acts as the central container for triggering the animation.
- **`.imagediv`**: A dynamically created div that contains the image and handles its animation.

### CSS

- **General Styles**: Ensures the red div is centered and sets up basic styling.
- **`.imagediv` and `img`**: Styles the image container and image for animation.

### JavaScript

- **Throttling**: The `throttleFunction` function limits the rate at which mousemove events are processed.
- **Event Listener**: Creates and animates an image when the mouse moves over the `#center` div.

## Contributing

Feel free to fork the repository and submit pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, you can reach me at [your.email@example.com](mailto:your.email@example.com).

