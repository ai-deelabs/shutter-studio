Build a landing page as a single file `v2.html` — all CSS
and JS inline, no frameworks.

Brand:
Shutter Studio is a photography studio specializing in portrait and commercial advertising photography. The brand features a minimal black and white aesthetic that conveys professionalism and elegance. The design emphasizes clean lines, high-quality visual presentation of photography work, and a sophisticated approach that highlights the studio's expertise in capturing compelling imagery.

This is variant 2 of 2.
Express the brand's style through layout, whitespace, typography,
visual rhythm, and photo treatment — not just color. Avoid cliché
color associations (gold for luxury, blue for trust, green for health).

Responsive, mobile-first. Set `<html lang="en">`.
Logo is text-only (styled with CSS/fonts) — no image logos.

No emojis. Use Lucide Icons:
`<script src="https://unpkg.com/lucide@0.460.0"></script>` in head,
`<i data-lucide="icon-name"></i>` in body, `lucide.createIcons()` at end.

Images — search with different keywords per section:
`bash /home/runner/work/web-builder-control/web-builder-control/core/tools/search-images.sh "keyword" [count]`
Use returned URLs in `<img>` with `?w=WIDTH&h=HEIGHT&fit=crop`.
Fallback: `https://picsum.photos/seed/{keyword}/{width}/{height}`.

No X-Frame-Options (this page loads inside an iframe for preview).
