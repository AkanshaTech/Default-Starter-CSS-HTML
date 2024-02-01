# CSS Default Starter / Global Styles

- Save time on project setup.
- Less lines of CSS.

## Normalize

Small CSS file that provides cross-browser consistency in the default styling of HTML elements.

Alternative/Fancier way of doing this

    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    }

- Go to https://necolas.github.io/normalize.css/
- Select the latest version
- Create normalize.css
- Setup the link in the HTML

        <link rel="stylesheet" href="./normalize.css" />

## Fonts

### Select Fonts

- www.fontpair.co
- www.pagecloud.com

### Grab the CSS

- typescale
  Make some adjustments

## Colors

    :root {
    /* primary */
     /* grey */
    --black: #222;
     --white: #fff;
    --red-light: #f8d7da;
    --red-dark: #842029;
     --green-light: #d1e7dd;
     --green-dark: #0f5132;
    }

### Select Primary

#### Manual Approach

- https://coolors.co/
- https://www.happyhues.co/
- select your own color
- get shades https://noeldelgado.github.io/shadowlord/#73fdad

#### Library/Faster Approach

- https://getbootstrap.com/docs/5.0/customize/color/#color-sass-maps
- https://tailwindcss.com/docs/customizing-colors#color-palette-reference

#### Select Grey

- https://tailwindcss.com/docs/customizing-colors#color-palette-reference

#### Just go with happyhues

- https://www.happyhues.co/

### Box Shadow

- https://tailwindcss.com/docs/box-shadow
