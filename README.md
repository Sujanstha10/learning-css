# Learning css using scss

## Overview

This project is a website developed using **HTML**, **CSS**, and **SCSS**. It demonstrates responsive web design principles, clean code structure, and modern web development techniques.

## Features

- **Responsive Design**: The website adjusts to different screen sizes (mobile, tablet, desktop).
- **SCSS (Sassy CSS)**: SCSS is used for easier management of CSS with variables, nesting, and mixins.
- **Clean and Organized Code**: HTML, CSS, and SCSS files are well-structured and easy to read.

## Technologies Used

- **HTML5**: For structuring the content.
- **CSS3**: For styling the website.
- **SCSS (Sass)**: For writing maintainable and scalable CSS.

## Installation

### 1. Install Node.js and npm (if not already installed)

To compile SCSS, you'll need Node.js and npm. You can download them from the [Node.js official website](https://nodejs.org/).

### 2. Install Sass

Once Node.js is installed, you can install Sass globally by running the following command in your terminal:

```bash
npm install -g sass
```

### 3. Clone the repository

```bash
git clone https://github.com/Sujanstha10/learning-css.git
```

Navigate to the project directory:

```bash
cd your-project-name
```

### 4. Configure npm Script

In your `package.json` file, add the following script to compile SCSS to CSS:

```json
"scripts": {
  "sass": "sass ./sass/main.scss css/style.css -w"
}
```

This will monitor the `main.scss` file inside the `sass/` folder and compile it into `style.css` inside the `css/` folder.

### 5. Compile SCSS

Run the following command to start compiling SCSS:

```bash
npm run sass
```

This command will watch your `main.scss` file for changes and automatically compile it into the `css/style.css` file.

## How to Use

Open `index.html` in your web browser to view the website.

## Project Structure

```
├── index.html
├── css
│   └── style.css
├── sass
│   └── main.scss
├── img
│   └── [images used in the project]
├── package.json
└── README.md
```

## License

This project is open-source and available under the [MIT License](LICENSE).
