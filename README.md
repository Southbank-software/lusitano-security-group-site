# Lusitano Security Group – Marketing Site

Multi-page static site (black theme) with a confidential enquiry form using **Netlify Forms**.

## Pages
- `/` Home
- `/services/` Services
- `/approach/` Approach
- `/about/` Professional Standards
- `/contact/` Enquire (Netlify form)
- `/thanks/` Form success page

## Local preview
```bash
python3 -m http.server 8888
```
Visit: http://localhost:8888

## Deploy: GitHub + Netlify
1) Create a GitHub repo (e.g. `lusitano-security-group-site`)
2) Push these files to the repo
3) Netlify → **Add new site** → **Import an existing project**
4) Choose the repo
   - Build command: (leave blank)
   - Publish directory: `.`
5) Deploy

### Netlify Forms
Netlify will detect the form named `enquiry`. After deployment:
- Netlify dashboard → Site → **Forms** → view submissions
- Configure email notifications in **Forms → Settings**

## Domain (lusitanosecuritygroup.com)
Netlify → Site settings → **Domain management** → Add custom domain.
Follow Netlify's DNS instructions. SSL is automatic once DNS is correct.

## Logo
The site uses: `assets/img/logo.svg`
Replace that file to swap logos.