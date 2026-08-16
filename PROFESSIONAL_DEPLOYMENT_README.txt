PROFESSIONAL UPDATE
- Independent fan/community disclosure added.
- About, Contact, Privacy, Terms, Cookies and Request Status pages added.
- Footer navigation added to public pages.
- Existing translator, live chat, JSONBin photo submission and admin inbox retained.
- Bin ID retained: 6a806543da38895dfee86ff1.

SECURITY:
Never put the Master Key or Access Key in GitHub Pages client-side JavaScript. If hub-api.js is browser-loaded, its secrets are exposed. Use a server/serverless function with environment variables for secret JSONBin writes/reads. The public config contains only the Bin ID.

TEST:
Chrome, Safari, Firefox and Edge; mobile camera/photo picker; translator; forms; status page; admin inbox.
