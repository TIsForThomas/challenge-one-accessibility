# challenge-one-accessibility

#### By Stephen "Thomas" Nelson

## What is it?

For my first challenge, I was tasked with updating an existing website to be more accessible to screen readers.

## Why update it?

Accessibility is important! By building a website to be more accessible, you can provide context AND content for those who need it. Websites nowadays need to be for both eyes AND ears.

## Semantic vs non-semantic

What's a semantic element? 

A semantic element describes its meaning to both developers AND the browser. A non-semantic element on really has meaning to the developer or developers that created it. In html we have certain semantic tags we can put things on our page into that allow the browser to read them out to a sceen reader.
Examples of semantic vs non-semantic tags:
- Non-semantic elements include: `<div>` and `<span>`.
- Semantic elements include:`<header>`, `<footer>`, `<nav>`, and `<section>`.

## What changed?

Divs divs divs! Whats wrong with those? They have no context! Why do we need context? Because our website isn't just one paragraph! I ended up adding more context to those divs by adding specific semantic tags to places on the page that would be benifited by having them. Another thing I added where tags to images that would described the image is to someone who was using a screen reader.

## What changed (specifically)?

While I did end up still including most of the divs on the page (screen readers can't read them anyway), any area that needed it I added those specific tags to the page. 
For example, on this website, you can see we have a header (which included a navigation bar), a section of content, an asside bar, and a footer. I added all those tags to those areas:
- `<header>` for the header section.
- `<nav>` for the navigation bar located in the header section.
- `<section>` for the main section of the page.
- `<asside>` for asside bar located on the page.
- `<footer>` for the footer of the page.
For the images I added `<alt="what the image is">` tags which describe the image to the browser so it can relay that information to the screen reader.
Example: `<img alt="social media marketing table" src="./assets/images/social-media-marketing.jpg">`