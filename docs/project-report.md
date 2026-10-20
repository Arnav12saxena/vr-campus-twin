# Development of 360° Virtual Tours for SKUAST-K Campus and CAIML

## Project information
- **Submitted to:** Centre for Artificial Intelligence and Machine Learning (CAIML), SKUAST-Kashmir
- **Supervisors:** Dr. Showkat Rasool and Mr. Mohammad Saqib Dar
- **Department:** CAIML, B.Tech AI (2024 batch)
- **Duration:** April 2026 – August 2026 (approximately four months)
- **Completion date:** 18 August 2026
- **Project context:** A departmental initiative, not the team's final B.Tech project.

## Team

| Name | Roll number | Role |
|---|---|---|
| Arnav Saxena | BTAI-2024-26 | Team Leader |
| Mir Faiq | BTAI-2024-11 | Member |
| Mohammad Fouzan | BTAI-2024-23 | Member |

## 1. Introduction
This project involved creating two separate 360° virtual tours: one covering the SKUAST-Kashmir main campus and one covering the CAIML department. The tours are intended to support remote exploration by prospective students, visitors, and the public, and are designed to be embeddable in the official university and department websites.

## 2. Objectives
- Create an immersive, remotely accessible 360° representation of the SKUAST-K campus and CAIML department.
- Enable prospective students, visitors, and the public to explore the locations digitally.
- Support institutional outreach through web-embeddable interactive tours.
- Lay groundwork for future digital-twin or VR-based campus applications.

## 3. Hardware and software
- **Hardware:** Insta360 X4 360° camera.
- **Insta360 Studio:** Processing `.insp` files into panoramic images.
- **Panoee:** Constructing and hosting both tours and configuring navigation/hotspots.

## 4. Data acquisition
The team physically walked through both locations and captured 360° imagery in `.insp` format using an Insta360 X4.

### SKUAST-K campus
- Outdoor coverage only; no indoor sections.
- Major outdoor areas, prominent buildings, and open fields were captured zone by zone.
- 230 individual 360° images/scenes.

### CAIML (Discovery Building)
- Indoor coverage of the department building.
- 35 individual 360° images/scenes.

## 5. Image processing
The raw `.insp` files were processed in Insta360 Studio and exported as equirectangular panoramic JPG images.
- Original export resolution: 12000 × 6000.
- Final compressed resolution: 8000 × 4000.

The project report records that the original dataset was approximately 6 GB and that reducing the images allowed the dataset to fit within the Panoee free-tier storage allowance stated in the report as 3 GB.

## 6. Virtual-tour development
Both tours were built on Panoee using the processed panoramic images as individual scenes.

Features configured:
- Interactive hotspots for scene-to-scene navigation.
- VR mode support.

The campus tour and CAIML tour are independent, unconnected tours hosted separately on Panoee.

## 7. Published tours
- **SKUAST-K campus:** https://tour.panoee.net/6a7a0bea123af5701c233152 — 230 outdoor scenes.
- **CAIML building:** https://tour.panoee.net/6a32d4bdd0e5ab828601d2fb — 35 indoor scenes.

Intended website destinations:
- SKUAST-K: https://skuastkashmir.ac.in/
- CAIML: https://skuastkashmir.in/CAIML/

## 8. Web integration
Both tours are hosted on Panoee and have iframe embed snippets with fullscreen, VR, and gyroscope/device-motion options. Final embedding into the official websites is to be performed by the respective website administrators.

## 9. Challenges and solutions
**Storage constraint:** The report identifies a Panoee free-tier storage allowance of 3 GB and an original dataset of approximately 6 GB. Compressing panoramas to 8000 × 4000 pixels reduced storage requirements while preserving acceptable visual quality for the tours.

## 10. Results
Two web-ready 360° tours were produced:
- A 230-scene outdoor tour of the SKUAST-K campus.
- A 35-scene indoor tour of the CAIML department.

Both tours are hosted on Panoee and include interactive hotspot navigation and VR mode.

## 11. Future scope
- Integrate both tours into a unified campus digital twin.
- Expand the CAIML tour to include outdoor department surroundings.
- Add informational overlays for key locations.
- Explore a fuller VR-based navigable campus experience.

## 12. Conclusion
The team created two deployable 360° virtual tours for the SKUAST-K campus and CAIML. The tours support remote exploration and represent an initial step toward broader campus digitization.

---
This Markdown version summarizes the supplied project report for convenient viewing on GitHub. Use the original DOCX report for the formal report layout and verify all details before official submission.
