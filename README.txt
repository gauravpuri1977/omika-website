OMIKA COUTURE — PUBLISH TO /sample2

This package is structured for the existing GitHub Pages site at:
https://omikacoutures.com/sample2/

PACKAGE STRUCTURE
sample2/
  index.html
  assets/
    catalogue images, logo, poster images, and four silent MP4 fashion videos

HOW TO PUBLISH USING GITHUB WEB UI
1. Extract this ZIP on your computer.
2. Open the GitHub repository that currently publishes omikacoutures.com.
3. At the repository root (the same level as the existing index.html and CNAME), create a folder named sample2.
4. Upload the contents of this package's sample2 folder into that new folder, preserving the assets subfolder.
   Required paths include sample2/index.html and sample2/assets/...
5. Commit the upload to the branch configured for GitHub Pages (usually main).
6. Wait for GitHub Pages to finish deploying.
7. Visit https://omikacoutures.com/sample2/ (the trailing slash is recommended).

IMPORTANT
- Do not replace or delete the root index.html; that keeps your current homepage/Coming Soon page unchanged.
- Do not replace, move, or delete the existing root CNAME file.
- Keep the entire sample2/assets folder; the page uses relative paths to its images and videos.
- The HTML uses relative asset paths, so it works inside /sample2/ without changing your custom domain or DNS.
- This is a static design prototype. Newsletter submission and most footer/policy destinations are not connected yet.
- If GitHub Pages is publishing from a /docs folder or a different branch/folder, upload sample2 into that configured publishing location instead of the repository root.
