# Prigeon Website

## Project Milestone 3: Accessible & Designed

This project improves my Milestone 2 website by adding accessibility features, intentional visual design, and an accessible contact form.

## Accessibility Fixes

* Added `lang="en"` to each HTML document to help screen readers identify the page language.
* Added viewport and character encoding metadata for better accessibility and responsive behavior.
* Added descriptive page titles to all three pages.
* Added `aria-label="Main navigation"` to identify the main navigation for screen reader users.
* Added `aria-current="page"` to identify the user's current page.
* Used semantic HTML elements including `header`, `nav`, `main`, `section`, `article`, and `footer`.
* Improved the heading structure by using headings in a logical order.
* Replaced unnecessary `<b>` and `<u>` formatting with more meaningful HTML where appropriate.
* Added visible keyboard focus indicators to links, buttons, and form fields.
* Added proper `<label>` elements for every contact form input.
* Added a `<fieldset>` and `<legend>` to group related contact information.
* Added required form fields to prevent incomplete submissions.
* Added accessible error messages connected to form controls with `aria-describedby`.
* Added visual invalid states to help users identify form errors.
* Updated text and background colors to provide strong contrast and support WCAG AA accessibility requirements.
* Used the same color palette and typography throughout all three pages for consistency.

## WAVE Testing

I tested the three website pages using WAVE and corrected accessibility issues identified during testing.

Pages tested:

1. Home page
2. Projects page
3. About/Contact page

## Visual Design

### Gestalt Principle: Proximity

I used proximity to group related information together. Sections group related content, while the contact form keeps related contact fields together.

### Gestalt Principle: Similarity

I used similarity by giving related content the same visual treatment. The food cards use the same borders, spacing, background, and typography so users can recognize them as related items.

## Color Palette

The website uses a consistent color palette across all three pages:

* Dark navy: `#12355B`
* Light blue: `#D9F0F7`
* White: `#FFFFFF`
* Dark text: `#172033`
* Accessible link blue: `#064F7D`
* Error red: `#8B0000`

The colors were selected to provide clear visual separation and strong text contrast.

## Accessible Contact Form

The About/Contact page includes:

* Name field
* Email field
* Message field
* Proper labels
* Required fields
* Fieldset and legend
* Accessible error descriptions
* Keyboard focus indicators
* Invalid form styling

## Author

Created by Shavon Prigeon.
