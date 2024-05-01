# Bug_02: Notification not received for new messages

[![Made by Adam Cegiełka](https://img.shields.io/badge/made%20by%20-Adam%20Cegielka-blue.svg?style=flat-square)](https://adamcegielka.pl)
[![Telegram](https://img.shields.io/badge/Testing%20App-Telegram-24A1DE.svg?logo=telegram)](https://web.telegram.org)

<br>

| # | Elements | Description |
| --- | --- | --- |
| 1 | ID: | Bug_02|
| 2 | Title: | Notification not received for new messages |
| 3 | Environment: | Android 14, Telegram v10.12.0 on Samsung Galaxy S24 Ultra 5g 256gb |
| 4 | Preconditions: | User is logged in, has notifications enabled in both the Telegram app and Android settings, app is running in the background |
| 5 | Steps for reproduction | 1. Ensure the Telegram app is running in the background<br>2. Send a message to the user from another Telegram account<br>3. Observe the notification area on the device |
| 6 | Expected Result: | A notification appears for the new message with a preview and sound alert |
| 7 | Actual Result: | No notification appears on the device despite new messages being received.<br>Error `Code: N1020` (NotificationServiceFailure - Background app refresh or notification service failed). Logs suggest a failure in triggering the Android notification service when the app is backgrounded. |
| 8 | Attachment: | `Screenshot of the crash moment` |
| 9 | Severity: | High |
| 10 | Priority: | High |
