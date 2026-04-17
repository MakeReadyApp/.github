# Make Ready

Open-source match-day platform for competitive shooting — USPSA, IDPA, Steel Challenge, and (soon) PCSL. Built to replace paper scoresheets and spreadsheet-based match management with something shooters and match directors can actually fork, improve, and run.

Live beta: [makereadyapp.com](https://makereadyapp.com)

## About this project

I'm not a developer. I'm a competitive shooter who got frustrated with the state of match management tools and decided to build something. Most of this code was vibecoded with Claude and a lot of trial and error. It's running as a beta, but it is **not production-ready software** — there are rough edges everywhere and plenty I don't know enough to do well.

I'm open-sourcing it so that actual developers, coders, and software engineers in the shooting community can take it somewhere better. Fork it, rewrite it, tear it apart — do whatever makes it useful. GPLv3; it belongs to the community now.

## The two halves

| Repo | What it is | Who uses it |
|------|------------|-------------|
| [MakeReady.Web](https://github.com/MakeReadyApp/MakeReady.Web) | Next.js / Supabase web app for match discovery, registration, results, and club management | Shooters, match directors |
| [MakeReady.Mobile](https://github.com/MakeReadyApp/MakeReady.Mobile) | Expo / React Native app for match-day scoring and squad management, offline-first | Match directors + range officers on Fire tablets |

The web app is the source of truth for match creation and registration. The mobile app downloads a match, works offline during the day (syncs between a master pad and scoring pads over a local WiFi hotspot), then uploads results back to the cloud when the match ends.

## Ways to help

- **Shooters / MDs / ROs** — file issues, bug reports, feature requests. Test on your club's matches and tell me what breaks.
- **Coders** — bug fixes, features, refactors. See `CONTRIBUTING.md` in each repo.
- **Experienced developers who want to lead this project** — I'd genuinely welcome that. Email **dev@guccigunclub.com** and let's talk.

## License

GPLv3 across both repos. Contributions accepted under the same license.
