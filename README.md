# Dharma Bharti Public Welfare Trust — deployment package

Static, responsive multi-page website for DBPWT.

## Included
- `index.html` — homepage
- `about.html` — purpose, history, offices and beneficiaries
- `work.html` — work areas
- `foundations.html` — Fundamental Duties, Commitment to Global Peace and SDGs
- `leadership.html` — trustees and governance
- `contact.html` — participation/contact page
- `assets/styles.css` — site styles
- `assets/script.js` — navigation/interactions
- `404.html` — fallback page
- `robots.txt` — crawler policy
- `.nojekyll` — keeps GitHub Pages from attempting Jekyll processing

## Important privacy note
The public deployment package intentionally excludes the scanned Trust Deed PDF. The deed contains personal identifiers, addresses, contact details and signatures that should not be placed in a public GitHub repository or public website without an explicit privacy/legal review.

## Cloudflare Pages
Recommended for this static site.

1. Create a GitHub repository and upload the contents of this folder to the repository root.
2. In Cloudflare Dashboard, open **Workers & Pages** → **Create application** → **Pages** → **Import an existing Git repository**.
3. Select the GitHub repository.
4. Production branch: `main`
5. Build command: `exit 0`
6. Build output directory: `.`
7. Deploy.

Cloudflare will provide a `*.pages.dev` address and can automatically redeploy when changes are pushed to GitHub.

## GitHub Pages alternative
1. Push this folder to a GitHub repository.
2. Repository → **Settings** → **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Branch: `main`; folder: `/ (root)`.
5. Save and open the generated GitHub Pages URL.

## Before production launch
- Connect the contact form to a secure form/email backend.
- Verify official email, phone, registration and tax/donation details.
- Add Privacy Policy / Terms / Cookie notice as legally required.
- Add the approved DBPWT logo and photography.
- Review all public biographies and office-holder details.
- Do not publish Aadhaar numbers, private residential addresses, personal phone numbers, signatures or identity-document scans.
