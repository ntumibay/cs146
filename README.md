# AniRate – Anime Rater and Watchlist

CS146 group project by Ian Zambrano, Jayden Tumbokon, Jessie Ibea, and Noah Tumibay.

A responsive HTML/CSS front end for rating anime, keeping a watchlist, viewing watch metrics, customizing a profile, and sharing a snapshot of your lists.

## Pages

| Page | Purpose | User story |
| --- | --- | --- |
| `index.html` | Landing page: Top Anime (top 3 by rating), Soon to Watch, and Share button | 1, 2, 5 |
| `rate.html` | Browse & Rate: search, catalog with Add to Watchlist, rating form, and your ratings | 1, 2 |
| `profile.html` | Profile with stickers, watch metrics, Watching/Watched/Soon to Watch lists, and settings | 3, 4, 5 |
| `snapshot.html` | Shareable snapshot opened by the Share button (not in the nav) | 5 |
| `about.html` | Project and team info | – |

All styles live in `styles.css`. Images are in `images/`.

## Responsive layouts

- **Desktop** (wider than 900px): 3-column card grids and lists; profile and metrics side by side.
- **Tablet** (900px and below): 2-column cards; lists, profile, and metrics stack.
- **Phone** (600px and below): single column, centered wrapping nav, full-width buttons.

## Current limitations

This assignment does not allow `<script>` or `<style>` tags, so the pages are static. Buttons and forms show the intended UI states with sample data but do not change anything yet. Adding to the watchlist, removing, marking as watched, uploading images, live metrics, and generating snapshots will need JavaScript in a later phase.

## Validation

All HTML pages pass the W3C Nu HTML Checker with no errors or warnings.
