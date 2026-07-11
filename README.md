# The Skin Edit — Static Website

## Edit before publishing

The WhatsApp number `919016325595` is already wired into the hero button, the
contact card and the floating chat button. To change it, search `index.html`
for `919016325595` and replace every occurrence (country code, no `+`).

Still to do in `index.html`:

1. Replace `https://www.instagram.com/` (marked with a `TODO` comment) with the
   clinic's real Instagram profile URL.

2. Update any treatment text, FAQ answers or location details you want.

## Test locally

Simply double-click `index.html`.

## Fastest deployment options

### Netlify Drop
1. Go to Netlify Drop.
2. Drag the entire `theskinedit-static-site` folder.
3. Add your custom domain in Domain Management.

### Vercel
1. Create a GitHub repository.
2. Upload these files to the repository root.
3. Import the repository into Vercel.
4. Framework preset: `Other`.
5. Add `theskinedit.co.in` and `www.theskinedit.co.in` under Domains.

### Existing hosting/cPanel
Upload all three files inside your website's `public_html` directory.

## Important DNS note

Your Google Workspace email will keep working as long as you do not remove or overwrite Google's MX records.

For website hosting, add only the A/CNAME records provided by your hosting provider.
