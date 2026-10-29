# Filip Pielecki's portfolio

Personal portfolio presented as an interactive handheld console, with projects, an illustrated technology game catalogue, an About section, and contact links.

Live site: https://fp2003.github.io/

## Local preview

Open `index.html` in a browser, or serve this folder with:

```sh
python -m http.server 4173 --bind 127.0.0.1
```

Then visit http://127.0.0.1:4173/.

## Editing

The `DATA` object near the top of `index.html` contains the biography, project entries, technology list, and contact links. Styling and interaction code live in the same file. No build step or package installation is required.

Three.js loads from jsDelivr and fonts load from Google Fonts. The portfolio content remains available if the 3D renderer cannot initialise. The CV is not included; visitors can contact me through LinkedIn or email.

## Deployment

GitHub Pages serves the root of the `main` branch. Push changes to `main` to publish an update. `.nojekyll` keeps the site as plain static files.

Section URLs such as `/#projects`, `/#stack`, and `/#contact` can be shared directly.
