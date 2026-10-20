# Development of 360° Virtual Tours for SKUAST-K Campus and CAIML

A university project documenting two web-based 360° virtual tours created using panoramic imagery captured with an Insta360 X4, processed in Insta360 Studio, and assembled and hosted using Panoee.

> **Scope:** Panoee was used as the virtual-tour builder and hosting platform. This repository documents the team's capture, image-processing, tour-creation, and embedding work; it does not claim that the team developed Panoee itself.

## Live tours

### SKUAST-K Campus
- **Coverage:** Outdoor campus
- **Scenes:** 230
- **Open tour:** https://tour.panoee.net/6a7a0bea123af5701c233152
- **Embed snippet:** [`embeds/campus-embed.html`](embeds/campus-embed.html)

### CAIML — Discovery Building
- **Coverage:** Indoor department building
- **Scenes:** 35
- **Open tour:** https://tour.panoee.net/6a32d4bdd0e5ab828601d2fb
- **Embed snippet:** [`embeds/caiml-embed.html`](embeds/caiml-embed.html)

Both tours are hosted separately on Panoee. They are intended for embedding on the respective official websites; final website integration is to be carried out by the relevant website administrators.

## Objectives
- Create remotely accessible 360° representations of the SKUAST-K campus and CAIML department.
- Capture panoramic imagery and prepare it for web delivery.
- Create two separate interactive tours with scene-to-scene navigation and VR mode.
- Document the workflow, outputs, and embedding snippets for academic review and future maintenance.

## Tools used

| Tool | Purpose |
|---|---|
| Insta360 X4 | Capture 360° imagery |
| Insta360 Studio | Process `.insp` files and export panoramic JPG images |
| Panoee | Build tours, configure navigation/hotspots, host and embed the tours |
| GitHub | Version project documentation and store embed snippets |

## Image preparation
According to the project report, the original panoramic exports were 12000 × 6000 pixels and were compressed to 8000 × 4000 pixels. This reduced the dataset from approximately 6 GB to fit within Panoee's stated 3 GB free-tier storage allowance while retaining acceptable visual quality.

## Repository contents
- `docs/project-report.md` — report draft based on the project report details
- `docs/methodology.md` — capture-to-publishing workflow
- `docs/team-and-credits.md` — team and supervisor details
- `tours/` — links and details for both published tours
- `embeds/` — supplied Panoee iframe and device-motion snippets
- `assets/` — space for approved screenshots and a workflow diagram

## Team

| Name | Roll number | Role |
|---|---|---|
| Arnav Saxena | BTAI-2024-26 | Team Leader |
| Mir Faiq | BTAI-2024-11 | Member |
| Mohammad Fouzan | BTAI-2024-23 | Member |

**Centre:** Centre for Artificial Intelligence and Machine Learning (CAIML)  
**Programme:** B.Tech AI (2024 batch)  
**Institution:** SKUAST-Kashmir  
**Supervisors:** Dr. Showkat Rasool and Mr. Mohammad Saqib Dar  
**Project duration:** April 2026 – August 2026 (approximately four months)  
**Completion date:** 18 August 2026

## Future scope
- Integrate both tours into a unified campus digital twin.
- Expand CAIML coverage to include outdoor surroundings.
- Add informational overlays for key locations.
- Explore a more comprehensive VR-based campus experience.

## Notes for maintainers
- Test both tour URLs periodically.
- Obtain university approval before embedding tours on official sites or publishing images of restricted areas.
- Do not commit passwords, access tokens, private Panoee settings, or the full high-resolution panorama dataset.
- Test the HTML snippets on the intended website before production use. Some content-management systems accept only iframe markup rather than a full HTML document.

## Acknowledgement
The project was undertaken under the guidance of Dr. Showkat Rasool and Mr. Mohammad Saqib Dar at CAIML, SKUAST-Kashmir.
