# Unidos Landscaping - project instructions

## Image prompts (always apply)
Whenever the user asks for an image prompt (any service, page or project), return it ready to copy in a code block:

1. Start with the command `/proshoot ` (if the user says their tool writes it differently, e.g. `/pro shoot`, use that and update this file).
2. Then the scene description (specific, unique scene; vary house style, plants, angle and light so images in the same set do not look alike).
3. End with this realism/style block, verbatim:

```
Authentic unedited photograph, shot on a full-frame DSLR with a 35mm lens, real-world natural light, true-to-life colors, subtle natural imperfections, fine film grain, realistic textures. Looks like a real photo of a real finished project, not CGI, not a 3D render, not an illustration, not over-saturated. No people, no workers, no hands, no vehicles, no text, no logos, no watermarks.
```

Rules: finished projects only, never people working. Albuquerque, NM context. Wide shots may use 24mm, close-ups 85mm macro.
Sizes: hero image 1600x900 (16:9); other images 1200x900 (4:3).

## Site
- WordPress site: https://unidoslandscaping.com/ (content is pasted into WordPress manually from `wordpress-pages/`).
- Each service page has exactly 3 image slots. Prompts live in `image-prompts.md`.
- Source of recommendations: ELITE Builders X-Ray report (website items only; ignore Instagram, Facebook, ads, Google Business).
