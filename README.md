# Femmer Fusion Fitness

Static homepage for **Femmer Fusion Fitness**: online home workouts and Zumba classes for women in Kerala.

- `index.html` has inline CSS and JS. Fonts come from Google Fonts: Noto Sans Malayalam, Poppins and Great Vibes.
- `assets/` holds the logo, the hero image and the icons.
- The page opens in Malayalam by default. Use `?lang=en` for English, or the മലയാളം/English toggle in the header. Text swaps come from the `data-ml` and `data-en` attributes.
- WhatsApp CTAs link to `wa.me/919946785211` with a prefilled message.

## Placeholders to replace
Trainer name and bio; testimonials (hidden in an HTML comment); class app; batch timings; missed-class policy; Instagram handle.

## Deploy
Vercel deploys this as a plain static site with no build step. Every push to `main` deploys to production.

Local preview: `python3 -m http.server` and then open http://localhost:8000
