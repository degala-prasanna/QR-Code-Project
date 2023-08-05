
---

# QR Code Generator

This is a Node.js project that generates a QR code for a user-provided URL using the "qr-image" and "inquirer" packages from NPM. It allows users to input the URL via the command line and then generates a QR code image and saves it as a PNG file.

## Installation

To run this project, you need to have Node.js installed on your system. Follow these steps to set up and run the project:
1. Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

```bash
git clone  https://github.com/degala-prasanna/QR-Code-Project.git
```

2. Change into the project directory.

```bash
cd QR-code-project
```

3. Install the required dependencies using NPM.

```bash
npm install
```

### Usage

To generate a QR code and store the user input URL into a text file, follow these steps:

1. Run the project.

```bash
node index.js
```

2. The command-line tool will prompt you to enter a URL.

3. Enter the URL you want to generate the QR code for.

4. The tool will generate a QR code image named `qrimage.png` in the project directory.

5. The user input URL will be stored in the `URL.txt` file.

### Dependencies

The project relies on the following NPM packages:

- `qr-image`: This package is used to generate the QR code image based on the user input URL.
- `inquirer`: This package is used to prompt the user for the URL input in the command line.

The `package.json` and `package-lock.json` files list the project dependencies. To install the required dependencies, run `npm install` in the project directory.

### File Structure

The project directory contains the following files:

- `index.js`: The main entry point of the application.
- `package.json`: The file that holds project metadata and dependencies information.
- `package-lock.json`: The lock file for NPM dependencies.
- `qrimage.png`: The generated QR code image file.
- `URL.txt`: The text file where the user input URL is stored.
- `node_modules`: The directory where NPM packages and dependencies are installed.

### Contributing

If you wish to contribute to this project, you can fork the repository, make your changes, and create a pull request. We welcome any improvements or bug fixes!

### Contact

If you have any questions or suggestions, feel free to contact us at [saiprasannadegala19@gmail.com].
