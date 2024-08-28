# Inspirational Message Generator

This JavaScript code provides a random inspirational message along with a piece of ASCII art to motivate and uplift users. The code randomly selects parts from three arrays—`messIntro`, `messMiddle`, and `messEnd`—to generate a complete message and combines it with a random piece of ASCII art from the `asciiArtArray`.

## Code Overview

### Arrays

- **`messIntro`**: Contains various introductory phrases for the inspirational messages.
- **`messMiddle`**: Contains various middle phrases to build upon the introduction.
- **`messEnd`**: Contains various concluding phrases to complete the message.
- **`asciiArtArray`**: Contains different pieces of ASCII art to visually enhance the inspirational message.

### Code Explanation

1. **Random Selection**:

   - A random phrase is selected from `messIntro`, `messMiddle`, and `messEnd` arrays.
   - A random piece of ASCII art is selected from `asciiArtArray`.

2. **Message Construction**:

   - The selected phrases are concatenated to form a complete inspirational message.
   - The selected ASCII art is appended to the message.

3. **Output**:
   - The final inspirational message and ASCII art are logged to the console.

### Example Output

Each sunrise brings a new chance to you embrace your inner potential and push forward and reach heights you never imagined possible.
**\_**  
 / \\
| () () |
\\ ^ /
|||||
|||||

## Usage

1. Copy and paste the provided JavaScript code into a JavaScript file (e.g., `inspirationalMessage.js`).
2. Run the file using Node.js or include it in your web application.
3. Observe the console output, which will display a randomly generated inspirational message and ASCII art.

## Contributing

Feel free to contribute to this project by adding more phrases or ASCII art to the arrays. Pull requests and suggestions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
