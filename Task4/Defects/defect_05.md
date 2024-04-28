# Bug_05: Incorrect timestamp on messages

[![Made by Adam Cegiełka](https://img.shields.io/badge/made%20by%20-Adam%20Cegielka-blue.svg?style=flat-square)](https://adamcegielka.pl)
[![Telegram](https://img.shields.io/badge/Testing%20App-Telegram-24A1DE.svg?logo=telegram)](https://web.telegram.org)

<br>

| # | Elements | Description |
| --- | --- | --- |
| 1 | ID: | Bug_05|
| 2 | Title: | Incorrect timestamp on messages |
| 3 | Environment: | Android 14, Telegram v10.12.0 on Samsung Galaxy S24 Ultra 5g 256gb |
| 4 | Preconditions: | User is logged in, system time is correctly set |
| 5 | Steps for reproduction | 1. Open Telegram<br>2. Send a message to any contact<br>3. Observe the timestamp next to the sent message |
| 6 | Expected Result: | The timestamp should correctly reflect the time the message was sent, based on the system's clock |
| 7 | Actual Result: | Messages show a timestamp that is several hours ahead of the actual time |
| 8 | Attachment: | `Screenshot of the crash moment` |
| 9 | Severity: | Medium |
| 10 | Priority: | Medium |
