# luckypigstudio.com — BaoTio Website

## File Structure
```
/
├── index.html          ← Main website
├── app-ads.txt         ← Ad network verification (MUST be at root)
└── screenshots/        ← App screenshots folder
    ├── screen1.png     ← Out of numbers screen
    ├── screen3.png     ← Home screen (pig + button)
    ├── screen4.png     ← Lucky number result (0830)
    ├── screen7.png     ← Toto numbers result
    └── screen8.png     ← Previous numbers list
```

## GitHub Pages Setup

1. Create a new repository named exactly: `luckypigstudio.github.io`
   (or any repo name, then enable Pages in Settings)

2. Upload all files maintaining the folder structure above

3. Go to Settings → Pages → Source: Deploy from branch → main → / (root)

4. Your site will be live at: https://luckypigstudio.github.io

## Namecheap Custom Domain Setup

1. In Namecheap → Domain List → luckypigstudio.com → Manage → Advanced DNS
2. Add these DNS records:
   - Type: A | Host: @ | Value: 185.199.108.153
   - Type: A | Host: @ | Value: 185.199.109.153
   - Type: A | Host: @ | Value: 185.199.110.153
   - Type: A | Host: @ | Value: 185.199.111.153
   - Type: CNAME | Host: www | Value: luckypigstudio.github.io

3. In GitHub Pages settings → Custom domain → enter: luckypigstudio.com
4. Check "Enforce HTTPS" once DNS propagates (can take up to 24 hours)

## Screenshots
Rename your app screenshots and place them in a /screenshots folder:
- screen1.png = Out of numbers (Image 1 from your uploads)
- screen3.png = Home screen Chinese (Image 3)
- screen4.png = Lucky number 0830 (Image 4)
- screen7.png = Toto result (Image 7)
- screen8.png = Previous numbers (Image 8)

## App Store Link
Once your iOS app is live, update the App Store button href in index.html.
Search for "Coming to App Store" and replace the # with your App Store URL.

## Email
Update support@luckypigstudio.com to your real support email in index.html.
