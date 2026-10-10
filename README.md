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
Square photos (512×512 JPEG) live in `images/people/<name-slug>.jpg` and are referenced from
`index.html`, `speakers.html` and `organizers.html`. To replace a photo, overwrite the file with the same name.

Sources: each person's homepage or institutional profile (linked from their name on the site);
Razvan Pascanu's is from his Mila profile, Muhammad Haris Khan's from the MBZUAI faculty directory.

## After acceptance
- Change "ICLR 2027 Workshop Proposal" in the hero pill and remove the `.notice` banners
- Fill in date, room, OpenReview link, and talk titles in the schedule
