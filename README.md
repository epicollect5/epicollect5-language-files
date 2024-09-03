# Epicollect5 Language Files

## Overview

This repository provides the base English language files for the Epicollect5 mobile app. These files are intended to be used by the community to translate the app into other languages. The translation process involves copying these base files and replacing the English text with the appropriate translations.

## Provided Files

### 1. `strings-en.js`

This file contains the labels and other text elements used throughout the app. Each entry is a key-value pair, where the key is a unique identifier, and the value is the text displayed in English.

#### Example Format:
```javascript
collect_errors: 'Collect errors',
help_us_improve: 'Help us improve our app',
view_on: 'View on',
edit: 'Edit',
invite: 'Invite',
edit_remote_entries: 'Edit Remote Entries',
...
```

Keys: These should remain unchanged during translation.
Values: Translate the English text to the target language.

### `status-codes-en.json`

This file contains error messages, alerts, and notifications. It’s formatted as a JSON object, where each key corresponds to an error code, and the value is the associated English message.
Example Format:


```json
{
  "ec5_11": "Project does not exist.",
  "ec5_12": "User could not be authenticated.",
  "ec5_13": "User not authorised to view project.",
  "ec5_14": "No data attribute found in json structure.",
  "ec5_15": "Form does not exist.",
  "ec5_16": "Could not retrieve media.",
  "ec5_17": "A required owner entry for this branch does not exist.",
  "ec5_18": "A required parent form does not exist.",
  ...
}
```
Keys: Do not change these.
Values: Replace the English message with the translated text.

### 3. App Store/Play Store Description (Optional)

This is a text file named "Epicollect5 English Language Files" containing the description used for the app in the Apple App Store and Google Play Store.

Purpose: This description can also be translated to provide localized content in app stores.

### How to Translate
Copy the Files: Make a copy of the provided files for the target language. For example, if you are translating to Spanish, create files named strings-es.js, status-codes-es.json, and app-description-es.txt.
Translate the Values:
In strings-en.js, translate the English text (the values) while keeping the keys unchanged.
In status-codes-en.json, replace the English messages with the appropriate translations.

Save and Test: Ensure that the translated files are saved with UTF-8 encoding. 

Contributing

If you would like to contribute your translation to the community, please submit a zip file with your translated files to epicollect&#64;cgps.group 

Make sure to follow the same structure and format as the original English files to ensure compatibility.

Thank you for helping to make Epicollect5 accessible to a global audience!
