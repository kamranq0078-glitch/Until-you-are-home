# Until You're Home

A small, private, mobile-first illustrated page made with HTML, CSS, vanilla JavaScript, and original SVG artwork.

## Preview locally

Open index.html directly in a browser, or run a simple local server from this folder:

    python3 -m http.server 8000

Then visit http://localhost:8000.

## Edit the words

All page copy is in index.html, grouped under HTML comments for OPENING, WHAT I KNOW YOU'RE MISSING, FAMILY, ABOUT DADYY, HOME SOON, and CLOSING. Edit the corresponding text elements in those sections. The closing signature currently reads Kamran.

## Tune snowfall

In scripts/main.js, adjust density to change how many flakes are requested per screen area and maxFlakes to set a hard ceiling. Each flake's vy range controls fall speed. The canvas caps drawing at about 30 frames per second and uses at most 58 particles to keep the effect light on phones. Check on the target phone after changing these values.

## Share privately

For a quick private share, send a password-protected preview link from a hosting service that supports access protection, directly in a private message. Keep the page behind the password and avoid posting the URL publicly. The noindex, nofollow metadata discourages search indexing but is not access control.
