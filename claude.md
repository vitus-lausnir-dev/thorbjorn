Background

I did couple of months ago demo for Oskar owner of Thorbjörn  (Þorbjörninn)

Just got feedback from hims. I will paste that document into the chat.
Important. I Wanna keep a much as possible current look and feel. That is the first demo. 
Somehow merge my first webpage with his feedback that just came now in a word document.
2 Main points from him.
1. Just english version
2. product oritented focus instead of "mine" history and who are we focus.

## Project overview

Static single-page English site (`index.html`, inline CSS/JS, no build step) for Þorbjörn ehf / Thorfish, Grindavík. Live at https://vitus-lausnir-dev.github.io/thorbjorn/ (GitHub Pages from `main`, ~1–2 min deploy). Repo: github.com/vitus-lausnir-dev/thorbjorn.

Images live in folders next to `index.html` (`Fish illustrations/`, `History pictures/`, `Product pictures/`, `Ship Pictures/`, `Logos/`) and must be deployed with it.

## Page structure

Hero (old GK 255 photo) → Our products (carton gallery) → five species cards → Frozen at sea → "Find the right product" spec table → "Seafood from Iceland" logo → Contact ("Orders and enquiries") → footer.

## Decisions / rules

- Keep the first demo's look and feel (colours, reveal animations). Headings now use Hanken Grotesk (same as body); the earlier Fraunces serif was dropped because it looked AI-made.
- Customer-supplied wording is not to be changed without asking. The hero headline "Icelandic seafood. A tradition carried forward." stays as is.
- Header/footer logo is the Thorfish-only lockup (waves + "Thorfish", `Logos/thorfish-logo-horizontal.png`). Óskar said the Þorbjörn logo cannot be shown together with the waves (legal issue).
- All contact uses sales@thorbjorn.is (contact button and footer).
- Only product-focused content; history, sustainability and timeline sections were removed. The old GK 255 photo stays in the hero (customer wish).
- Untracked on purpose: `customer feedback/`, unused source logos in `Logos/`, unused Ship Pictures.

## Status (2026-10-23)

Latest commit pushed to `origin/main`; site is ready for Óskar's review apart from the open items.

## Open items

- Check mobile layout (logo size, hero headline wrap).
- Ask Óskar: does the Þorbjörn legal concern also cover the name in text? It still appears in the page title, hero eyebrow and lede, the "Behind every box" sentence and the footer copyright.
- Footer still shows "thorfish.is" as a website name; decide whether to change to thorbjorn.is.
- Confirm address and phone (Hafnargata 12, +354 420 4400) with Óskar.
- Redfish card says Sebastes norvegicus; his table lists mentella and marinus/norvegicus.
- Hero photo is only 1149px wide; ask for a higher-res scan.
- `Product pictures/Stacked Blue Thorfish Cartons.png` is 1.9 MB and could be compressed.
