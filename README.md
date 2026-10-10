# Unidos Landscaping - website pages (from the ELITE Builders X-Ray report)

Structure for the new individual service pages. Web-only recommendations; Instagram, Facebook, ads and Google Business excluded.

## Page structure

```
/services/   (hub page: link to all pages below)
 ├─ /landscaping-maintenance-albuquerque-nm/
 ├─ /irrigation-repair-albuquerque-nm/
 ├─ /service-calls-albuquerque-nm/
 ├─ /outdoor-lighting-albuquerque-nm/
 ├─ /xeriscaping-albuquerque-nm/
 ├─ /yard-cleanup-albuquerque-nm/
 ├─ /masonry-albuquerque-nm/
 ├─ /concrete-contractor-albuquerque-nm/
 ├─ /paver-installation-albuquerque-nm/
```

Each page has 3 image slots only (hero + 2 inline). See `image-prompts.md` for the 30 prompts.

## Files
- `wordpress-pages/*.html`: one file per page; paste into a Custom HTML block.
- `wordpress-pages/unidos-services.css`: shared styles (Additional CSS).
- `image-prompts.md`: 3 AI image prompts per service.

## Global fixes (not service pages)
- Home H1: "Landscaping and Hardscaping in Albuquerque, NM"
- Add "Proudly serving Albuquerque, Rio Rancho and Corrales" in the hero and service pages
- Show real Google Reviews on the Home
- Copy fixes: "Checkout" -> "Check Out", "GET A QUOTES" -> "Get a Free Estimate", "Others Services" -> "Other Services"
- Home FAQ: cost, timeline, license, service area, xeriscaping
- Link each service block on /services/ to its page; add a "See More" button on the Home services section
