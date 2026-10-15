# James Vandermost Professional Website

A static professional website highlighting conversational AI leadership and enterprise delivery. Includes responsive layouts, optional animation, and a downloadable resume.

## Cloudflare Pages deployment

Connect this repository in Cloudflare Workers & Pages, selecting Pages and importing an existing Git repository.

- Framework preset: None
- Production branch: main
- Build command: `exit 0`
- Build output directory: `public`
- Root directory: leave at repository root

No environment variables, packages, server, or paid services are required.

## Local preview

Run `python -m http.server 4173 --directory public` from this directory, then visit http://localhost:4173.

## Editing

The page content, theme overrides, and animation behavior are in `public/index.html`. Base styles are in `public/styles.css`. Replace `public/resume.pdf` to update the resume.

After the final public URL is assigned, add a canonical link and an `og:url` meta tag with that URL. A custom domain can be connected through the Pages project settings.
