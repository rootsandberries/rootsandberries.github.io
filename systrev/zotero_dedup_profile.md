# Deduplicating searches for systematic reviews using Zotero profiles

Because Zotero cannot deduplicate within collections, only within an entire library, creating a separate Zotero profile for each systematic review can make it easier to manage the deduplication process. 

Zotero detects duplicates as follows (see [this page](https://www.zotero.org/support/duplicate_detection) for more information):

> Zotero currently uses the the title, DOI, and ISBN fields to determine duplicates. If these fields match (or are absent), Zotero also compares the years of publication (if they are within a year of each other) and author/creator lists (if at least one author last name plus first initial matches) to determine duplicates.

### Step 1 Open Zotero Profile Manager
To create a new profile on a computer that already has a Zotero instance (for example, your own personal Zotero library), open the Zotero profile manager via the command line as follows (see [this page](https://www.zotero.org/support/kb/multiple_profiles) and [this page](https://www.zotero.org/support/debug_output#real-time_debug_output) for more details):

For Mac:
* Open Terminal via Spotlight or /Applications/Utilities.
* Paste "/Applications/Zotero.app/Contents/MacOS/zotero -P", without quotes, into the Terminal window. Note the space before the hyphen.
* Press Return

For Windows:
* Press Windows + R or search for 'run' to open the Run window. Click Browse and locate Zotero (typically located at "C:\Program Files (x86)\Zotero\zotero.exe")
* Select the appropriate file and click Open.
* In the Run box, append " -P" (without quotes) to the very end of the text, after any quotes if present. Note the space before the hyphen.
* Click OK.

---

### Step 2 Create a new Zotero profile
* In the pop-up profile manager that appears, click Create Profile and then Continue.
* Name your new profile and click Done.
* You can uncheck the box next to "Use the selected profile without asking at startup". This will allow you to choose which profile you want to open when you launch the Zotero desktop application. 
* With the new profile highlighted, click Start Zotero. You may be prompted to install the Word plugin or create and online account, but neither of these are necessary if you're only using this profile to deduplicate searches. 

---

### Step 3 Import database searches in your new library

---

### Step 4 Detect and merge duplicates



