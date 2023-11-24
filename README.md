

# URL to Code 

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/your-username/your-repo-name/blob/main/LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/Bahrul-Rozak/url-to-code)](https://github.com/Bahrul-Rozak/url-to-code/issues)
[![GitHub stars](https://img.shields.io/github/stars/Bahrul-Rozak/url-to-code)](https://github.com/Bahrul-Rozak/url-to-code/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/your-username/your-repo-name)](https://github.com/your-username/your-repo-name/network)

A simple Node.js web scraper using [website-scraper](https://www.npmjs.com/package/website-scraper) to download an entire website.

## Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Bahrul-Rozak/url-to-code.git
    ```

2. Navigate to the project directory:

    ```bash
    cd your-repo-name
    ```

3. Install dependencies:

    ```bash
    npm install
    ```

### Usage

1. Open `index.js` in your preferred code editor.

2. Set the `websiteUrl` variable to the URL of the website you want to scrape.

    ```javascript
    const websiteUrl = 'https://example.com';
    ```

3. Customize other options if needed (e.g., `maxDepth`, `directory`, etc.).

4. Run the scraper:

    ```bash
    node index.mjs
    ```

5. Check the `./result` directory for the downloaded website.

## Configuration

- `urls`: An array of URLs to scrape.
- `urlFilter`: A function to filter URLs. The example filters URLs that start with the specified `websiteUrl`.
- `recursive`: If `true`, the scraper will follow links recursively.
- `maxDepth`: Maximum recursion depth.
- `prettifyUrls`: If `true`, URLs will be prettified.
- `filenameGenerator`: File naming strategy, set to `'bySiteStructure'` in the example.
- `directory`: Output directory for the downloaded website.


## Acknowledgments

- [website-scraper](https://www.npmjs.com/package/website-scraper) for providing an easy-to-use web scraping library.

Happy downloading! 🕸️
