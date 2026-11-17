# unpaintd
unpaintd – Track, rate and review artworks you've seen, discover new artists, and unlock achievements along the way.

**The art you've seen. The stories you keep.**

> Log paintings, sculptures, installations, street art, and everything in between.

**Status:** Early prototype / work in progress

## Why unpaintd?

I love going to galleries and finding a piece that sticks with me, but I always forget its name a week later. 

unpaintd is my side project, built between night shifts and painting sessions. It is not a marketplace or an AI art generator. It is a place to remember art you actually experienced.

— Roger S

## Features in the prototype

- **Art diary:** Log an artwork, artist, museum/location, date seen, medium, and personal notes.
- **Ratings:** Give each work 1–5 stars.
- **Your collection:** Browse, search, filter, and delete logged works.
- **Progression:** Level up as you discover more **unique** works.
- **Achievements:** Unlock milestones for logging, reviews, museums, and mediums.
- **Local-first:** Data will be saved in your browser with `localStorage`; no account or backend yet.
- **Export/import:** Download your diary as JSON or import it again.

## Levels

| Level | Title | Unique artworks |
|---|---|---:|
| 1 | Curious Eye | 1 |
| 2 | Gallery Wanderer | 10 |
| 3 | Art Enthusiast | 25 |
| 4 | Art Connoisseur | 50 |
| 5 | Collector of Moments | 100 |
| 6 | Curator | 250 |
| 7 | Art Historian | 500 |
| 8 | Living Archive | 1,000 |

**Counting rule:** An artwork is counted once for level progression, even if you log repeat visits. In this prototype, duplicate detection uses a normalized artist + title pair.

## Achievements

| Badge | Unlock requirement |
|---|---|
| First Impression | Log your first artwork |
| Double Digits | Log 10 unique artworks |
| Century Club | Log 100 unique artworks |
| Thoughtful Critic | Write notes on 10 entries |
| Museum Regular | Log works from 5 distinct locations |
| Medium Explorer | Log works in 4 distinct mediums |
| Five-Star Finder | Give 5 artworks a five-star rating |

## Quick start

Work in progress.

## Project layout

```text
unpaintd/
├── README.md
```

## Roadmap

- [x] Set up repository and readme
- [ ] Local diary and ratings
- [ ] Level progression and achievements
- [ ] Search and filter
- [ ] JSON export/import
- [ ] Profiles and sign-in
- [ ] Follow friends and see their activity
- [ ] Museum and exhibition pages
- [ ] Artwork database and metadata search
- [ ] Repeat-visit timeline
- [ ] Verified artwork records and duplicate matching
- [ ] Accessibility and mobile polish

## My take on art

I want this to be about actual encounters with art, especially work made by people. I don't want an endless feed of AI-generated images. Supporting small artists matters to me. `#supportsmallartists`

## Privacy

Do not enter sensitive personal information.

## License

See [LICENSE](LICENSE).
