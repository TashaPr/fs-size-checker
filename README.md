# fs-size-checker

A powerful CLI tool to check the size of files and directories.

## Features

- [x] Check sizes of files and directories
- [x] Set size limits and get warnings when exceeded
- [x] Configurable via command-line arguments
- [ ] Configurable via a configuration file
- [ ] Use regex patterns to match specific filesenhancement)*
- [ ] Colorized output for better readability

Legend:
- [x] Implemented feature
- [ ] Planned feature

## Key Characteristics

- **Zero Dependencies**: This project is built without any external runtime dependencies, ensuring a lightweight and secure installation.
- **Object-Oriented Programming (OOP) Approach**: Utilizes OOP principles for better code organization, maintainability, and extensibility.
- **TypeScript**: Written in TypeScript for enhanced type safety and better developer experience.
- **SOLID Principles**: Adheres to SOLID principles of object-oriented design, promoting clean and maintainable code.
- **Extensible Architecture**: Designed with extensibility in mind, making it easy to add new features or modify existing ones.
- **Cross-platform Compatibility**: Works on Windows, macOS, and Linux operating systems.
- **Comprehensive Test Suite**: Includes a robust set of unit and integration tests to ensure reliability.
- **Well-documented**: Provides clear and comprehensive documentation for easy understanding and usage.

## Security

- No execution of external code or scripts
- Strict input validation to prevent potential vulnerabilities
- Read-only operations ensure no modifications to your file system

## Installation

Prefer to use it as a development dependency in your project:

```bash
npm install --save-dev fs-size-checker
```

## Usage

### Using as an npm script

You can also add `fs-size-checker` as a script in your `package.json` file. This is useful for projects where you want to check file sizes as part of your development or build process.

Add one of the following scripts to your `package.json`:

Examples:

1. Using a specific directory and size limit in KB:

```json
{
  "scripts": {
    "check-size": "fs-size-checker ./dist 50000"
  }
}
```

2. Checking a specific file with a size limit in KB:

```json
{
  "scripts": {
    "check-file-size": "fs-size-checker ./dist/index.js 1000"
  }
}
```

Run it with:

```bash
npm run check-size
```

Options:
- `<path>`: The path to check. Can include directory and file matching.
- `<max_size>`: The maximum allowed size (a positive number) in KB.

## Development

To set up the project for development:

1. Clone the repository
2. Install dependencies: `npm install`
3. Build the project: `npm run build`
4. Run tests: `npm test`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file in the project root for the full license text.

The MIT License is a permissive license that allows for reuse with few restrictions. It permits use, modification, distribution, sublicense, and private use, provided that the license and copyright notice are included in all copies or substantial portions of the software.
