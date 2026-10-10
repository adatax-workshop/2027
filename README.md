# AdaTax @ ICLR 2027 — Workshop Website

**The Adaptation Tax: What Breaks When We Update Models?**

Live at https://adatax-workshop.github.io/2027/ (GitHub Pages, served from `main`).
Future editions go in sibling repos: `adatax-workshop/2028`, ...

Plain static HTML/CSS/JS, no build step. Structure and styling follow the DG-EBF CVPR 2026 site.

## Pages
- `index.html` — Home: motivation, three questions, speakers, organizers, topics, dates, contact
- `call-for-papers.html` — scope, topics, tracks, policies, review, AI policy, dates
- `program.html` — tentative schedule, format, panel, remote participation
- `speakers.html` — invited speakers with proposed focus and bios
- `organizers.html` — organizer bios and program committee

## Photos
Square photos (512×512) go in `images/people/<name-slug>.jpg`.
People without a photo currently use an initials placeholder `images/people/<name-slug>.svg`.
To swap one in, add the `.jpg` and change `.svg` to `.jpg` in `index.html`, `speakers.html` and/or `organizers.html`:

```
grep -rl "people/<name-slug>.svg" *.html | xargs sed -i '' 's#people/<name-slug>.svg#people/<name-slug>.jpg#g'
```

## After acceptance
- Change "ICLR 2027 Workshop Proposal" in the hero pill and remove the `.notice` banners
- Fill in date, room, OpenReview link, and talk titles in the schedule
