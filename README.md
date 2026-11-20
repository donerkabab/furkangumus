# Furkan Gümüş — Personal Portfolio

Professional portfolio website for **Furkan Gümüş**, Process & Mining Engineer specializing in gold mining, mineral processing, and operational excellence.

Built from the exact `alancavagnaro.com` Weebly/Birdseye theme with 100% of the HTML structure, CSS stylesheets, layout dimensions, fonts, and responsiveness preserved.

---

## Profile Summary

- **Title**: Process & Mining Engineer / Mineral Processing Engineer
- **Current Position**: Process Shift Engineer at **Avesoro Resources** (FIFO Rotation, Liberia)
- **Previous Position**: Process Shift Engineer at **Centerra Gold Inc. (Öksüt Gold Mine)** (Kayseri, Turkey)
- **Education**: B.Sc. in Mining Engineering, **Hacettepe University** (100% English Curriculum, GPA: 3.05/4.00, Department 1st Place Capstone Project)
- **Expertise**: Crushing & Grinding, CIL/CIP Leaching, Heap Leaching, Zadra ADR, Elution & Electrowinning, Induction Smelting & Dore Production, Metallurgical Accounting, Mass & Energy Balance, KPI Monitoring, HSE & AI-assisted Safety Management.
- **Languages**: Turkish (Native), English (Advanced/Fluent), Mandarin Chinese (HSK 3 - Peking University)
- **Contact**: Ankara, Turkey | +90 553 151 3644 | furkangumus166@gmail.com | [LinkedIn](https://www.linkedin.com/in/furkangumus1998/)

---

## Pages

1. **`index.html`** — Home (Hero with Furkan's photo collage, 3 operational focus cards, professional summary, contact CTA)
2. **`my-story.html`** — My Story (Furkan's biography, academic foundation at Hacettepe, career milestones at Avesoro and Centerra Gold, safety philosophy, international ambitions)
3. **`my-experience.html`** — My Experience (Technical skillset grid, complete career timeline, education, awards & honors)
4. **`my-work.html`** — My Work (8 dedicated gold processing and operational excellence cards)
5. **`contact.html`** — Contact (Direct phone, email, location, LinkedIn connection, and contact form)

---

## Local Preview

```bash
cd /home/elliot/myworks/furkangumus/www.alancavagnaro.com
python3 -m http.server 8080
```

Open `http://localhost:8080/` in your browser.

---

## Deployment to GitHub Pages

1. Push this repository to GitHub:
   ```bash
   git add .
   git commit -m "feat: integrate Furkan's photos and resume"
   git branch -M main
   git remote add origin https://github.com/<YOUR_USERNAME>/<REPO_NAME>.git
   git push -u origin main
   ```
2. In GitHub: **Repository Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. `.github/workflows/deploy.yml` automatically publishes the website.
