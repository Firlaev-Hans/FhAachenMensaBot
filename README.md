# FH Aachen Mensa Bot
<div>
  <img alt="Lines of code" src="https://img.shields.io/tokei/lines/github/philpinsdorf/fhaachenmensabot?label=Lines%20of%20Code&style=for-the-badge">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/philpinsdorf/fhaachenmensabot?style=for-the-badge">
  <img alt="GitHub" src="https://img.shields.io/github/license/philpinsdorf/fhaachenmensabot?color=red&style=for-the-badge">
</div>  

</br>

A small Telegram bot that will send you a message with the canteen meals of the day. \
Now working for all Canteens in Aachen. \
Created during another boring TI lecture. \
Feel free to create pull-requests.

# How to use
Follow this link: http://t.me/fhaachenmensabot \
Press on **Start** \
You'll get all relevant information through the bot.

# Commands
| Command | Description |
|---|---|
| /start | Subscribe for daily canteen updates. |
| /stop | Unsubscribe from daily canteen updates. |
| /request | Immediately sends you todays meals. |
| /today | Immediately sends you todays meals. |
| /tomorrow | Immediately sends you tomorrows meals. |
| /select | Select your canteen. |
| /share | Get QR-Code for sharing the Bot. |
| /code | Get Link to GitHub repo. |

# ToDo
- [x] Clean up code
- [x] Sanitize usernames
- [x] Rewrite in TypeScript
- [x] Select your canteen
- [x] Add all canteens in Aachen
- [x] Get tomorrows Meals
- [x] Request QR-Code for sharing

# Attention
The new meals are loaded at 4:30am. Any requests before that time will give you yesterdays meals.

# Author
Phil Pinsdorf
