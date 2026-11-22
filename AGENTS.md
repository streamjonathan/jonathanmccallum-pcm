# AGENTS.md — jonathanmccallum-pcm (Nigerian Pidgin mirror of jonathanmccallum.com)

Nigerian Pidgin mirror site. Same theme and design as the main site (Paper Light),
content translated into Nigerian Pidgin, meaning-first. Repo: streamjonathan/jonathanmccallum-pcm.
Live (when approved): pcm.jonathanmccallum.com. Proof: jonathanmccallum-pcm.pages.dev.

## Mission

Mirror jonathanmccallum.com in Nigerian Pidgin — every article translated for meaning,
not word for word, in Jonathan's voice: plain short sentences, friendly, positive,
never preachy. An average person interested in Jesus, not an expert or theologian.

## Roles

- **Bobby (Muse) is the lead builder.** He coordinates, builds, pushes to GitHub
  and deploys to Cloudflare. He is the ONLY one who pushes or deploys.
- **Claude advises and reviews** translation quality. He does not push or deploy.
- **Helper Muses translate** one article at a time, drafts only.

## The one rule above all

**Never publish or alter live production assets without Jonathan's clear
permission.** The Nigerian Pidgin site goes live on pcm.jonathanmccallum.com only when
he says so, after reading the pilot article(s). Drafts stay drafts until he
approves them. Work on a branch, never straight on main. Give Bobby a preview URL.

## Translation rules

- English repo (streamjonathan.github.io) is the source of truth. Articles are
  translated from the English Markdown, keeping the same date, slug, source_video
  and shareImage. Only the title and body are translated.
- Lewis quotations: use the published Nigerian Pidgin translation where one exists
  (cite it); otherwise translate fresh and mark it "translated for this site".
- Bible verses: use a published Nigerian Pidgin Bible translation where one exists (cite it); otherwise translate fresh and mark it "translated for this site".
- Names (never vary): Narnia proper nouns stay in English: Narnia, Aslan, Cair Paravel, White Witch, Lucy, Digory, Tirian, Adam and Eve. Book titles stay in English. Names stay as they are: Jesus, God, Christ, Peter, Lewis.
- Voice: Everyday spoken Nigerian Pidgin — na / wey / dey / don / go / make / e / dem / oda. Short sentences, plain, warm, honest. No preaching. Reader addressed as "you".
- No emojis, no newsletter form, no links the English article does not have.
- Never invent facts, dates, links or details.

## Site facts

- Eleventy 3, Cloudflare Pages, Paper Light theme (Fraunces + Newsreader).
- No Ask chat and no note Worker on this site yet — search (Pagefind) works,
  Ask and notes come later. The Ask floating button and ask.js are removed.
- CSS is preloaded, not inlined (CSP blocks inline style). Bump the `?v=` query
  on any CSS/JS file you change.
