# Methodology and Workflow

## 1. Capture
The team physically walked through the selected locations and captured 360° imagery in `.insp` format using an Insta360 X4.

## 2. Image processing
The files were processed in Insta360 Studio and exported as equirectangular panoramic JPG images.
- Original export resolution: 12000 × 6000
- Final compressed resolution: 8000 × 4000
- Approximate original dataset size: 6 GB
- Panoee free-tier storage allowance cited in the report: 3 GB

## 3. Tour creation
The prepared panoramic images were imported into Panoee as individual scenes. Two independent tours were created:
- SKUAST-K outdoor campus: 230 scenes
- CAIML Discovery Building interior: 35 scenes

Interactive hotspots were configured for scene-to-scene navigation, and VR mode was enabled through Panoee.

## 4. Publishing and embedding
Each tour was published separately on Panoee. The published URLs and the supplied iframe embed snippets are stored in this repository. Final embedding into official university websites remains the responsibility of their website administrators.

## 5. Verification checklist
- [ ] Confirm the campus tour URL opens.
- [ ] Confirm the CAIML tour URL opens.
- [ ] Test the iframe snippets on the intended website.
- [ ] Test fullscreen and VR behavior on supported devices.
- [ ] Add approved screenshots to `assets/screenshots/`.
