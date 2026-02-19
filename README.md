# MindsLinked Website

Landing page for the MindsLinked app.

## Deploy to GitHub Pages

1. Create a new GitHub repo named `mindslinked-landing` (or use your GitHub Pages repo `username.github.io`)
2. Push this folder to the repo
3. Go to Settings → Pages → Source: main branch → Save
4. Site will be live at https://username.github.io/mindslinked-landing

## Custom Domain (mindslinked.com)

1. Add a `CNAME` file with content: `mindslinked.com`
2. In your domain registrar, add a CNAME record: `www → username.github.io`
3. For apex domain, add A records pointing to GitHub Pages IPs:
   185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
4. Enable "Enforce HTTPS" in GitHub Pages settings
