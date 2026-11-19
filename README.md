# Furkan Gümüş — Personal Portfolio

Personal portfolio website for Furkan Gümüş, Mining Engineer specialising in
gold mining and mineral processing operations.

Built from the alancavagnaro.com Weebly/Birdseye theme with original content
replaced.  All HTML, CSS, and JavaScript structure is preserved.

## Local Preview

```bash
cd www.alancavagnaro.com
python3 -m http.server 8080
# Open: http://localhost:8080/
```

## GitHub Pages Deployment

1. Create a new GitHub repository (e.g. `furkan-portfolio`)
2. Push this project:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/furkan-portfolio.git
   git push -u origin main
   ```
3. In repo **Settings → Pages → Source → GitHub Actions**
4. The site deploys automatically via `.github/workflows/deploy.yml`

## Content Placeholders

The following items need real information from Furkan:

| Placeholder | Location | What to update |
|---|---|---|
| `[Current Mining Company]` | my-experience.html | Real employer name |
| `[Start Date]` | my-experience.html | Employment start date |
| `[Previous Mining Operation]` | my-experience.html | Previous employer |
| `[University Name — Turkey]` | my-experience.html | Degree institution |
| `[Graduation Year]` | my-experience.html | Year of graduation |
| Profile photo | uploads/.../editor/img-8421.jpg | Portrait photo |
| Operations photos | uploads/.../*_orig.jpg | Work/site photos |

## Pages

- `index.html` — Home
- `my-story.html` — About / Biography
- `my-experience.html` — Career & Skills
- `my-work.html` — Projects & Operations
- `contact.html` — Contact

## Notes

- The Weebly contact form (`action="https://www.weebly.com/weebly/apps/formSubmit.php"`)
  will not submit (requires Weebly account). Use LinkedIn for contact.
- Background images are from the original site and are scenery/abstract —
  they do not contain any personal photos of Alan Cavagnaro.
