# Niche Kit Preview
Hyper-local niche CTA preview sites: private well testing (NH/ME), radon (Iowa), septic (rural VT), plus an evidence sheet.

## Go live
Each niche page has a config line near the bottom:
```js
var NK={affiliate:"",formEndpoint:"",phone:""};
```
- `affiliate`: partner/affiliate URL for the main button (empty = button scrolls to the quote form)
- `formEndpoint`: any form backend that accepts POST (e.g. Formspree); empty = preview mode, nothing is collected
- `phone`: pay-per-call tracking number (empty = Call button hidden)

Static site, deploys on Vercel with no build step.
