# Jadezo CSS

Developed by Zarmeen, Jesse, & Daniela

## Installation

To use Jadezo CSS in your project, follow these steps:

1. **Create a Directory:** At your website's root level, create a directory titled `css`. Within this folder, create a `main.css` file.

2. **Link the CSS File:** In your `index.html` file, link to the `main.css` file to include Jadezo CSS in your project.

3. **Compile SASS:** Use the following command: sass --watch ./src/main.scss ./css/main.css

## Usage

With Jadezo CSS, you can easily customize the appearance of text on your website by adding specific classes to your HTML tags. Replace `[brackets]` with your desired attribute:

- **Font Weight:** `type-weight-[weight]`
- **Font Italic:** `type-[italic]`
- **Line Height Utilities:** `type-line-[tight, normal, loose]`
- **Letter Spacing:** `type-spacing-[tight, normal, wide]`
- **Text Transform:** `type-[uppercase, lowercase, capitalize]`
- **Text Alignment:** `type-align-[left, center, right, justify]`

### Text Colors

Apply color to your text using these utility classes:

- **Primary:** `.text-primary` - Use for primary text.
- **Secondary:** `.text-secondary` - Use for secondary text.
- **Success:** `.text-success` - Use for success messages.
- **Info:** `.text-info` - Use for informational messages.
- **Warning:** `.text-warning` - Use for warnings.
- **Error:** `.text-error` - Use for errors.
- **Light:** `.text-light` - Use for light text on dark backgrounds.
- **Dark:** `.text-dark` - Use for dark text on light backgrounds.

### Background Colors

To set background colors, use the following classes:

- **Primary:** `.bg-primary`
- **Secondary:** `.bg-secondary`
- **Success:** `.bg-success`
- **Info:** `.bg-info`
- **Warning:** `.bg-warning`
- **Error:** `.bg-error`
- **Light:** `.bg-light`
- **Dark:** `.bg-dark`

### Font Weight and Sizes

For font weight:

- **Normal:** `.font-normal`
- **Bold:** `.font-bold`

For font sizes:

- **Large (lg):** `.font-lg`
- **Small (sm):** `.font-sm`
- **Extra Small (xs):** `.font-xs`
- **Extra Large (xl):** `.font-size-xl`
- **2x Extra Large (2xl):** `.font-size-2xl`

### Strong and Emphasis Styles

Emphasize text using `.strong` for bold and `.emphasis` for italic text. These classes make it easy to highlight parts of your text.

### Buttons

Create interactive and visually appealing buttons by applying these classes:

- **Primary Button:** `btn-primary` - Use for main actions.
- **Secondary Button:** `btn-secondary` - Use for alternative actions.
- **Success Button:** `btn-success` - Use for successful actions.
- **Info Button:** `btn-info` - Use for informational buttons.
- **Warning Button:** `btn-warning` - Use for warnings or cautionary actions.
- **Error Button:** `btn-error` - Use for error-related actions.
- **Light Button:** `btn-light` - Use for light-themed buttons.
- **Dark Button:** `btn-dark` - Use for dark-themed buttons.

### Blockquotes

Enhance the presentation of quotes or highlighted text with these styles:

- **Primary Blockquote:** .blockquote-primary - Use for important quotes.
- **Secondary Blockquote:** .blockquote-secondary - For secondary emphasis.
- **Success Blockquote:** .blockquote-success - Highlights success or positive quotes.
- **Warning Blockquote:** .blockquote-warning - Use for cautionary or warning quotes.
- **Error Blockquote:** .blockquote-error - For error or critical messages.
- **Info Blockquote:** .blockquote-info - For informational content.
- **Light Blockquote:** .blockquote-light - Light-themed for dark backgrounds.
- **Dark Blockquote:** .blockquote-dark - Dark-themed for contrast on light backgrounds.
