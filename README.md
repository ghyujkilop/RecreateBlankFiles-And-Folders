Prerequisites:

A Text Editor (I personally use Notepad++)

Python 3.x (https://www.python.org/downloads/)

WizTree: https://diskanalyzer.com/

Make a folder that we'll use that contains your scripts & csv data. This forlder is referred to as "Blue Lagoon" below.



Preparation:

1. Open it up and select the folder names you wish to backup, then select File > Export to .CSV File... and save this in Blue Lagoon.

NOTE: You can do this with as many CSV files as you like. It will just be more time consuming when it comes to restoring. So best to select main directories.

2. Open up your PowerWorking.py in a text editor, then change your "C:\Blue Lagoon\My Folders.csv" to suit your csv and filename.

3. Similarly, in the same .py file, change "C:\Blue Lagoon Processed" path to a folder you want to see your new blank files & folders in.

4. After you've done that, open CMD as admin, then locate to your folder that you have all these files in, and type into CMD (without quotes) "python PowerWorking.py"

5. Now you're done! You now have copies of your whole PCs file structure for exactly 0kbps!


Optional:

If you have more than one .csv, just keep updating and/or changing the paths to continuously reflect your data in different ways.


Use Case example:

I had made a backup recently, and realized it didn't include all my files and folders. I then saved these blank files as essentially as "living" version of what I had on my PC,
so I could go back and look over it to see if there were any files that I missed. Also, my backup software didn't backup files I had in it lol, so when I went to erase all/
reinstall windows (fresh/clean install) only to THEN realize that my software wasn't backing up EVERYTHING I wanted. So it's good I had this structure, to help me see/remember
what files I have and are missing.

Example of what an end result could look like for you:

![image](https://github.com/user-attachments/assets/1d409de6-ff7a-43d4-9271-5bf3cbdde7e8)


Warnings about this; this does NOT replace your actual data. DO NOT USE TO REPLACE YOUR ACTUAL DATA!!! This of it like an imitation, or like a decoy of your actual info.

None of these files with actually work or open (except for the folders of course) because they have no real data in them.
