# Define ANSI escape codes for text colors

- Default: `\x1b[0m`
- Red: `\x1b[31m`
- Green: `\x1b[32m`
- Yellow: `\x1b[33m`
- Blue: `\x1b[34m`
- Magenta: `\x1b[35m`
- Cyan: `\x1b[36m`
- White: `\x1b[37m`

# Example Node.js
```js
const colors = {
  reset: "\x1b[0m",
  red: "\x1b[31m",
  green: "\x1b[32m",
  yellow: "\x1b[33m",
  blue: "\x1b[34m",
  magenta: "\x1b[35m",
  cyan: "\x1b[36m",
  white: "\x1b[37m",
};

// Function to log text with color
function consoleColor(text, color) {
  console.log(`${colors[color]}${text}${colors.reset}`);
}

consoleColor('Hello world','red')
```js
