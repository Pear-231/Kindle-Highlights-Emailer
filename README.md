# Random-Kindle-Highlights-Emailer

# What does it do?
Similar to the random kindle highlights emailing service Readwise, this Google Sheets document will send you a daily email containing a random highlight, the attached note and the book they come from, using your kindle clippings file.

**[Get the Random Kindle Highlights Emailer here!](https://docs.google.com/spreadsheets/d/1_NqiNolCmhEPIZVdCnyXzpl5wjWRFEmIVNW-5kFWEAo/edit?usp=sharing)** 

**To use all the features of this document a google account is required.*
  
# Instructions:
**1) Go to 'File' > 'Make a copy', to save the Portfolio Tracker to your Google Drive.**

**2) Adding your kindle clippings file.**

*To get your clippings file from your kindle, and import them into the spreadsheet, follow these steps:*

  - Go to the website https://www.clippings.io/, make an account, click import, and follow the instructions for the method you wish to import your clippings. (I use the 'Kindle 'My Clippings.txt'' method)
  - Once your clippings are imported, go to 'Export' and choose 'Excel 2007' and download the file.
  - Open the downloaded 'clippings_export' file, copy the all data including all headings.
  - Open the Random Kindle Highlights Emailer Template document, click on the sheet 'Paste Clippings Here' and paste the data into cell A1 to replace the template content.
  - Press ctrl+f, press the 3 dots settings icon for more options, in 'Find' type 'Notes: ' (make sure the space space after the : is included), for 'Search', change 'All sheets' to 'Specific range', select column I (the notes column), click 'Replace All' and 'Done'. 
  
  **3) Setting up the automatic emailer.**

*To set up the automatic daily emails and test the emailer, follow these steps:*

  - Go to the 'Email Content' sheet, in the cell that contains 'youremailgoeshere@email' type your email address.
  - To test the 'Send Email' button, press it, if a box appears retuesting authorisation, click continue, choose an email address, click advanced, click 'go to Random Kindle Highlights Emailer (unsafe) - click Allow. To receive a test email press the 'Send Email' button and check your emails.
  
    *Example Email:*

![Image](https://drive.google.com/file/d/10Aic-a53meatVaOhXKu-cNljOgbuH0X9)
  
  - Go to 'Tools' > 'Script editor'. This is where the code for the automation is stored.
  - Click the clock icon on the top bar or go to 'Edit > Current Project Triggers'.
  - Click 'Add Trigger': Under 'Choose which function to run' select 'highlightsEmail', under 'Select event source' select 'Time-driven', under 'Select type of time based trigger' select 'Day timer', under 'Select time of day' select the time of day you want to receive the automatic email, click save. If a screen appears that reads 'This app isn't verified', click 'Advanced' > 'Go to portfolio Scripts (unsafe)' > 'Allow'.
  
The Random Kindle Highlights Daily Automatic Emailer is now set up and running.
  
 
