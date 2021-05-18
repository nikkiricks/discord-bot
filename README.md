# The Abyss Quotes Bot

![Bot](images/bot.png "Discord Bot Screen shot")

## What it is

A personalized Discord Bot for my friends.

## But why?

We had created a `#quotes` channel where we saved one anothers funny or insightful quotes. Which was great, but I wanted a way to integrate the quotes in a more interactive way.

And this was the outcome:

![Message](images/message.png "Discord Bot Screen shot")

The user types in "-" + the name of the person they're wanting to quote and voila, you get a random quote.

This was all well and good but then I started to get sick of having to copy and paste the quotes myself. And as much as I loved my friends, I wasn't up for continuing the unpaid labor. So I decided to use a google form that they could fill out, enter the quote, and the bot could read it from the spreadsheet.

![Google spreadsheet](images/google_spreadsheet.png "Google Spreadsheet")

## API's used

- [Google Sheets for Developers API](https://developers.google.com/sheets/api/)
- [Discord.js](https://discord.js.org/?source=post_page---------------------------#/)
  ![Discord Bot](images/discord_bot.png "Discord Bot Screen shot")

## Getting Started

If wanting for personal use, you'll need to run through the Google Sheets for Developers quickstart guide, swap out the spreadsheet link, enter your personal discord bot credentials, google api credentials, and discord token.

To start, in the terminal run:

`$ node .`

## Things I Learned

- How to use the [dotenv](https://www.npmjs.com/package/dotenv) properly.
- Working with Google sheets API
- Working with Discord bots
