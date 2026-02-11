# Rabbit Hole Solutions — Website Project Brief

## Domain
**rabbitholesolutions.ca** (currently on Google Workspace via domain partner)

## Logo
- File: `inverted.png` (included alongside this brief)
- Design: High-contrast black & white. Circle containing a rabbit silhouette made of circles (head, body) with two long pointed ears — one straight, one bent/kinked at the tip. Single dark eye. Hand-drawn circle border with slight organic imperfection.
- Renders well at small sizes (GitHub avatar, email icon, favicon)
- Key property: Works extremely well as img2img / ControlNet input for SDXL pipelines — the high contrast silhouette produces recognizable branded imagery across wildly different scenes (the ears especially become a recurring visual motif)

## Company Overview
**Rabbit Hole Solutions Inc.** is a one-person indie software studio run by Jason, a 48-year-old senior freelance technologist (former CTO/CISO at multi-billion revenue companies) based in New Westminster, BC. The company builds niche tools for deep nerd communities — VR productivity apps, AI image generation tools, developer utilities, and eventually games.

## Business Strategy
- Build ~20 niche tools over 6 months serving specific technical communities (VR users, SDXL/AI image gen community, developers, etc.)
- Most tools are open source with optional paid builds (e.g., $5 Quest native builds with bonus features)
- Revenue per tool is tiny (~$250 each) but that's not the point
- The portfolio builds brand recognition and trust across overlapping nerd communities
- When bigger projects ship (e.g., a game), there's a warm audience and established credibility
- Philosophy: "one of us shipped something bigger" rather than "some company wants my money"

## Current/Planned Tools
(Populate with real names as available — these are known from conversation context):
1. **VR SSH Client** — SSH client for Meta Quest 3
2. **Image Viewer/Tagger** — For SDXL community; image organization, tagging for model tuning. Will be on npm as open source, with a $5 Quest native build
3. **More to come** — ~20 total planned across various niche developer/creator communities

## Website Requirements

### Tone & Style
- **Bold and playful** — lean into the rabbit hole theme
- Not corporate, not trying to look bigger than it is
- Confident indie studio energy — a skilled nerd building tools for other nerds
- The rabbit hole metaphor should be present but not overdone

### Visual Concept
- Dark theme (matches the logo's black background)
- The logo's silhouette should be a recurring visual motif
- Background concept: AI-generated images that all embed the logo shape in different real-world scenes (e.g., a woman at a pottery studio where cast light forms the rabbit ears over her head). These would be generated via SDXL img2img/ControlNet from the logo. **For the initial build, use placeholder areas or subtle CSS/SVG treatments that echo the logo shape** — Jason will generate the actual AI images separately
- High contrast, clean typography

### Pages/Sections
1. **Hero/Landing** — Logo, company name, tagline, immediate sense of what this is
2. **About** — Who is behind this, the philosophy (niche tools, fair pricing, open source ethos)
3. **Tools/Portfolio** — Grid or list of shipped tools with links (GitHub, npm, Quest store). Should be easy to add new entries as tools ship
4. **Contact** — Simple contact info or form

### Technical Notes
- Static site is fine (this will be hosted simply)
- Should be a single HTML file or minimal static site that's easy to deploy
- Make it easy to add new tools to the portfolio (clear data structure or simple HTML pattern)
- Favicon from the logo
- Mobile responsive

## Assets Available
- `inverted.png` — The logo (white on black, high-res)
- Domain: rabbitholesolutions.ca

## Next Steps
- Build the site using this brief
- Jason will generate AI images from the logo for the background/hero treatment
- Populate tool listings as they ship
- Point domain DNS to hosting
