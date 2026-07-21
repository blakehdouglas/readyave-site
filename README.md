# Ready Ave website

This is a simple one-page site designed to be easy to update.

## Update the content

Open `content.js` in any text editor. Nearly all text, links, release details,
and the hero image path are controlled there.

## Add images

1. Put the finished cover or band photo in the `images` folder.
2. Name it `cover.jpg`, or change `heroImage` in `content.js`.
3. A landscape image will work, but a portrait or square image will fit best.

## Add Bandcamp

On Bandcamp, open the release page, choose Share / Embed, copy the iframe code,
and paste it between the backticks after `embedHtml` in `content.js`.

## Publish it

Easy options:

- Carrd: rebuild the layout there for visual editing.
- Netlify Drop: drag this whole folder into Netlify for free hosting.
- GitHub Pages or Cloudflare Pages: connect the folder/repository.
- Any ordinary web host: upload all files to the public web directory.

## Domain

Register the domain separately, then point its DNS to the hosting provider.
Do not pay for email hosting unless you need a real inbox; forwarding
`hello@readyave.com` to your normal email is often enough.
