**English** | [العربية](README.ar.md)

# Random Password Generator

A small browser application that generates two random password suggestions at a time. It was built to practice JavaScript arrays, loops, random selection, functions, and DOM updates through a clean responsive interface.

## Features

- Generate two password suggestions with one click.
- Produce 15-character passwords.
- Use uppercase letters, lowercase letters, numbers, and symbols.
- Replace previous results whenever new passwords are generated.
- Adapt the result layout for narrow screens.

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts

## Run Locally

No package installation or build process is required.

```bash
git clone https://github.com/mohammadimad/Password-Generator.git
cd Password-Generator
```

Open `index.html` in a browser, or serve the directory with a local development server.

## How It Works

The `characters` array contains the available letters, digits, and symbols. When `Generateor()` runs, it clears both result boxes, selects 15 random characters for each password, and updates the page through `textContent`.

## Project Structure

```text
.
|-- index.html    # Generator interface
|-- index.css     # Responsive card styling
`-- index.js      # Character set and generation logic
```

## Security Note

This project uses `Math.random()` for educational purposes. Its output is not cryptographically secure and should not be used to generate passwords for real sensitive accounts. Production password generation should use the Web Crypto API, such as `crypto.getRandomValues()`.

## Possible Improvements

- Use a cryptographically secure random source.
- Add configurable password length.
- Let users enable or disable character categories.
- Add one-click copy buttons and confirmation feedback.
- Guarantee at least one character from each selected category.
- Add automated tests for the generation rules.

## Author

[Mohammad Imad Abdelfattah](https://github.com/mohammadimad)
