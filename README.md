# Orlando Family Trip Playbook

Day-by-day itinerary for our October 2026 Orlando trip, hosted on GitHub Pages.

**Live site:** https://bpolhamus13.github.io/DisneyItinerary/

## Hosting

The whole site is a single self-contained `index.html`. To publish:

1. Push to `main`.
2. In the repo go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, then `main` and `/ (root)`, and save.
4. The site goes live at the URL above within a minute or two.

## Editing

All itinerary content is in the `const data = [...]` block near the top of the `<script>` in `index.html`. The trip guide content is in `const guide = {...}` right below it.

The planning Word doc is intentionally gitignored so it never gets published.
