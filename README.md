# GPSHunt
Code for a GPS based geohunt webpage

Direct someone on a mobile device to this webpage and it will show simply the number of feet to a target GPS location. It gives no other hints what it is about. I found it took about 3 minutes for seekers to figure out that as they move around the numbers change and they always get lower in a certain direction. Then the hunt is on!

When they reach within 5 feet of the target GPS location the page changes to a 'success' photo which would probably be either the next clue, or a photo at the location that pinpoints the thing they are supposed to find (like "DIG HERE ->")

Everything is contained in one HTML file. To use it host it somewhere, free GitHub hosting or Netlify hosting is fine. Change the target GPS coordinates in the file to the coordinates you want, and change the URL for the 'success' image that should come up when they reach the target. You can direct your seekers to the page with a QR code, or you can use a URL shortener like bit.ly to make a short version of the URL to embed in a clue.
