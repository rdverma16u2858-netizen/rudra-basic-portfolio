# Basic portfolio — HTML and CSS only

Open `index.html` in your browser. Edit `index.html` for the content and `style.css` for its appearance. No installation, build step or internet connection is required to view the page. External project, email and GitHub links need the appropriate service or app.

This is a separate, simplified version of Rudra's portfolio. The original portfolio and Student Portal assignment are unchanged. There is no JavaScript, Tailwind, Bootstrap, external font or image library.

## Explain it in your viva

“I made a single-page portfolio using HTML and an external CSS file. HTML creates the navigation, sections, project cards, lists and links. CSS adds colours, spacing, fonts and borders. I used Flexbox for the navigation and hero, Grid for the project cards, and media queries to stack columns on smaller screens.”

## HTML to understand

- `header` and `nav`: logo and navigation links.
- `main` and `section`: main content and individual topics.
- `h1`, `h2`, `h3`: page, section and project headings.
- `p`: descriptions and paragraphs.
- `article`: an individual project card.
- `div`: a general grouping container.
- `span`: a small piece of content within a group.
- `em`: emphasized words, styled green with a serif font.
- `ul` and `li`: skills, achievements and goals lists.
- `a href="#projects"`: jumps to the section with `id="projects"`.
- `input type="checkbox"`: native browser checkbox. It can be checked without JavaScript, but the page does not save completion or calculate progress.
- `label`: makes each goal's text clickable and names its checkbox.
- `footer`: the closing information.

## CSS to understand

```css
.project-info {
  padding: 24px;
}
```

`.project-info` is a class selector. `padding` is a property; `24px` is its value. A colon separates the property from the value, a semicolon ends the declaration, and braces group the declarations.

- `color` and `background-color`: text and surface colours.
- `margin` and `padding`: outside and inside spacing.
- `border` and `border-radius`: outlines and rounded corners.
- `font-family`, `font-size`, `line-height`: typography.
- `display: flex`: arranges items along a row or column.
- `display: grid` and `grid-template-columns`: create the project columns.
- `gap`: space between flex/grid items.
- `:hover`: styling while the pointer is over a link.
- `:focus-visible`: a visible outline for keyboard navigation.
- `@media`: styles applied at a particular viewport size.

## How the visuals work

The green introduction card, letter “r.” and four coloured project covers are ordinary HTML text and CSS backgrounds. They are not photos, screenshots or imported logos.

## What works without JavaScript

Navigation anchors, external links, email links, responsive layout, hover styles and native checkboxes. There are no filters, pop-up project notes, saved goals or scripted menus. Navigation links remain visible and wrap on narrow screens.

The first-year roadmap is a proposed plan, not a completed-achievements list.
