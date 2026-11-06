FELIX BIX FAVICON PACKAGE

Upload all image files to the ROOT of your GitHub Pages repository (the same folder as index.html).

Add these lines inside the <head> section of index.html:

<link rel="icon" type="image/x-icon" href="/favicon.ico">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">

Commit the changes, wait for GitHub Pages to deploy, then hard-refresh the website. Favicons may remain cached; check in a private/incognito window if the old icon persists.
