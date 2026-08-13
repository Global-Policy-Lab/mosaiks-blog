# The MOSAIKS Blog

Source for [The MOSAIKS Blog](https://blog.mosaiks.org), a [Quarto](https://quarto.org) website built by the [Global Policy Lab](https://www.globalpolicy.science) at Stanford. The blog covers earth embeddings, earth observation, and novel ways to use satellite and sensor data — sharing research findings and updates from the MOSAIKS project more quickly than the formal publication process allows.

## Future ideas

A list of possible additions to consider:

**Content discovery / reach**
- **Email/newsletter signup** — the homepage has a Mailchimp-style subscribe widget (`subscribe.html`), but it's a placeholder: the form isn't wired to a real Mailchimp (or other) list yet, so submitting just links to `subscribe-placeholder.qmd`, a page noting that signups aren't live yet. Since this is a static GitHub Pages site with no backend, going live means embedding a real third-party service rather than building one. Common options: Buttondown (simple, RSS-to-email built in), ConvertKit, Substack, Mailchimp embed form. Mailchimp is covered in the Quarto documentation.

- **Social share previews (Open Graph / Twitter card tags)** — without these, links to posts shared on Slack/Twitter/LinkedIn show no image/description. Quarto supports this via a few `_quarto.yml`/front-matter fields (e.g. `image`, `twitter-card`, `open-graph`).
- **Analytics** — currently none configured. Options range from privacy-friendly/no-cookie-banner-needed (Plausible, GoatCounter, Fathom) to the free-but-heavier Google Analytics.

**Engagement**
- **Comments on posts** — e.g. Giscus (uses GitHub Discussions on the existing repo, free, no backend) or Utterances (GitHub Issues-based). Optional for a research blog — many choose not to have comments.
- **Author info per post** — bylines already show name/date; could add short author bios/photos, especially as more authors post.

**Polish / correctness**
- **License / citation info** — a short footer note or `LICENSE` file, useful since this blog discusses published research (how to cite posts, reuse of figures, etc.).
- **Performance** — Automatically compress any large images in post folders to speed up page loads.
- **Legal/contact basics** — a way to reach the team (email address or contact link) beyond the GitHub repo link.
