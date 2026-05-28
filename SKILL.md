CLAUDE SKILL: BUILD AND PUBLISH AN ACADEMIC RESOURCE WEBSITE FOR A CONFERENCE WORKSHOP USING ANTIGRAVITY AND GITHUB

WHAT THIS SKILL DOES

This skill guides you through creating a free, public website to share academic documents (PDFs, Word files, slide decks) — using Antigravity AI to do the technical work for you. No coding knowledge is required. You only need to describe what you want in plain English.

WHAT YOU NEED BEFORE YOU START
A folder on your computer containing the files you want to share (PDFs, Word documents, PowerPoint slides, a banner image if you have one)

A free GitHub account (create one at https://github.com)

A new, empty GitHub repository created at https://github.com/new

Choose a clear name (this becomes part of your website address)
Example: if your username is ILOVEICECREAM and repo is named MyWorkshop, your site will be at: https://ILOVEICECREAM.github.io/MyWorkshop/
Antigravity open and ready to chat

BACKGROUND: WHAT THESE TOOLS ARE

ANTIGRAVITY An AI assistant that can take actions on your computer — reading files, writing website code, and running technical commands — based on plain English instructions. Think of it as a skilled assistant who does the technical work while you describe what you want.

GITHUB A free online service for storing and sharing files. It has a feature called GitHub Pages that turns your stored files into a real public website, instantly and at no cost.

GIT A background system that tracks file changes and sends them from your computer to GitHub. You never interact with it directly — Antigravity handles this for you.

REPOSITORY (REPO) Your project folder on GitHub. All website files live here. Its name becomes part of your website address.

THE PROMPTS — COPY AND ADAPT THESE
PROMPT 1 — Create the website from your local files Use this as your very first message to Antigravity.

"This is my folder path: [paste your full folder path here] The GitHub address for this project is: [paste your GitHub repo URL here] In the folder there is a PNG image that should appear at the top of the page, along with the title '[your page title]'. Please create the repo and build the website."

Example: "This is my folder path: C:\Users\myname\PycharmProjects\CONFERENCENAME The GitHub address is: https://github.com/ILOVEICECREAM/CONFERENCENAME-Publishing-workshop
In the folder you can add a PNG that should form the design top of the web page, along with a title e.g. 'Peer Review Workshop'. Please create the repo."

What Antigravity will do:

Look inside your folder and read all the files
Build the website (index.html and style.css)
Set up Git, commit all files, and push them to GitHub
PROMPT 2 — Add names, faculty, or any text to the page Use this to add people's names, dates, or descriptions to the hero section.

"Please add the following names under the page title: Dr [Name]; Dr [Name]; Dr [Name]; Dr [Name]"

Example: "Please can you also add the names of faculty under the workshop title: Dr ABC; Dr GHJ etc

What Antigravity will do:

Edit the HTML to add the names as styled badges
Push the update to GitHub automatically
PROMPT 3 — Add new documents to the page Use this whenever you add new files to your local folder.

"I added two new sources. Please add them to the web page: '[full path to file 1]' '[full path to file 2]'"

Example: "I added two new sources please can you add them to the web page. 'C:\Users\myname\PycharmProjects\CONFERENCENAME\NAMEOFMANUSCRIPT.pdf' 'C:\Users\myname\PycharmProjects\CONFERENCENAME\Peer Review Workshop.pptx'"

What Antigravity will do:

Add a new download/view card for each file on the webpage
Commit and push the updated page and new files to GitHub


What Antigravity will do:

Explain the steps 

Update the local Git configuration so future pushes go to the new address

STEP-BY-STEP: WHAT HAPPENS BEHIND THE SCENES

Step 1 You describe your folder, GitHub address, and page title to Antigravity
Step 2 Antigravity explores your local folder and reads all the files
Step 3 Antigravity checks that the GitHub repository exists
Step 4 Antigravity writes index.html (page structure) and style.css (design)
Step 5 Antigravity runs "git init" to set up version tracking in your folder
Step 6 Antigravity runs "git add ." and "git commit" to package all files
Step 7 Antigravity connects to GitHub and runs "git push" to upload everything
Step 8 YOU log in to GitHub and enable Pages (Settings > Pages > main > Save) This is the only manual step — it requires your GitHub login
Step 9 Wait 1-2 minutes. Your site is live at your GitHub Pages URL (you may need to refresh browser or delete cache if you click too early)
Step 10 Add more content anytime using Prompt 2 or Prompt 3 above

THE ONE MANUAL STEP — ENABLING GITHUB PAGES
After the first push, you must enable Pages once. Antigravity cannot do this because it requires your GitHub account login.

Go to: https://github.com/[your-username]/[your-repo-name]/settings/pages
Under "Build and deployment", set Source to: Deploy from a branch
Set Branch to: main Folder: / (root)
Click Save
Wait ~2 minutes, then refresh — a green banner shows your site is live
Note: The "Rename" button when changing a repository name only appears AFTER you start typing a new name in the name field on the Settings page.

TIPS
Keep all your files in ONE folder before you start
Create the empty GitHub repository BEFORE sending Prompt 1
Stay signed in to GitHub when enabling Pages or renaming the repo
GitHub Pages takes 1-5 minutes to update after each push
To add more files later: drop them in your local folder, use Prompt 3
Your site stays live indefinitely at no cost
The site is automatically mobile-friendly

GLOSSARY

Commit A saved snapshot of your files with a description, like Track Changes
Push Sending your saved files from your computer up to GitHub Repository Your project folder on GitHub; its name = part of your URL Branch 
The version of your project (default is called "main") index.html
The main page file of any website style.css
The file controlling colours, fonts, and layout
GitHub Pages Free
GitHub feature that turns your files into a live website 
Prompt A plain-English instruction you type to Antigravity

REAL EXAMPLE — THE SOAP 2026 PEER REVIEW WORKSHOP https://github.com/ACCESSCD/SOAP-Publishing-workshop
Total time: Under 30 minutes Code written by user: None

=========================================================================================== END OF SKILL DOCUMENT
