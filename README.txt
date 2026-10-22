YOUR MINIMAL BIRTHDAY WEBSITE — EDITING GUIDE

The site has three pages/stages:
1. Birthday greeting + cake. Tap “Blow out the candles”; candles go out, then tap again to continue.
2. Letter page. Replace the bracketed sample text with your own letter.
3. Picture page. Replace photo placeholders with your own pictures.

EDIT NAME:
Open index.html in a text editor (VS Code, Notepad, etc.) and replace [HER NAME] and [YOUR NAME].

ADD PHOTOS:
1. Make a folder named photos beside index.html.
2. Copy your photos into it, e.g. photo1.jpg, photo2.jpg, photo3.jpg.
3. For each <div class="photo-placeholder">YOUR PHOTO 01</div>, replace it with:
   <img src="photos/photo1.jpg" alt="A favourite memory of us">
   Use photo2.jpg and photo3.jpg for the other two slots.
4. You can change each [caption] underneath the photo.

PREVIEW:
Double-click index.html to open it in a browser.

GET A WEBSITE LINK:
Upload index.html and the photos folder to a GitHub repository, then enable GitHub Pages in repository Settings. The published page is viewable by people with the link; editing access is controlled by repository permissions. Avoid including private information you don't want online.
