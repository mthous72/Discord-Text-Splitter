# Text Splitter

A simple, lightweight application for splitting large text into smaller chunks of a specified maximum length, while intelligently preserving paragraph or word boundaries.

## What is Text Splitter?

Text Splitter is a single-file HTML/JavaScript tool that helps you break down large blocks of text into smaller segments with a specific character limit. The application runs entirely in your browser - no server required, no data sent anywhere, and no installation needed.

Many platforms, APIs, and tools impose character limits (like social media, messaging platforms, or AI interfaces). This tool makes it easy to split your content in a way that preserves readability by respecting paragraph structures and word boundaries.

## How It Works

1. You paste your large text into the input area
2. Select your preferred splitting method:
   - **Paragraph mode**: Tries to keep paragraphs intact and only splits when a paragraph exceeds the character limit
   - **Word mode**: Ensures no words are cut in half, creating clean splits at word boundaries
3. Set your desired character limit (default is 2000 characters)
4. Click "Process Text"
5. Each segment appears in the output area with its own "Copy" button for easy transfer to your target platform

## Features

- Split text into segments with a customizable character limit (default: 2000 characters)
- Choose between two splitting methods:
  - **Paragraph Boundaries**: Preserves complete paragraphs when possible
  - **Word Boundaries**: Ensures no words are cut in the middle
- Real-time character count
- Easy copying with dedicated buttons for each text segment
- Visual feedback when copying
- Works as both a web app and a desktop application

## Use Cases

- Preparing content for platforms with character limits
- Breaking down large documents into smaller, manageable pieces
- Processing text for APIs with size restrictions
- Splitting content for social media posts

## Getting Started

The beauty of Text Splitter is its simplicity. The entire application is contained in a single HTML file.

### To Use Text Splitter:

1. Download the `index.html` file
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge, etc.)
3. That's it! No installation, no server, no internet connection required

The application is entirely client-side, meaning your text never leaves your computer. It's completely private and secure.

### Implementation Details:

Text Splitter is built with:
- **HTML5**: For structure
- **CSS3**: For styling
- **Vanilla JavaScript**: For text processing logic

No external libraries or frameworks are used, making it extremely lightweight and portable.

## How It Works

1. Paste your text into the input area
2. Select your preferred splitting method (paragraph or word boundaries)
3. Set the maximum character count per segment
4. Click "Process Text"
5. Use the "Copy" buttons next to each segment to copy them to your clipboard

## Development

### Project Structure

This is an intentionally simple project:

```
text-splitter/
└── index.html       # The entire application
```

That's it! Everything is contained in a single file for maximum portability.

### Technical Highlights

- **Self-contained**: Everything (HTML, CSS, JavaScript) is in one file
- **No dependencies**: No need for npm, libraries, or frameworks
- **Cross-platform**: Works on any device with a modern browser
- **Offline capable**: No internet connection required after initial download
- **Private**: All processing happens locally in your browser

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Acknowledgments

- Created to solve the common problem of splitting text for character-limited platforms
- Inspired by the need for a simple, cross-platform text processing tool



MIT License

Copyright (c) 2025 mthous72

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
