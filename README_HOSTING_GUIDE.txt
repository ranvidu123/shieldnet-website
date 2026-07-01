ShieldNet Technologies Website - GitHub Pages Ready

Files included:
- index.html
- CNAME
- assets/shieldnet_logo.png
- README_HOSTING_GUIDE.txt

What is fixed:
- Logo is embedded inside index.html, so it will show even if the assets folder path has a problem.
- Mobile responsiveness improved for phone, tablet and desktop.
- Contact details updated:
  Mobile: +94769783959
  Email: ranvidud@gmail.com
  Location: Gampaha, Sri Lanka
- Motto updated:
  Connect. Protect. Perform.
- Footer copyright sentence centered.
- CNAME file added for your domain:
  shieldnettechnology.tech

Very important:
Do not open the website directly from inside the ZIP file. Extract the ZIP first, then open index.html.
For hosting on GitHub Pages, upload index.html and CNAME to the root of the repository.

Recommended GitHub repository name:
shieldnet-website

GitHub Pages settings:
Settings > Pages > Build and deployment
Source: Deploy from a branch
Branch: main
Folder: /root
Custom domain: shieldnettechnology.tech
Then enable Enforce HTTPS when available.

DNS records for your domain provider:
For root/apex domain shieldnettechnology.tech, add these A records:
@  A  185.199.108.153
@  A  185.199.109.153
@  A  185.199.110.153
@  A  185.199.111.153

For www subdomain, add this CNAME:
www  CNAME  YOUR-GITHUB-USERNAME.github.io

Replace YOUR-GITHUB-USERNAME with your real GitHub username.

DNS can take a few minutes to 24 hours to update.
