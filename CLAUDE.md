# Shanghai Sangamam — Project Bible for Claude Code

## Project identity

- **Brand name**: Shanghai Sangamam
- **Domain**: www.shanghaisangamam.com (registered on Hostinger)
- **Tagline**: *Connecting Tamil hearts across China* 🌏❤️
- **Mission**: A digital home for the Tamil-speaking Indian community in Shanghai — celebrating culture, enabling connection, and making life easier for every Tamil living in China.
- **Language**: Primary English, secondary Tamil (தமிழ்) where appropriate
- **Tone**: Warm, welcoming, community-first. Never corporate. Think neighbour, not brand.

---

## Who this is for

Tamil-speaking Indians living in Shanghai (and broader China). Mix of IT professionals,
business people, students, spouses, and families. They want:
- Community events and meetups
- Cultural celebrations (Pongal, Diwali, Tamil New Year etc.)
- Practical help settling into Shanghai life
- Business networking within the community
- A space that feels like home away from home

---

## Website

### Hosting & platform
- **Domain**: shanghaisangamam.com (Hostinger — for DNS only, no hosting needed there)
- **Hosting**: Render (paid plan, already active ✅)
- **Code repo**: GitHub (already active ✅)
- **Tech stack**: Plain HTML5 + CSS3 + vanilla JavaScript — no framework, no build step
- **Deploy flow**: Push to GitHub → Render auto-deploys (same as other projects)
- **DNS**: Point shanghaisangamam.com CNAME from Hostinger → Render custom domain
- **CMS**: None — Claude Code handles all content updates quickly
- **WordPress**: Not used — unnecessary cost, HTML/JS is sufficient

### Why HTML/JS (not WordPress)
- Render + GitHub already paid and working — zero extra cost
- Updates are monthly/festival-based — Claude Code can update HTML files in minutes
- No extra hosting bill, no plugin maintenance, no security patches
- Same proven workflow as valUProp and sourcercn.com

### Pages to build
1. **Home** (index.html) — Hero banner, tagline, upcoming events preview, social links
2. **About** (pages/about.html) — Who we are, our story, committee members
3. **Events** (pages/events.html) — Upcoming and past events, photo gallery
4. **Community** (pages/community.html) — Member info, WhatsApp group links
5. **Contact** (pages/contact.html) — Contact form, social media links

### Design direction
- Colours: Saffron orange + deep green (Indian flag inspired) with white/cream backgrounds
- Tamil script (தமிழ்) used decoratively in hero and section headings
- Fonts: Google Fonts — Poppins (headings) + Noto Sans Tamil (Tamil text)
- Feel: Festive but clean. Think temple gopuram meets modern web.
- Mobile-first — most community members browse on phones

---

## Social media accounts

### Instagram
- **Handle**: @shanghaisangamam (register this)
- **Content**: Event photos, reels of cultural moments, Tamil quotes, Shanghai life tips
- **Post frequency**: 3–4x per week
- **Templates folder**: social-media/instagram/

### Facebook
- **Page name**: Shanghai Sangamam
- **Content**: Event announcements, longer posts, photo albums, community polls
- **Post frequency**: 2–3x per week
- **Templates folder**: social-media/facebook/

### YouTube
- **Channel name**: Shanghai Sangamam
- **Content**: Event highlights, vlogs, community interviews, cultural videos
- **Post frequency**: 2x per month to start
- **Templates folder**: social-media/youtube/

---

## Content pillars (for all channels)

1. 🎉 **Events** — Meetups, celebrations, Tamil cultural events in Shanghai
2. 🏮 **Shanghai Life** — Tips, recommendations, expat hacks for Tamil community
3. 🤝 **Community Spotlights** — Member stories, introductions, achievements
4. 🍛 **Food & Culture** — Tamil food finds in Shanghai, recipes, restaurant tips
5. 📣 **Announcements** — New members welcome, important community news

---

## Brand voice

- Speak like a warm community leader, not a marketer
- Use Tamil words naturally where they add warmth (anna, akka, vanakkam, etc.)
- Emojis welcome — especially 🌏❤️🎉🏮🍛
- Short and punchy for social, slightly longer for website copy
- Always inclusive — this is for ALL Tamil speakers regardless of background

---

## Folder structure

```
shanghai-sangamam/
├── CLAUDE.md                        ← project bible (you are here)
├── README.md
├── .gitignore
├── index.html                       ← home page
├── style.css                        ← global styles
├── script.js                        ← global scripts
├── pages/
│   ├── about.html
│   ├── events.html
│   ├── community.html
│   └── contact.html
├── components/
│   ├── header.html
│   ├── footer.html
│   └── nav.html
├── assets/
│   ├── logo/
│   ├── images/
│   ├── banners/
│   └── videos/
├── social-media/
│   ├── instagram/
│   ├── facebook/
│   ├── youtube/
│   ├── captions/                    ← saved as YYYY-MM-DD-title.md
│   └── content-calendar/
└── docs/
    ├── brand-guide.md
    ├── social-strategy.md
    ├── event-templates/
    └── copy-bank.md                 ← reusable captions, taglines, bios
```

---

## Key contacts & context

- **Project owner**: Thiaga (Shanghai-based, Tamil community leader)
- **Related projects** (completely separate — do NOT mix):
  - valuprop.in — Indian property valuation web app (Flask + Render + GitHub)
  - sourcercn.com — China-India sourcing business site (Render + GitHub)

---

## Claude Code working rules

1. Always keep this project in its own folder — never mix with valuprop or sourcercn
2. Website files live at root and in pages/ — plain HTML, no framework
3. When adding new events or festival updates, edit pages/events.html directly
4. Social media captions go in social-media/captions/ with date prefix (YYYY-MM-DD-title.md)
5. All assets go in assets/ folder
6. Never put passwords, API keys, or credentials in any file
7. Default language: English. Add Tamil where specified.
8. Mobile-first always — most community members browse on phones
9. Keep it simple — no npm, no build tools, no frameworks unless absolutely necessary

---

## First tasks (priority order)

- [ ] Create GitHub repo: shanghai-sangamam
- [ ] Connect repo to Render (static site)
- [ ] Point shanghaisangamam.com DNS from Hostinger to Render
- [ ] Build index.html with hero, tagline, and social links
- [ ] Build pages: About, Events, Community, Contact
- [ ] Design logo — save to assets/logo/
- [ ] Register social media handles (Instagram, Facebook, YouTube)
- [ ] Write first month content calendar
