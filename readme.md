# RaiseFunders — Landing Page Website

## Project Overview
A complete multi-page static landing website for **RaiseFunders**, an outsourced sponsorship and fundraising partner built specifically for youth athletic organizations. Based in Minneapolis, MN.

**Brand Colors:**
- Flamingo Green Light: `#6BBF3F`
- Flamingo Green Dark: `#2D6B1A`
- Navy Night: `#0D1B2A`
- Black: `#000000` | White: `#FFFFFF` | Cool Gray: `#808080`

**Typography:** Montserrat (headings, 700/800/900) + Open Sans (body, 400/600)

---

## Completed Features

### Pages Built
| Page | File | Purpose |
|------|------|---------|
| Homepage | `index.html` | Hero, problem, process, why us, economics, assets, FAQ preview, CTA |
| How It Works | `how-it-works.html` | Detailed 4-phase process with responsibilities |
| Who We Help | `who-we-help.html` | Audience segments, pain points, not-a-fit section |
| About | `about.html` | Origin story, team, philosophy, differentiators |
| FAQ | `faq.html` | Full accordion FAQ by category |
| Book a Call | `book-a-call.html` | Google Calendar scheduling embed + backup form |
| Contact | `contact.html` | Tabbed form: asset assessment + general contact |
| Thank You | `thank-you.html` | Post-submission confirmation page |
| 404 | `404.html` | Not found page with helpful navigation links |
| Privacy Policy | `privacy.html` | Full privacy policy for MN-based business |
| Terms of Service | `terms.html` | Full terms of service |

### Shared Assets
- `css/style.css` — Complete design system (variables, components, layout, responsive)
- `js/main.js` — Navigation, mobile menu, FAQ accordion, scroll-reveal, counter animations, form handling

### Key Features Implemented
- ✅ Fixed responsive navigation with mobile hamburger menu
- ✅ Hero section with stats card visual, proof bar
- ✅ Problem section (6 pain-point cards)
- ✅ 4-step process (numbered, connected visual)
- ✅ Before/After economics comparison block
- ✅ Asset grid (8 sponsor-ready asset types)
- ✅ FAQ accordion (collapsible, keyboard accessible)
- ✅ Scroll-reveal animations via IntersectionObserver
- ✅ Animated stat counters
- ✅ Tabbed contact form (Assessment + General)
- ✅ Full brand color system and typography via Google Fonts CDN
- ✅ Font Awesome 6 icons throughout
- ✅ Mobile-first responsive layout (breakpoints: 1024px, 768px, 480px)
- ✅ SEO meta tags on all pages
- ✅ Semantic HTML5 throughout (header, nav, main, section, article, aside, footer)
- ✅ Accessibility: ARIA labels, roles, skip links, proper heading hierarchy
- ✅ Sticky nav with scroll shadow
- ✅ Active nav link detection by current page
- ✅ Animated thank-you page with step-by-step next actions
- ✅ CTA repetition every 2–3 sections per strategy brief

---

## Navigation Structure

**Primary Navigation:**
- Home (`index.html`)
- How It Works (`how-it-works.html`)
- Who We Help (`who-we-help.html`)
- About (`about.html`)
- FAQ (`faq.html`)
- Book a Call (`book-a-call.html`) — button CTA

**Secondary:**
- Contact / Asset Assessment (`contact.html`)

**Utility Pages:**
- Thank You (`thank-you.html`)
- 404 (`404.html`)
- Privacy Policy (`privacy.html`)
- Terms of Service (`terms.html`)

---

## Primary Conversion Goals (per Strategy Brief)
1. **Book a Free Discovery Call** — Primary CTA on every page
2. **Get a Free Asset Assessment** — Secondary CTA via contact form

---

## Recommended Next Steps

### Immediate (before launch)
1. **Activate Google Calendar booking** on `book-a-call.html` — go to Google Calendar → Settings → "Appointment schedules", create a 30-min schedule, then replace `YOUR-GOOGLE-BOOKING-LINK` in the iframe `src` with your real booking URL
2. **Update contact email** — replace `hello@raisefunders.com` with real inbox
3. **Logo** — Updated to new flamingo/dollar-bird SVG logo matching brand identity (green bird with wings + "raise" in green / "funders" in black bubble font)
4. **Add favicon** — link a `.ico` or `.png` favicon in all `<head>` sections

### Growth Features (post-launch)
5. **Connect forms to a backend** — integrate with Netlify Forms, Formspree, or similar service to actually capture submissions
6. **Add Google Analytics / tracking** — add GA4 tag to all pages for conversion tracking
7. **Add testimonials section** — currently has CSS support; add real client quotes when available
8. **SEO content expansion** — add blog/resources section targeting keywords like "youth sports sponsorship", "youth club fundraising"
9. **Add Open Graph / social meta tags** — for LinkedIn and social sharing previews
10. **Minneapolis location page** — local SEO page targeting MN/Twin Cities youth sports clubs

---

## File Structure
```
/
├── index.html              ← Homepage
├── how-it-works.html
├── who-we-help.html
├── about.html
├── faq.html
├── book-a-call.html
├── contact.html
├── thank-you.html
├── 404.html
├── privacy.html
├── terms.html
├── css/
│   └── style.css           ← Full design system
├── js/
│   └── main.js             ← All interactivity
└── images/
    ├── logo-wordmark-light.svg  ← Nav logo (flamingo/dollar bird, light bg)
    ├── logo-wordmark-dark.svg   ← Footer logo (flamingo/dollar bird, dark bg)
    └── (sport photo images)
```

---

## Technology Stack
- Pure HTML5, CSS3, Vanilla JavaScript (no build tools required)
- Google Fonts CDN (Montserrat + Open Sans)
- Font Awesome 6.5.0 CDN (icons)
- No frameworks, no dependencies — fully static

## Deployment
Deploy via the **Publish tab**. The site is fully static and works on Netlify, Vercel, GitHub Pages, or any static host.
