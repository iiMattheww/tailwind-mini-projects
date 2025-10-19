# Email Subscribe Card

A small, responsive email subscription card built with Tailwind CSS. This example demonstrates a compact card layout with an image, heading, description, and a simple email input + button.

## Preview

See the screenshot in `images/email-subscribe.png`.

## Features

- Responsive layout (stacks on small screens, side-by-side on md+)
- Utility-first styling using Tailwind's browser bundle (CDN)
- Hover transform on the image and simple form controls

## How to view

1. Open `index.html` in your browser (double-click the file), or serve the folder and browse to it:

   python -m http.server 8000

   Then open http://localhost:8000/Email-Subscribe-Card/ in your browser.

## Notes

This example uses the Tailwind browser bundle via CDN in the head of `index.html`:

```html
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
```

If you plan to reuse this component in a production app, integrate Tailwind with a build step so you can purge unused styles and configure theme tokens.

## License

Follow the repository license for reuse.