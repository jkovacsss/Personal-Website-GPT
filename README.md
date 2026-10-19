# Personal Website GPT

A responsive, single-page personal website built with plain HTML, CSS, and JavaScript. No build tools or dependencies are required.

## Files

- `index.html` — page content and semantic structure
- `styles.css` — responsive layout, colors, typography, and project-card illustrations
- `script.js` — mobile navigation and automatic footer year

## Personalize it

1. In `index.html`, replace **Your Name** and the **YN** initials with your name and initials.
2. Replace `you@example.com` with your email address.
3. Update the About section, projects, interests, and location so they reflect you.
4. Change the page title and description in the `<head>`.
5. If you add external project links, point each project card to the appropriate page or repository.

## Preview locally

Open `index.html` in a browser. For the best local development experience, use the Live Server extension in Visual Studio Code.

## Publish with GitHub Pages

1. Open this repository on GitHub and select **Settings**.
2. Choose **Pages** in the sidebar.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/(root)`, then save.
5. After GitHub Pages finishes deploying, the published URL will appear in the Pages settings.

The repository can remain private, but whether the published site can be public depends on your GitHub plan and organization settings.

## Customize the look

The main colors and font stacks are defined as CSS variables at the top of `styles.css`. The design uses a dark background, lime accent, and responsive layouts for smaller screens. Google Fonts are loaded from an external stylesheet; system fonts will be used if they are unavailable.