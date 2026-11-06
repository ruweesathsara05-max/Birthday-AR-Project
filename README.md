# Birthday AR – Interactive Celebration

A beginner-friendly, marker-based augmented-reality birthday scene built with HTML, A-Frame and AR.js.

## Scene features

- Hiro marker scene with a birthday cake, balloons, gift box, party hat and small decorations.
- Different primitives: boxes, spheres, cylinders and a cone.
- Text labels: “HAPPY BIRTHDAY!” and “Make a wish!”
- Animation 1: the birthday cake rotates.
- Animation 2: the pink balloon floats up and down.
- 3D model: `models/birthday-cake.glb`, an original procedural birthday cake model created specifically for this project.
- Interaction 1: tap/click the pink balloon to cycle through colours (`color-changer` component).
- Interaction 2: tap/click the gift box to enlarge and return it to normal size (`gift-toggle` component).
- Status banner changes text and colour when the Hiro marker is found or lost.

## 3D model licence and credit

`models/birthday-cake.glb` is an original procedural model created specifically for this project. It is not downloaded from a third-party model library, and no third-party model attribution is required. The model is provided as a glTF Binary (`.glb`) asset.

The project loads A-Frame 1.3.0 and AR.js 3.4.5 from their public CDNs. Refer to the respective projects for their licence terms.

## Run on a laptop

1. Extract the ZIP file.
2. Open the `Birthday-AR` folder in Visual Studio Code.
3. Install the **Live Server** extension if you do not already have it.
4. Right-click `index.html` and choose **Open with Live Server**.
5. Allow camera access in the browser.
6. Display or print the official Hiro marker: https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png
7. Hold the Hiro marker in front of the camera.
8. Tap/click the pink balloon and gift box to test the interactions.

## Publish over HTTPS

### Option A – Netlify Drop

1. Open https://app.netlify.com/drop
2. Drag the extracted `Birthday-AR` folder onto the page.
3. Wait for Netlify to publish it.
4. Open the HTTPS link on a phone and allow camera access.
5. Show the Hiro marker to the phone camera. Use a printed marker or display it on another screen.

### Option B – GitHub Pages

1. Create a **public** GitHub repository.
2. Upload `index.html`, `README.md` and the `models` folder, keeping the folder structure unchanged.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/ (root)`, then save.
5. Wait for deployment and open the HTTPS URL on a phone.
6. Allow camera access and scan the Hiro marker.

A phone browser generally requires HTTPS for camera access. Do not test the deployed project using a plain HTTP address.

## Group submission checklist

- [ ] Test marker detection and marker-lost status.
- [ ] Test both animations.
- [ ] Test balloon colour changing.
- [ ] Test gift-box resizing.
- [ ] Test the deployed HTTPS link on a phone.
- [ ] Make the GitHub repository public.
- [ ] Put the GitHub repository URL in a Word document.
- [ ] Name the Word document using your actual group number.
- [ ] Only one group member submits the work.

## Technology

- HTML, CSS and JavaScript
- A-Frame 1.3.0
- AR.js 3.4.5
- glTF 2.0 Binary (`.glb`)
