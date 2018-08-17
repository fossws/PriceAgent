# PriceAgent
Free/Libre Open Source Price Analysis Tool / Comparison Shopping Engine

*Note: There is no code yet. You can contribute or just wait.*

## Motivation
Most comparison shopping websites are bottom-line oriented and do not produce neutral results as they require online shops to pay percentages if they want their products listed. PriceAgent is not-for-profit and tries to become the best comparison shopping engine available for free, additionally mentioning sustainable development.

## Overview
In the long run, PriceAgent aims to cover all online and offline shops with public product catalogues.

These will be the most important parts of PriceAgent:
* comparison shopping website
* public API
* product database
* API for shops/dealers
* hosted crawler
* plugins for specific shops
* standalone apps with integrated database, crawlers, user-definable plugins

## Features
The hosted website and apps for mobile devices will offer the following features:
* global product browser
* sorting by any data available (e.g. price per unit, packaging size)
* comparing products of similar categories
* user-definable sorting algorithms (and community algorithm repository)
* product ratings by the community
* reseller ratings by the community
* offline-shopping assistant

## Architecture
The server runs Node.js and CouchDB. There will be a web app using PouchDB for offline support and enable free/libre standalone data research (without having to contact the PriceAgent server all the time). We use the x-ray library for web scraping.

## Development
After creating some specific data gathering tools (specific shop plugins), the first step will be to create the database structure and the public API. Some other specific shop plugins will follow, then the website itself will be created. The crawler follows, then standalone PriceAgent apps.

Contribution is welcome!
