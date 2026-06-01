KML Layer Checker deployment package
This package contains a browser-based static web app for searching an address or postcode and checking which embedded KML planning layers contain that point.
Included app
•	index.html — self-contained app with embedded KML layers, visible map polygons, layer legend, and address search
Fastest hosting options
Option 1: Netlify
1.	Sign in to Netlify.
2.	Go to the manual deploy area.
3.	Drag and drop the deploy-package folder, or upload index.html as the site root.
4.	Netlify will generate a shareable live URL.
Option 2: Cloudflare Pages
1.	Sign in to Cloudflare.
2.	Create a new Pages project.
3.	Choose direct upload for a static site.
4.	Upload the contents of this folder.
5.	Cloudflare Pages will generate a live pages.dev URL.
Option 3: GitHub Pages
1.	Create a GitHub repository.
2.	Upload index.html to the repository root.
3.	Enable GitHub Pages in repository settings.
4.	Share the generated Pages URL.
Notes
•	The app is self-contained, so it does not need separate KML files at runtime.
•	Users only need a browser and internet access for the base map and address lookup.
•	If you want to share this widely across a team, consider replacing the public geocoder with an organisation-approved geocoding service.
Suggested next improvements
•	Add CSV export of the matched layer results.
•	Add a branded title and organisation logo.
•	Add a short disclaimer about planning-layer screening versus formal determination.
