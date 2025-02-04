# Will You Be Mine?

A playful, personalized web page that asks, "Will You Be Mine?" featuring interactive animations, random GIFs, and a runaway "No" button. The page dynamically uses a URL parameter to address a custom name, making it perfect for personal messages.

## Features

- **Personalized Question:**\
  The question is personalized with a dynamic name. For example, accessing the page as `index.html?name=Lilly` will display "Lilly, will you make my heart complete?" If no name is provided, it defaults to "Emily".

- **Interactive Animations:**\
  Enjoy smooth animations including a heartbeat effect on GIFs and confetti bursts when a positive response is selected.

- **Runaway "No" Button:**\
  The "No" button evades the user's cursor by moving to random locations within the viewport on hover, making it nearly impossible to click.

- **Random GIFs:**\
  The page randomly selects GIFs for both the main card and the success screen from a predefined list, so the experience can vary each time you load the page.

- **Built with Tailwind CSS:**\
  The styling is handled by Tailwind CSS, providing a responsive and modern design without the hassle of writing extensive custom CSS.

## Demo



> Screenshot_2025-02-03-21-44-15-336_org.telegram.messenger.jpg

## How to Run

1. **Clone or Download the Repository:**

   ```bash
   git clone https://github.com/your-username/will-you-be-mine.git
   cd will-you-be-mine
   ```

2. **Open the HTML File:**\
   Simply open `index.html` in your favorite web browser. No additional build steps are required.

3. **Personalize the Message:**\
   Add a `name` parameter to the URL to change the recipient’s name. For example:

   ```
   index.html?name=Lilly
   ```

   If no name is provided, the default "Emily" will be used.

4. **Enjoy the Experience:**\
   Hover over the "No" button to see it jump around and click "Yes" to reveal the celebratory success screen!

## Project Structure

```
will-you-be-mine/
├── index.html       # Main HTML file with inline CSS and JavaScript
├── README.md        # This file
└── screenshot.png   # (Optional) Screenshot of the project
```

## Technologies Used

- **HTML5**: For the basic page structure.
- **JavaScript**: For dynamic behavior, animations, and handling URL parameters.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Google Fonts**: Uses the [Montserrat](https://fonts.google.com/specimen/Montserrat) font for typography.

## Customization

- **Dynamic Name:**\
  The recipient's name is set dynamically via a URL parameter (`name`). You can modify the default value or extend the logic by editing the JavaScript function `getNameFromURL()` in `index.html`.

- **GIFs:**\
  Update the `gifLinks` and `gifLinks2` arrays in the JavaScript to change the GIFs displayed on the page.

- **Animations and Styling:**\
  Modify the custom keyframes in the `<style>` section or update the Tailwind CSS classes in the HTML to adjust the design and animations.

## Contributing

Contributions are welcome! If you have improvements or suggestions, feel free to fork the repository and submit a pull request. Please ensure that your changes follow the project’s coding style and include clear documentation.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to [Tailwind CSS](https://tailwindcss.com/) for providing an easy-to-use utility-first CSS framework.
- Thanks to the creators of the GIFs and animations used in this project.

Made with ❤️ by Toewaioo
