As of version 1.0.0.14 Lootun offers support for the loading of custom Language Files.

### 1. Language File Example:
The "english_example.txt" file located in the "Languages" folder of the Lootun directory represents how a Language File for Lootun should look. Each string is contained within its own line of text and is comprised of a key and a value separated by "=".

### 2. Creating a Language File:
To begin, import "english_example.txt" into a spreadsheet or localisation software of your choice, making sure to separate the text using the "=" character. 
Once imported, all text to the right hand side of the "=" character can be translated.
Once the translation is complete, export the file making sure the "=" character is reinserted between the key and the value string.
Languages Files must be stored within the "Languages" folder of the Lootun directory and must use the ".txt" extension in order to be presented as a Language option within Lootun.
Language Files should be encoded with UTF-8.

### 3. Variables:
Many text strings used by Lootun contain variable data that is applied at runtime. This variable data is represented as bracketed numbers, for example: "{0} Gold Coins" where "{0}" is replaced by a number at runtime.
These bracketed numbers must remain within the translated text though the positioning of them can change.

### 4. Supported Characters:
Lootun currently provides support for Latin, Greek, Cyrillic, Chinese (simplified and traditional), Japanese, Korean, and Thai character sets.

### 5. Uploading to the Steam Workshop:
In order to upload a Language File to the Steam Workshop you must launch Lootun with the "-workshop" launch option set. This can be done through Steam by right clicking Lootun and navigating to Properties -> General -> and adding "-workshop" to the Launch Options.
Once set, you should be able to access the Workshop Upload Menu from the Main Menu allowing you to upload or update a Workshop Item.

Selecting a Language File to upload will generate a short summary of the file, listing the number of valid, missing for misformed language strings present. A Language File can be uploaded with missing or misformed strings but these strings will be replaced by the default English strings in game.
Selecting the "Print Missing Strings" button will create a list of each missing or misformed string for the selected Language File.
