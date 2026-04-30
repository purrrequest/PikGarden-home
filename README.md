
## 🌟 Highlights

A fan-made web app for Pikmin Bloom players to track their decor collection and find nearby decor spots.

**Live app:** [pikgarden.vercel.app](https://pikgarden.vercel.app)

<img src="images/PikGarden Decor Tracker Finder.jpg">
<img src="images/PikGarden More.jpg">
<img src="images/Pikmin Bloom Rare Decor.jpg">



## The Problem

Pikmin Bloom players collect decor Pikmin across dozens of location types and color variants. The game offers in-game catalog, but there are just too many types of decors and variations. Most players rely on memory or manually maintained spreadsheets. 



## What I Built

PikGarden is a mobile-first web app with two core features:

**Garden Tracker** — Track your decor collection by type and color variant. See your progress at a glance, mark individual variants as collected, and identify what you're still missing.

**Decor Finder** — Search by decor type to find nearby real-world locations. Open results directly in Google Maps to plan your next walk.



## How I Approached It

This is my first personal project. I treated this fan project the same way I'd approach a product, starting with real user problems, shipping fast, listening to feedback, and making deliberate decisions about what to build next.

Some decisions I made along the way:

**Web app over native**: Faster to ship and update. Pikmin Bloom releases new decors monthly, so being able to push updates instantly matters. Native apps would introduce App Store delays and added complexity for a fan project at this stage.

**PWA over native app**: Addressed user requests for a home screen experience without the overhead of native development. Users can add PikGarden to their home screen on both iOS and Android.

**Firebase for auth and storage**: Lets users save their collection progress across devices with Google sign-in. No backend to maintain.

**Community-first growth**: Shared the app on the Pikmin Bloom subreddit as the primary distribution channel. Used real community feedback to prioritize features and fixes.



## Stack

- Vanilla JS, HTML, CSS -- single file, no framework
- Firebase Auth + Firestore -- user authentication and collection sync
- Google Maps API -- location-based decor finder
- Vercel -- hosting
- Claude Code -- AI-assisted development
- Google Analytics -- usage tracking



## Status

Actively maintained. Updated monthly with new Pikmin Bloom decor releases.
