# SE762-IS300-Project
Team members: Cole Eruini-Bennett, Maric Kim, Vincent Lo, Avneet Sharma, Joel Shin, Justin Teo, Jigao Zeng

## Process
This is a RPA process that automates finding assessment differences between the University of Auckland Digital Course Outline (DCO) pages and its corresponding Canvas page. It outputs what is displayed in both DCO and Canvas pages and presents a summary of the differences in a Word document. 

## Project dependencies
1. UI path packages "UIPath.Word.Activities". To get this UI path package, add it to UI path via the "Manage Packages" function in UI path and search "UIPath.Word.Activities".
2. The RPA process only compatible with the Windows platform and Chrome web browser.
3. Ensure your Chrome web browser has the UIpath extension. Details on how to obtain the chrome extension can be found [here](https://docs.uipath.com/installation-and-upgrade/docs/studio-extension-for-chrome). 
4. The RPA process assumes you are logged in to Canvas in the Chrome browser. An easy way to achieve this is to have a Chrome window open and log in to Canvas there.
5. The RPA process requires an input file to run. An example format of this file is shown in example.xlsx. REQUIRED: only supply courses that you have Canvas access for.

## How to run
1. Import all the files to a UI path project.
2. Ensure ALL above project dependencies are met.
3. Run Main.xaml.

### Notes:
The log file can be found in the root directory of the project inside the Logs folder called logs.txt.
