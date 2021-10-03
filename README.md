# Amazon-price-tracker-app

This is a JavaScript application which scrapes off prices from Amazon's site and sends an email to the host when price of a particular item drops
below a set threshold. Scraping has been implemented using nightmare library, sendgrid has been used to implement mailing services.
dotenv library is used to handle the .env files.

### 🚀️ Setting up 

### `npm i nightmare @sendgrid/mail` 
To import nightmare and sendgrid libraries.




### `npm i dotenv`
To import dotenv library.

Api key from sendgrid copied stored in a variable inside .env file and set in parser.js.

Set up a mailing service where mail can be received. [temp-mail.org](https://temp-mail.org/en/) is a good option.

Simillarly, select an email from where the alert will be send.

### `node parser.js https://www.amazon.in/itemlink price_threshold`
To run the app.

This project has been completed by following [Web Dev Simplified](https://www.youtube.com/watch?v=H5ObmDUjKV4) video from YouTube.


### 📑️ Further Documentation
[docs.sendgrid](https://docs.sendgrid.com/for-developers/sending-email/api-getting-started) from Twilio has everything mentoned to setting up Sendgrid api.
