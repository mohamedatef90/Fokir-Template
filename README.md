# Fokir Template

A static, single-page personal portfolio template: a hero with a name and slider image, about, services, portfolio, client feedback, blog, and a footer with a form. It is plain HTML and CSS with no build step and no JavaScript.

## Sections of `index.html`

- Hero ("Hello i'm ...")
- About
- Services (UI/UX design, app development, product design) and counters
- Portfolio (six images)
- Client feedback
- Blog
- Footer with a form

The page is a template: it uses placeholder text and sample images from `img/`.

## Files

```
index.html          The page
css/style.css       Main styles
css/responsive.css  Responsive rules
css/all.min.css     Font Awesome styles (webfonts/ holds the icon fonts)
img/                Slider, about, portfolio, blog, and testimonial images
```

Fonts (Roboto and Source Sans Pro) load from Google Fonts.

## Running

`index.html` currently links its stylesheets as `../Fokir.com/css/style.css`, `../Fokir.com/css/all.min.css`, and `../Fokir.com/css/responsive.css`, so it expects to sit in a sibling folder named `Fokir.com`. To open the page from this repository as it is, change those three `href` values to `css/style.css`, `css/all.min.css`, and `css/responsive.css`, then open `index.html` in a browser.
