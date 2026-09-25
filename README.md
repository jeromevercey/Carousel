# Explorance — Vertical Carousel

A Kajabi-style vertical carousel for the Explorance "Build an Employee Experience that Boosts Revenue and Grows Your Business" section.

Single self-contained file (`index.html`): plain HTML, CSS and JavaScript, no build step or dependencies.

## Behaviour

- Numbered list on the left; the active item expands with its description and link, and a vertical progress bar fills beside it.
- The media panel on the right slides vertically to the matching visual.
- Loops continuously every 6 s while the section is on screen: after the last item it keeps sliding down to the first. Pauses on hover/focus; clicking an item jumps to it and the loop carries on from there.
- Keyboard navigation (arrow keys, Home/End) and `prefers-reduced-motion` support.
- Below 900 px it becomes an accordion with the visual inside the open item.

## Editing

- **Content:** edit the `ITEMS` array in the `<script>`. Set `image` to a screenshot URL to replace the built-in mock visual.
- **Colors / timing:** edit the CSS variables in `:root` (`--ex-navy`, `--ex-accent`, `--ex-duration`, …).
