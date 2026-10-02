CIRCUITGENIUS WEBSITE — LOGO EDITION

Your uploaded CircuitGenius logo is included in assets/circuitgenius-logo.png.
The design uses a black background with gold/yellow and white accents to match the logo.

FILES
- index.html: website homepage and sections
- assets/circuitgenius-logo.png: your logo
- README.txt: these instructions

PUBLISH FOR FREE WITH GITHUB PAGES
1. Download and extract this ZIP.
2. Sign in to GitHub and create a Public repository named circuitgenius-website.
3. Upload index.html and the entire assets folder (keep the folder name and structure).
4. Open repository Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select branch main and folder /(root), then Save.
7. Wait for publishing. The public site address will appear in Settings > Pages.

EDIT THE SITE
Open index.html in a text editor such as Acode. Edit the text, save, then upload the updated file to the same GitHub repository.

ADD YOUTUBE VIDEOS
Replace one of the video placeholder blocks in the Videos section with:
<div class="video-box">
  <iframe width="100%" height="100%"
    src="https://www.youtube.com/embed/VIDEO_ID"
    title="YouTube video" frameborder="0" allowfullscreen></iframe>
</div>
Replace VIDEO_ID with the ID from your YouTube video URL.

ADD PDF DOWNLOAD LINKS
1. Upload your PDF to Google Drive.
2. Set its General access to "Anyone with the link".
3. Copy the share link.
4. In index.html, find the PDF resource and replace href="#" on its Open link with the share link.

ADD PROJECT PHOTOS
Upload image files into the assets folder, then edit a project card in index.html. Replace its emoji thumbnail with:
<div class="thumb"><img src="assets/your-photo.jpg" alt="Project photo" style="width:100%;height:100%;object-fit:cover"></div>
Use the exact filename and keep the image inside assets.

IMPORTANT ABOUT UPLOADING
This is a static website. It does not include a private admin dashboard or a public upload form. Visitors can view public content; to add or replace files, the site owner updates the repository. For videos, YouTube embedding is recommended. For PDFs, a share link is convenient.
