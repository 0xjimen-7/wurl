# wurl
ultra-fast fetch urls to extract all urls and their fragmented parts like paths, query parameters, and files highly dangerous for your bug bounty

# Bug Bounty URL Extractor

![Project Logo](logo.png) (if you have a logo, include it here)

## Description

The Bug Bounty URL Extractor is an ultrarapid application designed to extract all URLs and their fragmented parts, such as routes, query parameters, and potentially dangerous files from a given domain. This tool is specifically developed to aid bug bounty hunters in discovering potential security vulnerabilities and vulnerabilities that could be exploited by malicious actors.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)
- [Changelog](#changelog)
- [Code of Conduct](#code-of-conduct)
- [Credits](#credits)

## Installation

To install and set up the Bug Bounty URL Extractor, follow these steps:

1. Clone the repository to your local machine.
2. Ensure you have Go (Golang) installed.
3. Install any required dependencies by running `go get` for the project.
4. Set up environment variables, such as `VT_API_KEY`, if required.
5. Compile the application using `go build`.
6. Run the application with the necessary flags and parameters.

## Usage

The Bug Bounty URL Extractor allows you to extract URLs and their parts from one or multiple domains. You can use the following flags and options to customize the extraction process:

- `-dates`: Show the date of the fetched URLs in the first column.
- `-no-subs`: Exclude subdomains of the target domain from the extraction.
- Provide domain names as command-line arguments or read from stdin.

The application will fetch URLs using various fetch functions, analyze the results, and filter out unwanted or irrelevant URLs. It will then save the extracted data to separate files for further analysis.

## Features

- Ultrafast URL extraction for bug bounty hunters and security researchers.
- Customizable options for displaying dates and excluding subdomains.
- Filtering out URLs with ignored file extensions to focus on potential security risks.
- Saving extracted URLs and their parts in separate files for easy analysis.

## Contributing

We welcome contributions from the open-source community. If you would like to contribute to the Bug Bounty URL Extractor, please follow these guidelines:

1. Fork the repository and create a new branch for your contribution.
2. Make your changes and additions following the project's coding style.
3. Write clear and detailed commit messages.
4. Open a pull request, and our team will review your changes.

Contributions of all sizes are valuable, and we appreciate your efforts in improving the application.

## License

The Bug Bounty URL Extractor is released under the [MIT License](LICENSE). You are free to use, modify, and distribute the application following the terms of this license.

## Support

If you encounter any issues or have questions related to the Bug Bounty URL Extractor, you can reach out to us via email or join our support community on [Discord](https://discord.gg/bugbounty).

## Changelog

### v1.0.0 - Initial Release (YYYY-MM-DD)

- Ultrafast URL extraction from multiple domains.
- Customizable options for date display and subdomain exclusion.
- Filtering out URLs with ignored file extensions.
- Saving extracted URLs and their parts to separate files.

## Code of Conduct

We maintain a code of conduct to ensure a welcoming and inclusive community. Please read our [Code of Conduct](CODE_OF_CONDUCT.md) to understand the expected behavior when participating in our project.

## Credits

The Bug Bounty URL Extractor is developed and maintained by [Your Name](https://github.com/yourusername). We would like to thank all contributors and supporters who have helped make this project possible.

---

Customize the content and sections with relevant information for your specific project. Remember to include details about the application's functionality, its purpose, and how it aids bug bounty hunting. A well-crafted README can attract more users and contributors to your project. Good luck and happy bug hunting!
