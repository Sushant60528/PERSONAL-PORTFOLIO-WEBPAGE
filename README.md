#PERSONAL PORTFOLIO WEBPAGE

##1. HTML Boilerplate:

The document begins with the <!DOCTYPE html> declaration, indicating it uses HTML5.

The <html> tag sets the language to English using lang="en".


<meta charset="UTF-8"> ensures the document supports a wide range of characters.

<meta name="viewport"...> enables responsive design for different devices.

<title>Developer Portfolio</title> sets the browser tab title.

A CSS file styles.css is linked for styling.



3. Body Content: The body is divided into semantic sections for better readability and accessibility:


Contains the developer's name (<h1>Susanta dash>) and a navigation menu (<nav>).

The navigation uses an unordered list (<ul>) with anchor links pointing to sections of the page (#about, #projects, #contact), allowing smooth internal navigation.


About Section:

Introduced with a heading (<h2>About Me>) and a short paragraph describing the developer’s skills.


Projects Section:

Showcases two sample projects, each inside a <div class="project"> container.

Projects include a heading (<h3>) and description.


Contact Section:

Displays the developer’s email and a link to their GitHub profile.


CSS Styling

The CSS portion defines the look and feel of the webpage:

1. Resetting Defaults:

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

This resets all elements to remove default spacing and sets box sizing for consistent layouts.


2. Base Styles:

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #f5f5f5;
  color: #333;
}

These lines give the body a clean font, good readability, and a light-gray background with dark text for contrast.


3. Header and Navigation:

The header has a dark background (#333) and white text.

Navigation links are styled to be inline and spaced, with no underlines and white color to match the header.



4. Sections and Projects:

Each section has padding and a max-width to ensure it looks good on all screen sizes.

Projects have a white background, padding, a left border, and spacing to separate them visually.



5. Footer:

The footer mirrors the header with similar background and text color, and centers the content.


Overall Functionality

The website is responsive, clean, and functional:

It introduces the developer, highlights work, and offers contact details.

#OUTPUT

![Image](https://github.com/user-attachments/assets/3425061d-2010-4134-a270-80462a20b764)

The layout is mobile-friendly due to the responsive meta tag and centered content.

The style is minimalist but effective for professional portfolios.


In summary, this code provides a great starting point for a web developer’s personal website, applying good HTML semantics and CSS practices to create a professional and appealing web presence.
