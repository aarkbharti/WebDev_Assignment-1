# Personal Portfolio Website (Lab 1)

**Student Name:** Aark Bharti  
**Course:** B.Tech CSE (1st Year)  
**Assignment:** Lab 1 - Semantic HTML Structure

## Project Description
This is a one-page personal portfolio website created using **Semantic HTML5** tags. The purpose of this project is to demonstrate the correct usage of document structure tags without relying on CSS for styling.

## Implementation Details
According to the problem statement, I have implemented the following:

### 1. Semantic Structure
I used the following tags to organize the content:
- `<header>`: Contains the main title and navigation.
- `<nav>`: Wraps the unordered list (`<ul>`) of links.
- `<main>`: Wraps the primary content of the page.
- `<section>`: Used to separate the Hero, About, Projects, Skills, and Contact areas.
- `<footer>`: Contains the copyright and external links.

### 2. Accessibility Features
- **Skip Link:** Added a "Skip to main content" link at the very top of the body.
- **Alt Text:** The profile image includes descriptive `alt` text.
- **Form Labels:** All inputs are associated with `<label>` tags using the `for` attribute.

### 3. Content Organization
- **Projects:** Displayed using an unordered list (`<ul>`).
- **Skills:** Displayed using a structured `<table>` with headers (`<th>`).
- **Contact:** A functional form using `required` attributes and placeholders.

## File List
- `index.html`: The main source code.
- `profile.jpg`: Image asset for the Hero section.
- `README.md`: Project documentation.

## How to Test
1. Open `index.html` in any web browser.
2. Click the navigation links to verify they jump to the correct section.
3. Try submitting the form without filling it out to see the HTML5 validation (required attribute) work.