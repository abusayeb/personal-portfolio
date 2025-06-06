# vCard - Personal Portfolio Website Template

![GitHub repo size](https://img.shields.io/github/repo-size/codewithsadee/vcard-personal-portfolio)
![GitHub stars](https://img.shields.io/github/stars/codewithsadee/vcard-personal-portfolio?style=social)
![GitHub forks](https://img.shields.io/github/forks/codewithsadee/vcard-personal-portfolio?style=social)
[![Twitter Follow](https://img.shields.io/twitter/follow/codewithsadee_?style=social)](https://twitter.com/intent/follow?screen_name=codewithsadee_)
[![YouTube Video Views](https://img.shields.io/youtube/views/SoxmIlgf2zM?style=social)](https://youtu.be/SoxmIlgf2zM)

## About the Project

vCard is a personal portfolio website template designed to help you showcase your skills, projects, and experiences in a professional and engaging manner. It's built with fundamental web technologies: HTML for structure, CSS for styling, and JavaScript for interactive elements. This template provides a solid foundation for creating a personalized online presence.

## Demo

![vCard Desktop Demo](./website-demo-image/desktop.png "Desktop Demo")
![vCard Mobile Demo](./website-demo-image/mobile.png "Mobile Demo")

## Features

*   **Responsive Design**: Adapts seamlessly to all devices, including desktops, tablets, and smartphones.
*   **Multiple Sections**: Includes dedicated sections for:
    *   About Me (introduction, skills)
    *   Resume (education, experience)
    *   Projects (portfolio showcase)
    *   Contact (ways to get in touch)
*   **Interactive Elements**: Features user-friendly navigation and potentially interactive project filters (if implemented in the original template).
*   **Easy to Customize**: Designed for straightforward personalization of content and appearance.

## Customization Guide

Personalizing your vCard template is easy. Follow these steps to make it your own:

### 1. Personal Information

*   Open `index.html` in a text editor.
*   Locate the sections containing placeholder personal information.
*   **Name and Title**: Update your name and professional title (e.g., "Web Developer", "UX Designer").
*   **Contact Details**: Change the email address, phone number, birthday, and location.
*   **Social Media Links**: Update the URLs for your social media profiles (e.g., LinkedIn, GitHub, Twitter).

### 2. Replacing Images

*   **Avatar**:
    *   Prepare your avatar image (preferably square, e.g., `my-avatar.png`).
    *   Replace the default avatar at `assets/images/my-avatar.png` with your image. Ensure the filename matches or update the path in `index.html`.
*   **Project Images**:
    *   Gather images for your projects.
    *   Place them in the `assets/images/` directory (or a subdirectory like `assets/images/projects/`).
    *   Update the `<img>` tags within the project sections in `index.html` to point to your new project images.

### 3. Updating Project Details

*   In `index.html`, find the portfolio or projects section.
*   For each project item:
    *   Change the **project title**.
    *   Update the **category** (e.g., "Web Development", "UI/UX Design").
    *   Write a concise **description** of the project.
    *   Update the project link if applicable.

### 4. Modifying Testimonials

*   Locate the testimonials section in `index.html`.
*   Replace the placeholder testimonial text, author names, and avatars with real ones. If you don't have testimonials, you can comment out or remove this section.

### 5. Changing Theme Colors (Optional)

*   This template might use CSS custom properties (variables) for easy theme color changes.
*   Open `assets/css/style.css`.
*   Look for a section (usually at the top) defining CSS variables, often within the `:root` selector. Example:
    ```css
    :root {
      --primary-color: #ffdb58;
      --secondary-color: #333;
      /* ... other color variables ... */
    }
    ```
*   Modify the hex codes or color values of these variables to change the overall theme. Save the file and check your browser to see the changes. If CSS variables are not used, you'll need to find and replace color codes throughout the stylesheet.

## Prerequisites

Before you begin, ensure you have met the following requirements:

* [Git](https://git-scm.com/downloads "Download Git") must be installed on your operating system.

## Installing vCard

To install **vCard**, follow these steps:

Linux and macOS:

```bash
sudo git clone https://github.com/codewithsadee/vcard-personal-portfolio.git
```

Windows:

```bash
git clone https://github.com/codewithsadee/vcard-personal-portfolio.git
```

## Contact

If you want to contact me you can reach me at [Twitter](https://www.twitter.com/codewithsadee).

## License

MIT
Use code with caution.
