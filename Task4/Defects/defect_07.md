# Bug_07: Group chat members not able to send messages

[![Made by Adam Cegiełka](https://img.shields.io/badge/made%20by%20-Adam%20Cegielka-blue.svg?style=flat-square)](https://adamcegielka.pl)
[![Telegram](https://img.shields.io/badge/Testing%20App-Telegram-24A1DE.svg?logo=telegram)](https://web.telegram.org)

<br>

| # | Elements | Description |
| --- | --- | --- |
| 1 | ID: | Bug_07|
| 2 | Title: | Group chat members not able to send messages |
| 3 | Environment: | Android 14, Telegram v10.12.0 on Samsung Galaxy S24 Ultra 5g 256gb |
| 4 | Preconditions: | User is logged in, part of a group chat with more than 10 members |
| 5 | Steps for reproduction | 1. Open Telegram<br>2. Navigate to a group chat<br>3. Try to send a message by typing in the message field and pressing the send button |
| 6 | Expected Result: | The message should be sent successfully and appear in the group chat for all members to see. |
| 7 | Actual Result: | The send button does not respond, and the message does not appear in the chat; no error message is displayed.<br>Error `Code: G1001` (GroupMessageFailure - Failed to process message send request). |
| 8 | Attachment: | `Screenshot of the crash moment` |
| 9 | Severity: | High |
| 10 | Priority: | High |
