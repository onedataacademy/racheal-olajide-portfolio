# Racheal Olajide Portfolio

I prepared this folder so the complete website can be kept, deployed and updated easily.

## Files

- index.html: page content, sections, navigation and contact form.
- style.css: colours, typography, layouts and mobile styles.
- script.js: navigation, experience filters and Web3Forms submission.
- assets/: portrait and downloadable CV.

## Preview

Open index.html in a browser. An internet connection is needed for Google Fonts and contact form delivery.

## GitHub and Cloudflare Pages

1. Create a GitHub repository named racheal-olajide-portfolio.
2. Upload the contents of this folder, with index.html at the repository root.
3. In Cloudflare, open Workers & Pages, create a Pages project and connect the repository.
4. Choose no framework, leave the build command empty and use the repository root as the output directory.
5. Deploy, then check the mobile layout, CV download and contact form on the live address.

## Contact form

The supplied Web3Forms public access key is configured in script.js. Messages are delivered to the recipient registered with that key. Confirm that recipient in Web3Forms before sharing the website. A successful response displays a confirmation and clears the form; failed delivery displays an error and the direct email option.

The key has been connected in the code. No live test message was sent during packaging. After deployment, send one test enquiry and verify it arrives in the intended inbox.

## Updates

Edit the relevant file and commit it to GitHub. Cloudflare Pages will redeploy connected changes automatically. Keep the assets folder alongside index.html.

## Photography

Illustrative stock photography from Unsplash is included locally. These images illustrate subject areas and are not presented as Racheal’s own projects.

- Research: https://images.unsplash.com/photo-1434030216411-0b793f4b4173
- Analytics image: https://images.unsplash.com/photo-1551288049-bebda4e38f71
- Nutrition image: https://images.unsplash.com/photo-1490645935967-10de6ba17061
