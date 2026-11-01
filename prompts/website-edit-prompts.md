# AI prompts for website editing

## Make one focused change
"Review the existing index.html in this repository before editing. Make only this change: [describe the change]. Preserve the current visual identity, responsive behavior, existing sections, links, and working functionality. Do not rewrite the entire site. Do not invent business details. Tell me exactly which files you changed and how I can preview the result."

## Replace an image
"Find the existing image used for [section]. Replace only that image with assets/images/[exact-folder]/[exact-filename]. Keep the current crop behavior, layout, and mobile responsiveness. Do not change any other content."

## Edit text
"Update only the [section name] copy using content/site-copy.md (or the relevant content file). Preserve the existing styling and layout. Do not invent prices, contact details, testimonials, or client claims."

## Add a portfolio project
"Add one portfolio item for [project]. Use the image at [path] and video URL [URL if available]. Match the existing portfolio card design and mobile layout. Do not change other projects."

## Before committing
"Check for broken image paths, missing links, mobile overflow, and console errors. Summarize the changes. Do not publish or merge without showing me the preview first."
