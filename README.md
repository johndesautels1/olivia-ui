# Olivia UI – AI Concierge Chat Interface

This repository contains the front-end interface for Olivia, the AI relocation concierge for John E. Desautels & Associates and the CLUES relocation platform.

## Features

- Connects to Olivia (ChatGPT-powered assistant)
- Uses D-ID video avatar to deliver personalized video responses
- Static `index.html` embeddable in Wix via iframe
- Designed for use within the CLUES members-only dashboard

## Deployment

This project is deployed using [Vercel](https://vercel.com). No build step is required — it's a static site with one `index.html` file.

## Usage

To embed Olivia into a website:

```html
<iframe
  src="https://your-vercel-url.vercel.app"
  width="100%"
  height="600"
  style="border:none; max-width:800px;"
  allow="autoplay; encrypted-media">
</iframe>
