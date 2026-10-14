# Alesja Deliu — Portfolio / Paketa e plotë për GitHub Pages

**Ky ZIP përfshin të gjithë website-in**: HTML, CSS, JavaScript, CV-në, 6 screenshot-e brenda `images/`, 8 video MP4 me 8 kopertina brenda `videos/`, portretin dhe fotot e tjera të statistikave.

## Si ta përditësosh website-in ekzistues

Repository: https://github.com/deliualesja/AlesjaDeliu-portfolio
Faqja: https://deliualesja.github.io/AlesjaDeliu-portfolio/

1. Shkarko ZIP-in dhe bëj **Extract All** në kompjuter.
2. Hape dosjen e nxjerrë. Brenda saj duhet të shohësh **index.html**, **style.css**, **script.js**, **images/** dhe **videos/**.
3. Në GitHub, hap repository-n dhe kliko **Add file → Upload files**.
4. Zvarrit **folderin `images` dhe folderin `videos`**, me emrat e tyre të pandryshuar, te faqja e ngarkimit. Mos ngarko vetëm fotot veçmas në rrënjë. Kliko **Commit changes**.
5. **Kthe `index.html` te versioni i këtij ZIP-i:** në GitHub kliko `index.html` → ikonën e lapsit → Ctrl+A. Hape `index.html` e ZIP-it në VS Code/Notepad → Ctrl+A → Ctrl+C → kthehu në GitHub → Ctrl+V → **Commit changes**.
6. Skedarët `style.css` dhe `script.js` ekzistues në repository janë të njëjtë me origjinalët e këtij ZIP-i. Nëse më vonë i ndryshon, mbaji të sinkronizuar me këtë paketë.
7. Prit 1–3 minuta, pastaj rifresko website-in me **Ctrl + Shift + R**.

## Kontrolli i fundit në GitHub

Në rrënjë (pranë `index.html`) duhet të shfaqen folderat **`images`** dhe **`videos`**.

- `images/`: 6 imazhe JPG (Meta Ads, Instagram dhe Facebook Insights).
- `videos/`: 8 video MP4 + 8 postera JPG. Videot shihen me **Play brenda telefonave** në website; nuk duan Instagram link.
- Në rrënjë: `portrait.jpg`, `insights-overview.jpg`, `insights-audience.jpg`, `post-112k.jpg`, `post-72k.jpg`, `post-5528.jpg`, `Alesja-Deliu-CV.pdf`.

**Kujdes:** Mos ngarko ZIP-in direkt si një file në GitHub. ZIP-in duhet ta shpaketosh dhe të ruash folderat dhe emrat e skedarëve siç janë. Nëse `images` ose `videos` vendosen gabim jashtë strukturës, pamjet nuk ngarkohen.

## Testuar

- Referencat lokale në HTML janë kontrolluar kundrejt skedarëve që përfshin paketa.
- Çdo foto JPG u kontrollua që të hapet si imazh.
- Secila nga 8 videot MP4 u kontrollua me `ffprobe` për formatin H.264 dhe AAC.
- Pamja desktop/telefon dhe funksionimi i JavaScript-it u verifikuan në një preview të faqes.
