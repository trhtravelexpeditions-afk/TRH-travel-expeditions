# TRH Travel & Expeditions — GitHub Pages

## Website files
- `index.html` — homepage with the full-screen Ladakh drone video and the three expedition cards.
- `sainj.html` — separate Unwinding in Sainj itinerary page. Each day opens/closes when tapped.
- `assets/` — logo, video and photographs.

## Publish to GitHub Pages
1. Open your existing repository on GitHub.
2. Back up the current files first (download ZIP, or create a branch).
3. Upload the **contents** of this folder to the repository root. Keep the `assets` folder and its subfolders together.
4. If asked, choose to replace `index.html`; add `sainj.html` and `assets/`.
5. Commit the changes. Open the GitHub Pages URL and refresh after a minute or two.

## Replace the hero video later
Replace `assets/ladakh-drone.mp4` with the new MP4, keeping the exact filename. Use H.264 MP4 if possible. The video is configured to autoplay muted and loop; some mobile browsers may only start it after page load/interaction.

## Replace photos
Upload a replacement image to `assets/` using the same filename to keep the layout unchanged. To add more gallery photos, edit the `photos` array near the bottom of `sainj.html` and add another `["assets/your-photo.jpg", "Description"]` entry.

## Important
- WhatsApp enquiry/book buttons point to +91 90151 49281.
- Sainj is live; Ladakh and Spiti are deliberately non-clickable and marked Coming Soon.
- The Spiti card uses a Pin Valley, Spiti photo by Timothy Gonsalves from Wikimedia Commons, licensed CC BY-SA 4.0. Credit and source link are shown on the homepage; if you edit or redistribute that image, follow the license terms.
- The hero video supplied for this version is the uploaded `15258.mp4` file. Please confirm it is the intended Ladakh drone footage.
