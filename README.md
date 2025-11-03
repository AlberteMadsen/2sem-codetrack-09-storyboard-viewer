Storyboard Viewer
=================

A very small static web project that displays a sequence of storyboard frames with captions and simple layout controls.

What it is
----------
- A single-page HTML viewer (`index.html`) that shows a set of frames (images + captions).
- Includes a control to toggle between 2 and 3 columns.

Project structure
-----------------
- `index.html` — main static page and inline styles/scripts
- `assets/frames/` — PNG frame images (frame_01.png ... frame_10.png)

Controls / Usage
----------------
- Use the "Columns" buttons in the header to switch the grid between 2 and 3 columns.
- Images are lazy-loaded with `loading="lazy"` to improve performance.

Adding or replacing frames
--------------------------
- Place image files into `assets/frames/` and update or add a corresponding `<figure class="frame">` block in `index.html`.
- Keep the image filenames and `img` `src` attributes consistent (example: `assets/frames/frame_11.png`).

Notes
-----
- This is a static demo project — no build step is required.
- Works in modern browsers.
