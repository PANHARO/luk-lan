# RoTrip

A static Cambodia travel website built with HTML, Tailwind CSS, and JavaScript, featuring destination sections plus about, contact, and login pages. Booking and account controls are frontend demonstrations.

## Preview

Run `python -m http.server 8000` from the repository root and open [localhost:8000](http://localhost:8000). Use `python3` if needed. The compiled stylesheet is included; external images, Tailwind CDN assets, and icons require internet access.

## Edit styles

Install Node.js and npm, then run:

```sh
npm ci
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

Edit page content in `index.html`, `about.html`, `contact.html`, and `login.html`. The local logo is in `images/logo.png`; most destination photographs load from external sites.
