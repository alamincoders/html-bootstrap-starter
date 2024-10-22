# HTML Bootstrap Starter

Welcome to the HTML Bootstrap Starter project! This template provides a structured approach to building responsive and stylish web applications using Bootstrap and custom utility classes.

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
- [Custom Utility Classes](#custom-utility-classes)
  - [Color Utilities](#color-utilities)
  - [Spacing Utilities](#spacing-utilities)
  - [Flex-box Utilities](#flexbox-utilities)
  - [Typography Utilities](#typography-utilities)
  - [Width & Height Utilities](#width--height-utilities)
  - [Responsive Utilities](#responsive-utilities)
- [Usage Examples](#usage-examples)
- [Full List of Utilities](#full-list-of-utilities)
- [How to Run the Project](#how-to-run-the-project)
- [Contributing](#contributing)

---

## Overview

This project is designed to help developers quickly create responsive web applications using:

![html](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![css](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![sass](https://img.shields.io/badge/SASS-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

## Getting Started

To get started with this project, simply clone the repository and include the necessary Bootstrap and custom stylesheets in your HTML file.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta
      name="viewport"
      content="width=device-width, initial-scale=1.0"
    />
    <title>Html Bootstrap Starter</title>
    <script
      type="module"
      src="./js/main.js"
    ></script>
  </head>
  <body>
    <!-- Your content goes here -->
  </body>
</html>
```

---

## Custom Utility Classes

### Color Utilities

Easily set text, background, and border colors with our utility classes:

- `ut-color-primary`: Text color using the primary theme color.
- `ut-bg-success`: Background color using the success color.
- `ut-border-danger`: Border color using the danger theme color.

### Spacing Utilities

Control the spacing around elements using margin (`ut-m`) and padding (`ut-p`) utilities. You can also apply margin and padding to specific sides:

- `ut-mt-3`: Adds top margin with a size of 12px (3 x 4px).
- `ut-px-4`: Adds horizontal padding (left and right) of 16px.

You can combine horizontal and vertical spacings:

- `ut-mx-my-5`: Adds margin on the X (horizontal) and Y (vertical) axis with 20px.

### Flexbox Utilities

For layout and alignment control:

- `ut-flex`: Applies `display: flex`.
- `ut-justify-center`: Centers items along the main axis.
- `ut-items-start`: Aligns items at the start along the cross-axis.

### Typography Utilities

Control text styles and alignment:

- `ut-font-bold`: Bold font weight.
- `ut-text-uppercase`: Converts text to uppercase.
- `ut-text-size-5`: Sets text size using a dynamic scale (clamp-based).

### Width & Height Utilities

Control element size:

- `ut-w-full`: Full width.
- `ut-h-auto`: Automatic height adjustment based on content.

### Responsive Utilities

Responsive spacing adapts based on the viewport size using `clamp()`:

- `ut-m-responsive-4`: Margin that scales responsively.
- `ut-p-responsive-3`: Padding that adjusts dynamically.

---

## Usage Examples

Here are some examples of how to use the custom utility classes in your HTML:

```html
<div class="ut-bg-primary ut-p-4 ut-text-center">Welcome to the Project!</div>

<button class="ut-bg-success ut-px-3 ut-py-2 ut-text-uppercase ut-font-bold">
  Click Me
</button>

<section class="ut-m-responsive-4 ut-p-responsive-5">
  This section has responsive margins and padding.
</section>
```

---

## Full List of Utilities

### Spacing

- **Margin (m)**: `ut-m-0` to `ut-m-20`, with directional variants like `ut-mt`, `ut-mb`, `ut-ml`, `ut-mr`
- **Padding (p)**: `ut-p-0` to `ut-p-20`, with directional variants like `ut-pt`, `ut-pb`, `ut-pl`, `ut-pr`
- **Combined Spacing**: Horizontal (`ut-mx`, `ut-px`) and Vertical (`ut-my`, `ut-py`)

### Color

- **Text Color**: `ut-color-{variant}`
- **Background Color**: `ut-bg-{variant}`
- **Border Color**: `ut-border-{variant}`

### Flex-box

- `ut-flex`
- `ut-flex-row`
- `ut-flex-col`
- `ut-justify-center`
- `ut-justify-between`
- `ut-items-center`
- `ut-items-start`
- `ut-items-end`
- `ut-gap-1` to `ut-gap-3`

### Typography

- `ut-font-bold`
- `ut-font-light`
- `ut-font-medium`
- `ut-text-left`
- `ut-text-center`
- `ut-text-right`
- `ut-text-uppercase`
- `ut-text-size-1` to `ut-text-size-10`

### Width & Height

- `ut-w-full`
- `ut-w-auto`
- `ut-h-full`
- `ut-h-auto`

### Border Radius

- `ut-rounded-0` to `ut-rounded-10`

### Shadows

- `ut-shadow-sm`
- `ut-shadow-md`
- `ut-shadow-lg`

### Display

- `ut-block`
- `ut-inline-block`
- `ut-hidden`
- `ut-inline-flex`

### Overflow

- `ut-overflow-hidden`
- `ut-overflow-auto`
- `ut-overflow-scroll`

### Cursor

- `ut-cursor-pointer`
- `ut-cursor-not-allowed`

### Opacity

- `ut-opacity-100`
- `ut-opacity-75`
- `ut-opacity-50`
- `ut-opacity-25`
- `ut-opacity-0`

---

## How to Run the Project

To run the project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/html-bootstrap-starter.git
   ```

2. Navigate to the project directory:

   ```bash
   cd html-bootstrap-starter
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server with the following command, which will also open the application in your default browser:

   ```bash
   npm run dev
   ```

   Alternatively, you can start the server without opening the browser:

   ```bash
   npm start
   ```

5. Open your browser and visit `http://localhost:3000` (or the specified IP address if running on a different host).

6. To build the project for production, use:

   ```bash
   npm run build
   ```

---

## Contributing

We welcome contributions to this project! Please feel free to open issues or pull requests for improvements or suggestions. Together, we can make this project even better.

---

Happy coding! 🎉
