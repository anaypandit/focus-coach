# Project notes

[Back to README](../README.md) · [Live demo](https://v0-new-project-emcec5fbckx.vercel.app/) · [Demo guide](DEMO_GUIDE.md)

## The hackathon idea

Focus Coach was developed collaboratively for UA Little Rock's **2025 AI and Mental Health Hackathon**. The team explored how a web-based assistant could help people recognize distraction and return to a task through supportive nudges, summaries, focus sessions, and restorative breaks.

The broader design included browser-based distraction awareness, personalized prompts, alternative ways to understand material, progress feedback, and optional social encouragement. These are design goals; the [demo guide](DEMO_GUIDE.md) records the behavior observed in the current deployment.

The design evolved through feedback about privacy and false positives. The team considered facial tracking, then moved toward browser behavior and positive reinforcement. Product outcomes and the effectiveness of these approaches have not been formally measured.

## Recognition

[UA Little Rock's August 7, 2025 article](https://ualr.edu/news/2025/08/07/mental-health-ai-hackathon/) identifies Focus Coach as the winning team and describes its real-time focus-support concept.

The existing project record documents a **$2,100 team competition award**, citing the organizer's June 18, 2025 email, “Congrats Focus Coach! - Survey, Media, Photos & Checks,” which specified five $420 checks. The award was a team prize, not app revenue; the private email is not included in this repository.

## Collaboration and tools

The project record, based on the shared proposal, credits **Anay Pandit, James Dempsey, Fahad Malallah, and Duron Huggins** on the development side and records Anay presenting the tool demonstration. It also credits **Aiden Behler, Elliot Estes, and Leelin Johnson** in the wider project work. Work was split across research, development, and presentation; individual component ownership has not yet been documented.

| Tool | Recorded use |
| --- | --- |
| Vercel v0 | Rapid UI prototyping. |
| ChatGPT | Research and drafting. |
| Claude | Listed among the development tools in the proposal. |
| Gamma | Presentation design. |

The working demo is hosted on Vercel. Its framework, package manager, service providers, and build requirements will be documented after the source is restored and inspected.

## Team materials

- [Team presentation](https://docs.google.com/presentation/d/1n8Fd8UMymu7sIbGSB8XO3PGjx_50vu_7MK9F-4hBxsM/edit)
- [Shared proposal and development notes](https://docs.google.com/document/d/1XgHXCt-FxwE_5cGWA7PIuJWSSFOFkVK1IPsetM1QHsg/edit)
- [University reporting](https://ualr.edu/news/2025/08/07/mental-health-ai-hackathon/)

Team materials may require access from their owners. Credits and tool history were retained from the repository's existing documentation; the current demo review does not independently establish individual implementation ownership.

## Source handoff checklist

The deployed demo was confirmed available on **November 12, 2026**. The repository still needs the original app source before it can support local development.

- [ ] Export or recover the original v0 application and any companion extension source.
- [ ] Review the source for credentials and remove private data before committing it.
- [ ] Include the package manifest, lockfile, assets, and required configuration.
- [ ] Add an example environment file with placeholder values only, if needed.
- [ ] Document the actual framework, runtime version, installation, development, and build commands.
- [ ] Verify a clean installation and production build from the committed files.
- [ ] Identify which AI, blocking, scoring, and social features use live integrations or demonstration behavior.
- [ ] Confirm contributor attribution and agree on licensing with the team.

Until this handoff is complete, this repository provides project documentation and screenshots rather than a runnable application.
