# HydroClean Website

**A six-page website for Townsend's HydroClean, an exterior cleaning company in Delaware. It was my first coding project and the first code I ever wrote.**

I built it in my senior year of high school (January to March 2021) for a real client. I worked directly with the owner and was responsible for the whole project: talking with him to work out what the site needed, deciding what to build, and building and delivering it. I wrote all of it by hand, on my own, learning HTML, CSS and JavaScript from W3Schools and web searches as I went. It's where my path into software engineering started.

## Pages

| Page | What it covers |
|---|---|
| **Home** (`Index.html`) | The company's pitch: soft washing services, why regular exterior cleaning protects a home, the eco-friendly process, and a photo gallery |
| **Services** (`Services.html`) | The nine services offered, a larger photo gallery, and the estimate form |
| **Estimates** (`Estimates.html`) | An embedded Google Form for requesting a free, personalized estimate |
| **FAQs** (`FAQs.html`) | Why HydroClean, why soft washing instead of pressure washing, links to socials and review pages |
| **Community** (`Community.html`) | A thank-you to local customers and the company's planned community service work |
| **Contact** (`Contact us.html`) | Click-to-call, email, the estimate form, the Google Business page and social links |

Every page shares the same header with the logo and navigation, and the same footer with service areas and hours.

## Features

- **Photo lightbox** (`Script.js`): click any gallery photo to open it full-size over a dimmed page, and click outside it to close. Written in plain JavaScript with DOM event listeners.
- **Animated navigation:** a bar slides in under each link on hover, using a CSS transition on a `::before` element.
- **Embedded estimate form:** customers request quotes through a Google Form inside the page, so the owner gets requests without needing a back end.
- **Click-to-call and email links** (`tel:` and `mailto:`), plus links to the company's Facebook, Instagram, TikTok and Google Business pages.

## Tech stack

- **HTML** for the six pages
- **CSS** in one shared stylesheet (`Style.css`)
- **JavaScript** for the lightbox (`Script.js`)

No frameworks, libraries or build tools.

## Running locally

Open `Index.html` in a browser. There's nothing to install.

The client's photos and logo aren't in this repository. The pages load them from an `images/` folder that sat next to the project folder, so they show up as broken images here.

## Repository structure

```
├── Index.html          # Home
├── Services.html       # Services and gallery
├── Estimates.html      # Estimate request form
├── FAQs.html           # FAQs, socials and reviews
├── Community.html      # Community page
├── Contact us.html     # Contact details
├── Style.css           # Shared styles
└── Script.js           # Photo lightbox
```

## Looking back

The code is kept as I wrote it in 2021. Knowing what I know now, I'd do a few things differently:

- Use semantic tags and classes instead of the made-up tags (`<p1>` to `<p7>`) and the deprecated `<center>` I styled the text with
- Build a responsive layout with flexbox or grid instead of fixed pixel widths
- Add `alt` text to every image
- Use consistent, lowercase file names without spaces and forward-slash paths: links point to `index.html` while the file is `Index.html`, which breaks on case-sensitive servers
- Share the header and footer through a template or component instead of copying them into every page

It still did its job, and building it taught me how to learn a technology from scratch, work with a client and deliver a finished product.

## Author

**[Kyle Tranfaglia](https://github.com/ktranfaglia1)**
