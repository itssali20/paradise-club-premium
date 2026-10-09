# Paradise Club · Elite Vacations (Premium cinematic design)

Static site: one `index.html`, GSAP + ScrollTrigger + Lenis. No build step.

## See it live in 1 minute (with all videos playing)
- Quick preview link: go to https://app.netlify.com/drop and drag this folder onto the page.
- Production: push the folder to GitHub → vercel.com/new → import → Framework preset **Other** → Deploy.
- Or simply double-click `index.html` to open it in Chrome.

## Media used
- **Videos:** Mixkit free stock footage (free licence, commercial use OK, no attribution required):
  turquoise aerials, scuba, snorkeling, coral reefs with tropical fish, wakeboarding/water skiing, jet ski,
  parasailing, horseback at sunset, beach dancing, couples at sunset. Loaded from assets.mixkit.co.
- **Photos:** Unsplash (free licence): beach volleyball, all 16 destinations, pageant, runway, tango,
  villas, yacht. Loaded from images.unsplash.com.
- **The club's own:** 46 photos + logo from the Wix site (gallery), 19 YouTube films (films section),
  phone 1-877-677-7795.
- Before launch, it's best to download the chosen videos/photos into `/media` so the site doesn't depend
  on other hosts. Swap any clip by changing `data-mx="ID"` (Mixkit id) or `data-un="ID"` (Unsplash id).

## Before going live
- **Form:** set `data-endpoint` on `<form id="applyForm">` to a Formspree/Getform URL.
  Without it the form only shows a thank-you message and sends nothing.
- Prices aren't in the brief, so packages say "Request pricing".
