Ideal for beginners learning modern HTML layout principles.


---

📐 Document Structure Overview

1. Doctype Declaration

The page starts with a <!DOCTYPE html> declaration, telling the browser to render the document in HTML5 mode.


2. HTML Root Element

<html> is the root element, with a lang attribute set to "en" for English.

This element wraps the entire content of the page.



---

🧠 Head Section

The <head> contains meta-information not directly displayed on the page, including:

Character Encoding: Defined as UTF-8 to support a wide range of characters.

Viewport Settings: Enables responsive design for different screen sizes, especially mobile.

Page Title: Sets the text shown in the browser tab.

External Stylesheet Link: Connects the page to an external CSS file for styling.



---

🧍‍♂️ Body Section

This is where all visible content is placed. It includes several semantic sections for structure and accessibility.

1. Header

Contains a <nav> element for the main navigation bar.

Includes a heading (restaurant name) and a navigation list with links to different pages (Home, Menu, Reservations, Contact).


2. Hero Section

A visually prominent section designed to welcome users.

Includes a subheading, a short description, and a call-to-action button linking to the reservation page.


3. Featured Menu Items

Introduced with a heading.

Contains a set of featured dishes, each including an image and a brief description with a price.


4. About Section

Gives a short description of the restaurant’s background and values.

Simple and informative content wrapped in a semantic <section>.


5. Testimonials

Showcases customer feedback using a <blockquote> element to highlight a review.


6. Footer

Located at the bottom of the page.

Displays a copyright notice.



---

✅ Syntax Highlights

Semantic Tags: Uses modern semantic elements like <header>, <nav>, <section>, <footer>, which improve readability and SEO.

Class Attributes: Used for styling purposes, allowing the linked CSS file to target specific sections.

Alt Text: Provided for all images, enhancing accessibility and usability.

Linking: Navigation uses anchor tags (<a>) to link to other pages within the site.

Consistency: Indentation, tag usage, and layout are consistent and clean.



---

🛑 Minor Issue

The closing </html> tag is missing the closing angle bracket >. This should be fixed to ensure proper parsing by browsers.
