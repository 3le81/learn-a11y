# Learn-a11y - Accessibility task

Task for identifying and fixing a11y problems on this example page: https://learn.foundersandcoders.com/workshops/learn-a11y/starter-files/ .

The page containes several failures to be identified and fixed for getting the website accessible to everyone.

These are the main issues I found, not sure it's all of them though:

1. Language not available:
   Including the lang attribute in the html tag with the appropriate language code is an important accessibility practice.

2. Title missing:
   The title tag is a crucial part of web accessibility, providing a concise and descriptive title for the web page.

3. Color Contrast:

   The color used for text (color: hsl(0, 5%, 60%);) may not provide sufficient contrast against the background, making it hard to read for users with visual impairments.

4. SVG Icon Accessibility:

   The SVG icons used for the menu button lack text alternatives (svg elements).

5. Hidden Navigation Content:

   The navigation menu (#toggleNav) is initially hidden using hidden attribute. This can be problematic for screen reader users who won't be aware of the hidden content.

6. Navigation Links:

   The navigation links within the menu (a elements) lack descriptive text or context, making it difficult for screen reader users to understand their purpose.

7. Image Alternative Text:

   The images within the carousel (img elements) lack alternative text (alt attribute), which is essential for users who rely on screen readers.

8. Semantic HTML:

   The use of h1 for the title without any additional heading levels (h2, h3, etc.) may affect the document's structure and semantic meaning.

9. Interactive Elements:

   The menu toggle button (toggleMenu) is not a semantic interactive element like a button. This could impact keyboard accessibility and the ability of screen reader users to understand its purpose.

10. SVG Icon Semantics:

    The SVG icons used for menu open/close lack semantic information. Using ARIA attributes (like aria-label, role etc.) can improve accessibility.

11. Text in Images:

    The title image (img within h1) may contain important text. If so, that text is not accessible to screen readers.

12. Scroll Snap Accessibility:

    The use of scroll snapping for the carousel may cause issues for users who navigate content differently, such as those who use screen readers or keyboard navigation.

13. Link Focus Styles:

    There are no defined focus styles for links (a elements), which can make navigation challenging for keyboard users.
