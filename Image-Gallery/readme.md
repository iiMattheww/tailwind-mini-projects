# Image Gallery

A responsive image gallery built with Tailwind CSS. The gallery demonstrates grid layout, hover overlays, simple search UI and responsive breakpoints.

## Preview

![Gallery preview](images/image-gallery.png)

## Features

- Responsive grid: adapts from single-column to multi-column at md/lg/xl breakpoints
- Hover overlay with metadata and an icon
- Minimal search input and an Upload action (UI only)
- Accessible-ish markup (images include alt attributes)

## How to view

Open `index.html` in your browser, or serve the folder and browse to it:

```powershell
python -m http.server 8000
# then open http://localhost:8000/Image-Gallery/
```

## Notes and suggestions

- Images are static assets in the `images/` folder; swap them with your own for experimentation.
- The example uses the Tailwind browser bundle via CDN. For production use, add a proper build step and optimize images.

## License

Follow the repository license for reuse.
