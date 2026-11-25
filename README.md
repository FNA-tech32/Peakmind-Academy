# Peakmind Academy

Static one-page site for Peakmind Academy. Visitors can read about the coach, browse health topics, open the training-plan ebook, review client stories, and get in touch.

## Contact

The previous Facebook and Instagram profiles have been replaced with:

- Email: [hello@peakmindacademy.com](mailto:hello@peakmindacademy.com)
- Phone: [+1 (415) 555-0148](tel:+14155550148)

Those details appear in the header, the side links, and the contact section.

## Sections

- **Home** — intro and a link to contact
- **About** — short about section
- **Health** — tabs for nutrition, training, and sleep
- **Training plan** — ebook download (`assets/training plan/training-plan.pdf`)
- **Clients** — client slider fed by `assets/data/data.js`
- **Contact** — email and phone

## Run locally

Open `index.html` in a browser. No build step is required for the page itself.

Styles are written in Sass and already compiled to `css/stylesheet.css`. To watch Sass while editing:

```bash
npm install
npm run compile:sass
```

That script uses `node-sass` and rewrites `css/stylesheet.css` when files in `sass/` change.

## Project structure

```text
index.html          Page markup
script.js           Nav, smooth scroll, year, and health tabs
slider.js           Client slider
assets/             Images, ebook, and slider data
css/stylesheet.css  Compiled styles
sass/               Sass source
```

## Branch

Work for this project is on the `Peakmind-Academy` branch. Git does not allow spaces in branch names, so the project name is written with a hyphen.
