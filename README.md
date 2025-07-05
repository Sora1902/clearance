# Clearance 🚀

![Clearance](https://img.shields.io/badge/Clearance-CLI%20Tool-blue.svg)
![Go](https://img.shields.io/badge/Built%20with-Go-00ADD8.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

Clearance is a lightweight CLI tool designed to help developers clean up their development caches and free up disk space. Built with Go, Clearance enables you to maintain a tidy development environment by removing unnecessary cache files. Whether you’re dealing with Docker caches, npm caches, or other temporary files, Clearance has you covered.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Supported Platforms](#supported-platforms)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Features

- **Lightweight**: Minimal footprint on your system.
- **Cross-Platform**: Works on Windows, macOS, and Linux.
- **Multiple Cache Types**: Supports various cache types including Docker, npm, and Yarn.
- **Simple Commands**: Easy to use commands for cleaning up caches.
- **Safe to Use**: Removes only unnecessary files, keeping your important data intact.

## Installation

To install Clearance, visit the [Releases](https://github.com/Sora1902/clearance/releases) section on GitHub. Download the appropriate binary for your operating system and execute it. 

For example, if you are using Windows, download the `.exe` file, and run it in your command prompt.

### Example Installation Steps

1. Go to the [Releases](https://github.com/Sora1902/clearance/releases) section.
2. Download the binary for your OS.
3. Place the binary in a directory included in your system's PATH.

## Usage

Using Clearance is straightforward. Open your terminal or command prompt and run the following command:

```bash
clearance clean
```

This command will initiate the cleanup process. You can also specify cache types:

```bash
clearance clean --docker
clearance clean --npm
clearance clean --yarn
```

Each command will target the specified cache type and remove unnecessary files.

### Help Command

To see all available commands and options, run:

```bash
clearance --help
```

This will display a list of commands and their descriptions.

## Supported Platforms

Clearance supports the following platforms:

- **Windows**: Compatible with Windows 10 and Windows 11.
- **macOS**: Works on recent versions of macOS.
- **Linux**: Compatible with most distributions.

## Contributing

We welcome contributions! If you want to help improve Clearance, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Test your changes.
5. Submit a pull request.

Please ensure your code adheres to the existing style and includes tests where applicable.

## License

Clearance is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Links

For more information, visit the [Releases](https://github.com/Sora1902/clearance/releases) section to download the latest version and check for updates. 

Feel free to explore the code and contribute to making Clearance even better! 

---

### Acknowledgments

Thanks to the Go community for their support and contributions. Your efforts make it easier for developers to create efficient tools.

### Additional Resources

- [Go Documentation](https://golang.org/doc/)
- [Docker Documentation](https://docs.docker.com/)
- [npm Documentation](https://docs.npmjs.com/)
- [Yarn Documentation](https://yarnpkg.com/getting-started)

### Feedback

We value your feedback! If you encounter any issues or have suggestions, please open an issue in the GitHub repository.

---

By maintaining a clean development environment, you can focus more on coding and less on managing cache files. Clearance makes this process simple and efficient. Enjoy coding!