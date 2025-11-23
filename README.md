# Login-Signup-Page

A simple HTML/JS/CSS starter template for a login and signup page.

# Project Blueprint

## Overview

This project is a single-page application that provides a modern and visually consistent login and user registration interface. Both the login and "Create Account" forms are contained within a single `index.html` file, with JavaScript used to toggle between the two views.

## Design and Style

*   **Aesthetics:** A modern, clean, and stylish user interface.
*   **Color Palette:**
    *   **Background:** A dark purple gradient (`#4f3289` to `#381d63`).
    *   **Containers:** A split layout with a purple illustration side and a white form side.
    *   **Accents:** A vibrant purple (`#7c5ac2`) for the login button and a green (`#28a745`) for the registration button.
    *   **Text:** Dark grey for forms and labels, white for the illustration section.
*   **Typography:** The 'Poppins' font is used throughout the application.
*   **Layout:** A two-column container with an illustration on the left and the form section on the right. The form section switches between the login and signup forms.
*   **Visual Effects:**
    *   **Drop Shadows:** The main container and buttons have soft shadows for a lifted look.
    *   **Rounded Corners:** The main container and buttons have rounded corners.

## Project Structure

*   **`index.html`:** The single file containing all HTML, CSS, and JavaScript for the application. It includes both the login and signup forms.
*    **`cartoon.png`:** An illustration image used on the login and signup page.

## Features

*   **Single-Page Application:** The login and signup processes are handled on a single page, providing a seamless user experience without page reloads.
*   **Dynamic Form Switching:** JavaScript is used to show or hide the login and signup forms based on user interaction.
*   **Login Form:**
    *   Includes fields for username and password.
    *   Features a link to switch to the "Create Account" view.
*   **Create Account Form:**
    *   A comprehensive registration form with fields for username, email, first name, last name, password, and password confirmation.
    *   Includes detailed client-side validation hints and password requirements.
    *   Features a link to switch back to the login view.

## Latest Changes

*   **Consolidated into Single Page:** The `signup.html` content was merged into `index.html`.
*   **Added Toggle Logic:** JavaScript was added to switch between the login and signup forms dynamically.
*   **Removed Redundant File:** The separate `signup.html` file was deleted.
*   **Updated Blueprint:** The `blueprint.md` has been updated to reflect the new single-page architecture.
