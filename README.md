# Nail Art Studio – Price List & Daily Sales Counter

A simple one-page web app for a nail art studio. Prices are in PKR, and a daily
sales counter keeps track of services done and money earned.

## Features
- Price list in PKR with a photo for each service (tap the picture to add your own)
- + / − buttons to record each sale
- Live totals for services done and sales for the day
- Resets automatically each day, with the last 7 days of history
- Works offline, with no server or install needed

## Pages
- `index.html` – Nail Art Studio (main page)
- `chai.html` – Chai stall version
- `wigs.html` – Hair wigs shop version

## Use it
Open `index.html` in any browser.

## Put it online with GitHub Pages
1. Upload all files to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Branch**, choose `main` and `/ (root)`, then click **Save**.
4. After a minute your site is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Edit prices
Open the HTML file in a text editor and change the `MENU` list near the top of
the `<script>` section.

## Note
Sales and photos are saved in the visitor's own browser (localStorage). They are
not shared between devices.
