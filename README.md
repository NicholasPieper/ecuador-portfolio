# Stas & Nick — Mountain & Expedition Portfolio

Bare-bones portfolio page for the Higher Earth Ecuador expedition photographer/videographer role (Cotopaxi & Cayambe, 12–25 Nov 2026; applications close 5 Nov 2026).

Plain static HTML: no build step, no dependencies. Videos are embedded from YouTube and TikTok and listed in the `VIDEOS` array at the bottom of `index.html`, so adding, removing or reordering a video is a one-line edit.

## Publish on GitHub Pages

```bash
cd ecuador-expedition-portfolio
git init && git add . && git commit -m "Ecuador expedition portfolio"
git branch -M main
git remote add origin https://github.com/<your-account>/<repo-name>.git
git push -u origin main
```

Then in the repo: **Settings → Pages → Source: Deploy from a branch → main / (root)**. The site will be at `https://<your-account>.github.io/<repo-name>/`.

## How videos were picked (stats pulled 29 Oct 2026)

Each piece is cross-posted, so the platform version with the most views was used across YouTube and TikTok. Instagram was not compared (logged out, it only shows the 12 newest reels); the one Instagram embed is the Mt. Whitney reel, included by request.

| Section | Video | Platform used | Views | Other platform |
|---|---|---|---|---|
| Mountains | Highest to Lowest: Whitney ski + bike (long-form) | YouTube | 90 | — |
| Mountains | Ski trip to the French Alps (long-form) | YouTube | 498 | — |
| Mountains | Mt. Whitney summit → Badwater (short) | Instagram (by request) | 364 likes, 16 comments | TikTok 5,918 views, 386 likes |
| Mountains | Glacier pumptrack, French Alps | TikTok | 4,856 | YT Short 3,365 |
| Mountains | Alpine lakes, San Juan Mountains | YouTube Short | 38,965 | TikTok 5,170 |
| Remote | Kyrgyzstan: yurts, horseback trekking, Lenin Peak (long-form) | YouTube | 14,454 (417 likes) | — |
| Remote | Horseback trekking & high lakes, Kyrgyzstan | TikTok | 15.7K | — |
| Remote | Kyrgyzstan honeymoon road trip | TikTok | 10.8K | — |
| Remote | Dagestan, Caucasus | TikTok | 11.9K | — |
| Volcanoes | Karymsky volcano & Valley of Geysers, Kamchatka | TikTok | 616.7K (52.7K likes) | YT Short ~6.3K |
| Volcanoes | Kamchatka volcanoes / heli touring | TikTok | 277.8K (12.8K likes) | YT Short 16.0K |

Stills (`assets/stills/`) were converted from the original CR2/HEIC files to JPG, max 2400 px on the long edge.

## Before sending

- The posting asks for **one camera person**. Adjust the hero/team copy if only one of you is applying.
- The application email also needs one line on climbing/altitude experience and your camera kit; the kit list on the page is copied from the Natural Selection Tour portfolio, so confirm it's current.
