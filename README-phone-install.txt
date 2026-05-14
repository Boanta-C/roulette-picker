Roulette - phone PWA

Files:
- index.html
- manifest.webmanifest
- sw.js
- icons/

Simplest install path:
1. Upload this folder to GitHub Pages / Netlify / any static web host.
2. Open the hosted URL on her phone in Chrome/Cromite.
3. Browser menu -> Add to Home screen.

Local test on your PC:
cd roulette-phone-pwa
python3 -m http.server 7358
Then open http://YOUR_PC_IP:7358 from the phone while on the same Wi-Fi.

Notes:
- Entries are saved on the phone using localStorage.
- Theme choice is also saved on the phone.
- For a proper installable PWA, HTTPS hosting is best. GitHub Pages gives that for free.
