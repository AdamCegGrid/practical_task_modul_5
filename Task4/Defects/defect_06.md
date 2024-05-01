# Bug_06: Search function fails with special characters

[![Made by Adam Cegiełka](https://img.shields.io/badge/made%20by%20-Adam%20Cegielka-blue.svg?style=flat-square)](https://adamcegielka.pl)
[![Telegram](https://img.shields.io/badge/Testing%20App-Telegram-24A1DE.svg?logo=telegram)](https://web.telegram.org)

<br>

| # | Elements | Description |
| --- | --- | --- |
| 1 | ID: | Bug_06|
| 2 | Title: | Search function fails with special characters |
| 3 | Environment: | Android 14, Telegram v10.12.0 on Samsung Galaxy S24 Ultra 5g 256gb |
| 4 | Preconditions: | User is logged in, app is updated to the latest version |
| 5 | Steps for reproduction | 1. Open Telegram<br>2. Tap on the search bar at the top of the chats screen<br>3. Enter a search term that includes special characters (e.g., "@JohnDoe_#!") |
| 6 | Expected Result: | The app should either return search results containing the special characters or display a message stating no results found.  |
| 7 | Actual Result: | The app crashes, or a loading error occurs, failing to return any search results.<br>Error `Code: S4050` (SearchFunctionException - Invalid character error). |
| 8 | Attachment: | `Screenshot of the crash moment` |
| 9 | Severity: | Medium |
| 10 | Priority: | Medium |
