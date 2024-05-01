# Bug_08: Automatic language translation not working

[![Made by Adam Cegiełka](https://img.shields.io/badge/made%20by%20-Adam%20Cegielka-blue.svg?style=flat-square)](https://adamcegielka.pl)
[![Telegram](https://img.shields.io/badge/Testing%20App-Telegram-24A1DE.svg?logo=telegram)](https://web.telegram.org)

<br>

| # | Elements | Description |
| --- | --- | --- |
| 1 | ID: | Bug_08|
| 2 | Title: | Automatic language translation not working |
| 3 | Environment: | Android 14, Telegram v10.12.0 on Samsung Galaxy S24 Ultra 5g 256gb |
| 4 | Preconditions: | User is logged in, translation feature is enabled in settings |
| 5 | Steps for reproduction | 1. Open Telegram<br>2. Receive a message in a foreign language (e.g., Spanish)<br>3. Tap on the message<br>4. Select 'Translate' from the options |
| 6 | Expected Result: | The message should be translated into the user’s default language (e.g., English) and displayed correctly. |
| 7 | Actual Result: | The translation feature does not activate; the message remains in the original language without any indication of translation attempt.<br>Error `Code: T4010` (TranslationServiceError - Failed to invoke translation service). |
| 8 | Attachment: | `Screenshot of the crash moment` |
| 9 | Severity: | Medium |
| 10 | Priority: | Medium |
