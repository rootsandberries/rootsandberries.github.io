# Deduplicating searches for systematic reviews using Zotero profiles

Because Zotero cannot deduplicate within collections, only within an entire library, creating a separate Zotero profile for each systematic review can make it easier to manage the deduplication process. 

Zotero detects duplicates as follows (see [this page](https://www.zotero.org/support/duplicate_detection) for more information):

> Zotero currently uses the the title, DOI, and ISBN fields to determine duplicates. If these fields match (or are absent), Zotero also compares the years of publication (if they are within a year of each other) and author/creator lists (if at least one author last name plus first initial matches) to determine duplicates.

### Step 1: Open Zotero Profile Manager
To create a new profile on a computer that already has a Zotero instance (for example, your own personal Zotero library), open the Zotero profile manager via the command line as follows (see [this page](https://www.zotero.org/support/kb/multiple_profiles) and [this page](https://www.zotero.org/support/debug_output#real-time_debug_output) for more details):

For Mac:
* Open Terminal via Spotlight or /Applications/Utilities.
* Paste "/Applications/Zotero.app/Contents/MacOS/zotero -P", without quotes, into the Terminal window. Note the space before the hyphen.
* Press Return

![Open Zotero Profile Manager in Mac](https://rootsandberries.github.io/systrev/terminal_zotero.png)

For Windows:
* Press Windows + R or search for 'run' to open the Run window. Click Browse and locate Zotero (typically located at "C:\Program Files (x86)\Zotero\zotero.exe")
* Select the appropriate file and click Open.
* In the Run box, append " -P" (without quotes) to the very end of the text, after any quotes if present. Note the space before the hyphen.
* Click OK.

---

### Step 2: Create a new Zotero profile
* In the pop-up profile manager that appears, click Create Profile and then Continue.

![Create new Zotero profile](https://rootsandberries.github.io/systrev/zotero_profile.png)

* Name your new profile and click Done.
* You can uncheck the box next to "Use the selected profile without asking at startup". This will allow you to choose which profile you want to open when you launch the Zotero desktop application. 
* With the new profile highlighted, click Start Zotero. You may be prompted to install the Word plugin or create and online account, but neither of these are necessary if you're only using this profile to deduplicate searches. 

---

### Step 3: Import database searches into your new library

* Import individual search results files by choosing File-->Import. Zotero accepts numerous file types including .ris and .bib.
* New collections will automatically be created for each file import and will be named with the file name. 
* If needed, rename the collections with the database name and date of search by right clicking and choosing Rename collection.
* The number of items in each search can be seen by clicking on the folder. The number of items in the folder will appear in the far right-hand pane. Verify that the number of items reflects the number of search results for each database search.

---

### Step 4: Detect and merge duplicates

* Scroll to the bottom of your collection folders and click on Duplicate Items.
* Click on the items in the middle pane. Merge item records when they appear to be a true duplicate. Check for differences in the metadata using the duplicate drop downs next to the fields in the right-hand pane. For more information and screenshots, see [this page](https://www.zotero.org/support/duplicate_detection). 
* After merging, the number of items in your individual database search collections will not have changed, reflecting the original number of records found in that database. However, the total number of items in the Zotero library will have declined by the number of duplicates that have been merged. Click on the brown My Library collection at the top of your collection folders in the left-hand pane to determine the new total. You can always add up the number of items in individual collections and subtract the My Library total to determine how many duplicates were removed. 



