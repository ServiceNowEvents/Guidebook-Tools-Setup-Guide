# Visual Studio Code and GitHub - Setup Guide
Visual Studio Code and GitHub setup guide for K18 Lab and CC Workshop speakers.

## Overview
K18 Marks a big change in how we deploy lab guides to our attendees as we move from a printed word document to an electronic and online guide, powered by the MarkDown syntax.

The objectives of this guide is to help our speakers properly configure the Visual Studio and GitHUB tools that are required to create and publish guides. 

Please pay special attention to the notes and tips provided. 

For additional setup assisttance, please send your help requests to [#####@servicenow.com](mailto:gerald.beaulieu@servicenow.com). 

Topics Covered in this Guide: 
* GitHub Configuration
* Visual Studio Code Installation
* Org and Guide Template Access
* Cloning Guide Locally
* Save and Upload Changes


Use Heading 1/H1 _only_ for lab titles.  All content under H1 will render as a single page when digital guidebooks are published.

# GitHub Configuraiton
## Create and Share Account
Follow these steps to create and share your GitHub acccount:

1. If you don't have a GitHub account already, navigate to .  [https://github.com/join](https://github.com/join) to create an account. The email address you submit shoudl be your ServiceNow email address. The user name can be whatever you wish.
1. Send the user name defined in step 1 to [Jason McKee](mailto:jason.mckee@servicenow.com) Jason will submit your name to the GitHub org created for K18. An inviation will be sent to your email that you must accept.

Beyond standard Markdown, we have a few conventions you need to follow for your guidebook to render properly

## Local Configuraiton
The following steps and terminal window commands need to be run on each machine to ensure GitHub is configured correclty to run with VS Studio and to properly access the GitHub repository. 

1. Load a terminal session from your computer
1. From the prompt type: Git

    * This may or may not initiate an installation process. If it does, follow the prompts to install. If it doesn't, then it should return a set of potential commands accessible to GIT.
1. Set your user name with this command. Replace "Mona Lisa" with your name 
* git config --global user.name "Mona Lisa"
1. Set your email address with this command. 
* git config --global user.email "email@example.com"
    
# VS Studio Configuration
## Install Visual Studio Code
Visual Studio Code will be used as the front-end editor for the guide. A template will be provided to you as a framework and will be discussed later in this guide. Follow these steps to install Visual Studio Code
1. Load Self Service from your computer
1. Select Featured from the categories
1. Run the "Grant Temporary Admin Rights" option. This will ensure the application can be installed on your computer.
1. Select Applications from the Categories list
1. Install the option named Visual Studio Code

# Org and Guide Template Access

## Submit User Name
As a K18 Lab or CC Workshop speaker, you will require access to the GitHub org set up as the repository for our guides. In addition, you will also need permission to download the guide template you are assigned to. Follow these steps to gain access to the org. 

1. If you haven't already, send your registerd GitHub user name to [Jason McKee] (mailto:jason.mckee@servicenow.com) . Jason will submit your name to the GitHub org created for K18. An inviation will be sent to your email that you must accept.
1. Open the invitation email from "GitHub" or "jasontmckeesn" to join the ServiceNow Events organization. 
1. Click the "Join ServiceNowEvents" button
1. Repeat these steps for each GitHub invitation you receive. 

# Cloning Guide Locally
## Downloading Guide Template
Now that you have access to the repository and have acceppted the invitation, it's time to start working on your guide. But first, you need to download the guide from the repository. Follow these steps to download it. This step is only required once. 

1. Log into your GitHub account. 
1. Under the "Your Repositories" tile on the left, click the lab guide repoistory for you specific lab. 
1. Once loaded, click the green "Clone or Download" button. 
1. From the small dialog that opens, copy\paste the URL. (Note: You an also click the clipboard icon in the dialog)
1. Swtich back to VS Studio Code
1. Select the "View|Command Palette" menu option
1. From the sub menu that opens, slect "Git:Clone"
1. Paste in the URL into the dialog and press enter
1. Type in a local directory path to store the file and press Enter. A sub folder is recommended.
1. Selet "Open Repository"
1. It may prompt you for an ID and Password. Plug in your GitHub ID and Password. 

# Save and Upload Changes
## Save Changes
Like any document, it's important to save your chagnes regularlly. To do this follow these steps. 

1. From the File Menu select "Save". That's it! 

## Upload Changes to GitHub
Saving the file from the menu only saves it locally. You also need to push it up to the GitHub site, but it's not necessary to do this every time. Just remember to upload after a major change to the doc and final changes of course. Follwow these steps to properlly upload your guide back to GitHub

1. Select teh icon in the left that looks like a "Y". This is your source control access. 
1. Type in a short descritpion of the recent changes made. Somethink like "Added new lab 3 to guide". Press the checkmark. 
1. It may prompt you with a dialog to "Stage" yur changes. Press "Yes"
1. 


## Lists
While Markdown supports nesting ordered and un-ordered lists, please avoid using nested lists in your guide book.  This is to avoid conflicts with how we style (or rather, don't) nested lists on the Developer Portal.

1. Use numbered lists for task steps
1. You don't have to manually number each step

    But sometimes you need paragraphs between steps.  In those cases, indent your paragraphs with a tab.

    Multiple paragraphs are OK too.

1. And markdown will pick up numbering where you left off.

# Images
## General



## Using Paste Image in Visual Studio Code

Link to howto documentation here:

# Help!

Office Hours once again