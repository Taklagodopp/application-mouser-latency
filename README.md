# Mouse Latency Tester

A simple browser-based mouse event timing demo that can be hosted for free with GitHub Pages.

## Features
- Live display of the time interval between browser-detected mouse events
- Event counter
- Reset button
- Responsive layout for desktop and mobile
- No dependencies and no data uploads

## Important limitation
This does **not** measure true hardware mouse latency. It displays the time interval between consecutive `mousemove` or `click` events received by the browser. The result depends on browser scheduling, operating-system event handling, and system load. It is not a reliable measurement of mouse polling rate either.

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser.

## Publish with GitHub Pages
1. Create a GitHub repository named `mouse-latency-tester`.
2. Upload `index.html`, `style.css`, `script.js`, and `README.md` to the repository root.
3. Open the repository's **Settings**.
4. Select **Pages** in the sidebar.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch `main` and folder `/(root)`, then click **Save**.
7. Wait for GitHub Pages to publish the site. The URL will appear on the Pages settings screen.

## Usage
Open the published page and move or click inside the test box. “Latest event interval” shows the elapsed time since the previous mouse event received by the page, in milliseconds.
