
# Login Modal

A small, responsive login modal component built for personal practice with Tailwind CSS.

![Login Modal screenshot](images/login-modal.png)

Why this project exists
- A compact component-sized project to practice Tailwind utility classes.
- Focuses on layout, responsive design, and accessible modal patterns.

## Features

- Responsive modal dialog for login (email + password).
- Keyboard accessible: focusable inputs and buttons, logical tab order.
- Mobile-first design using Tailwind CSS utilities.
- Lightweight: single static HTML file (no build step required).

## Built with

- HTML5
- Tailwind CSS (utility-first CSS)

## File structure

- `index.html` — the demo page containing the modal markup and Tailwind classes.
- `images/` — artwork and screenshots used in the README and demo.
- `README.md` — this file.

## Quick start (Windows PowerShell)

Open the project folder in VS Code or your editor of choice, then either open `index.html` directly in your browser or run a small local server.

Open directly (default browser):

```powershell
Invoke-Item .\\index.html
```

Run a quick static server (recommended when testing relative imports or XHR):

```powershell
# Using Python 3
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

Or use the VS Code Live Server extension to serve the file while you edit.

## Usage

1. Open the page and click the "Login" button (or whichever trigger is provided) to open the modal.
2. Enter an email and password and submit. The demo does not perform real authentication — it's a UI prototype.

To reuse the modal in your own project, copy the modal markup from `index.html` and the minimal Tailwind utility classes you need. If your project uses a Tailwind build, convert any inline classes to your preferred style or components.

## Customization tips

- Colors: adjust utility classes like `bg-white`, `text-gray-900`, or replace them with your design system tokens.
- Sizing: change spacing classes (`p-4`, `px-6`, `max-w-md`, etc.) to adapt the modal to different content.
- Animations: add Tailwind's transition and transform utilities or integrate with @tailwindcss/animations for fancier motion.

## Accessibility notes

- The demo aims to follow accessible modal patterns: focus is kept within the modal while open and an accessible label is provided. For production use, ensure:
  - The modal has `role="dialog"` and `aria-modal="true"`.
  - A visible and programmatic focus trap is implemented (so keyboard users can't tab behind the modal).
  - The close control is reachable by keyboard and announced to screen reader users (use `aria-label` or visible text).

## Contributing

This is a personal practice project. Feel free to copy, adapt, and improve the modal for your own use. If you'd like suggestions or improvements, open an issue or send a PR with a short description of the change.

## License & credits

This repository is for personal use and learning. See the top-level `LICENSE` file for terms that apply to the whole workspace.