# Wassim Farhat — Corporate Engineering Portfolio

## Included
- `index.html` — responsive, clean white-and-navy portfolio
- `Wassim_Farhat_CV.pdf` — CV download linked from the page (if included in this bundle)
- `reports/` — add approved PDF reports here
- `assets/videos/` — optional MP4 demonstrations
- `assets/images/` — optional project photos and diagrams

## Add your real reports and videos
Open `index.html` and find `const portfolioResources = [` near the bottom. Add one entry per real resource. Example entries:

```js
{ project: "plc", title: "PLC & SCADA technical report", type: "pdf", url: "reports/plc-scada-report.pdf", description: "Internship project report" },
{ project: "esp32", title: "Generator monitoring demo", type: "video", url: "https://www.youtube.com/watch?v=YOUR_REAL_VIDEO_ID", description: "Hardware demonstration" },
{ project: "solar", title: "PV installation walkthrough", type: "video", url: "assets/videos/solar-pv-demo.mp4", description: "Installation demonstration" },
{ project: "pcb", title: "PCB project files", type: "link", url: "https://github.com/YOUR-USERNAME/YOUR-REPOSITORY", description: "Design files" },
```

Replace all example filenames and URLs with real resources. Do not add a resource until the corresponding file or public URL exists.

Supported project keys:
- `plc` — PLC & SCADA modernization
- `esp32` — ESP32 generator monitoring
- `solar` — solar PV installation
- `scrap` — industrial scrap analysis
- `pcb` — Altium PCB design
- `parking` — smart parking
- `workshop` — Arduino workshop

Supported types: `pdf`, `video`, `link`.
- Local PDFs: put them in `reports/` and use a relative path such as `reports/plc-scada-report.pdf`.
- Local MP4s: put them in `assets/videos/` and use a relative path.
- YouTube: use the normal watch URL; the page adds a watch link.
- Google Drive: share the file with recruiter-accessible view permissions, then paste its share URL.
- Large videos are usually better hosted on YouTube or Drive than committed directly to GitHub.

## Publish on GitHub Pages
1. Download and extract the ZIP.
2. Open your GitHub repository, or create a new repository for the portfolio.
3. Upload `index.html`, `Wassim_Farhat_CV.pdf`, and any `reports/` and `assets/` files. Keep the same folder structure.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select your main branch and `/ (root)` as the folder, then save.
7. Wait for GitHub Pages to publish and open the URL shown in Settings → Pages.
8. Test every PDF, video and CV link on desktop and mobile.

## Privacy and accuracy
Only publish reports and videos you are allowed to share. Remove employer-confidential data, personal information, internal production records, and anything your school or employer restricts. The page currently contains no fabricated report or video links; add your real materials when ready.
