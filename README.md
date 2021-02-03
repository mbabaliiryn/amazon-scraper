# amazon-scraper

In this assignment, I'm scraping an amazom promo codes and their links

## Built with 
- JavaScript
- Puppeteer
- dotenv

**Process:**
1. opens a headless chromium browser
2. fills in login credentials and clicks signin button
3. scrolls to the bottom after a delay of 1 second and extracts promo code items
4. when the target number of items to scrape is reached, it closes the browser
5. logs scrapped items in the console.

## Screenshots

![scrapped_data](https://user-images.githubusercontent.com/44978186/106746004-f59c6f00-6632-11eb-9eec-540a85f2f804.png)


![terminal_scraped_data](https://user-images.githubusercontent.com/44978186/106746067-0f3db680-6633-11eb-8ab9-982e4191394d.png)



<!-- ABOUT THE PROJECT -->
## Get started

clone the repository

- `cd` into project directory.
- Run `npm install` to install all the required dependancies.

-  Add a `.env` file in your root directory and the following:

EMAIL= your email
PASSWORD= your password
SITE_URL= link to your amazon promo codes page

- Run `node index.js` in your terminal.

 ## Author

👤 **mbabaliiryn**

- Github: [mbabaliiryn](https://github.com/mbabaliiryn)
- Linkedin: [mbabaliiryn](https://www.linkedin.com/in/mbabali-iryn/)


## Show your support

Give a ⭐️ if you like this project!


## 🤝 Contributing

Contributions, issues and feature requests are welcome!