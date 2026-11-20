# theKatosphere website

A static site: one `index.html` plus an `images` folder. No build step.

## Deploy to Vercel
1. Upload this folder to a GitHub repo (or drag it into vercel.com/new).
2. Framework preset: **Other**. Build command: leave blank. Output directory: leave blank.
3. Deploy, then add your domain under Project > Settings > Domains.

## Swap in your real content
Search `index.html` for these placeholders:
- `Your portrait here`: replace that div's text with `<img src="images/kat-portrait.jpg" alt="Kat Serrano">`
- `Photo:` (five rooms): replace each with an `<img src="images/...">` tag
- `mailto:hello@example.com`: your contact email
- `href="#"` on the Substack links and "Explore the books": your real links
- The three "Coming soon" essays: your real Sunday Kitchen Table posts

## Quezon font
Headlines use Quezon by Kimchi Lee (kimchilee.gumroad.com/l/CLqiG).
Put the font file in the `fonts` folder, named `Quezon.otf` (or `Quezon.ttf` / `Quezon.woff2`).
Until it's there, headlines fall back to Gloock.
Check the license that came with your download for website use.
