**Personal Website/ Portfolio**

This is a simple website as I use as a resume and portfolio. It's hosted on GitHub pages. \
There are several links which visitors of the website can click on:\
	&nbsp;&nbsp;*my CV - this is a link to Google Drive where my updated CV is saved\
	&nbsp;&nbsp;*project links:\
	&nbsp;&nbsp;*FinLearn links - a link to our group pitch presentation in Googled Drive, and a link to the Figma prototype\
	&nbsp;&nbsp;*ChoreDoor - the code is saved in a repo in my GitHub that is deployed through GitHub pages\
	&nbsp;&nbsp;*Music Con - - the code is saved in a repo in my GitHub that is deployed through GitHub pages\
	
**Resources and references:**\
	&nbsp;&nbsp;*HTML templates with a variety of themes to choose from - https://html5up.net/ \
	&nbsp;&nbsp;*Portfolio Tutorial - https://www.youtube.com/watch?v=u-RLu_8kwA0&t=137s \
	&nbsp;&nbsp;*Deploying to GitHub Pages - https://www.codecademy.com/articles/f1-u3-github-pages \
	&nbsp;&nbsp;*More portfolio resources - https://discuss.codecademy.com/t/guide-how-to-build-a-web-dev-portfolio/394816?utm_source=youtube&utm_medium=organic-social&utm_campaign=codecademy_101_series&utm_content=yt_remembering_what_you_learn \
	
**GitHub Actions**
Every time I updated my CV, I would also need to update the link to my CV in the website. I sometimes forget and lose track if I've updated the websit already. To help me keep track, I made a workflow that makes a record on a Google Sheets file every time I push to my repo.\

Here are the steps to set up the workflow:\
&nbsp;&nbsp;1. Create a free account in https://ifttt.com/explore. This allows you to have three free applets.\
&nbsp;&nbsp;2. Click the "create" button.\
&nbsp;&nbsp;3. Click "If this". Then type "webhooks" in the search box and click on the webhooks icon.\
&nbsp;&nbsp;4. Click "Receive a web request".\
&nbsp;&nbsp;5. Give an event name in the box (ex. button_pressed). Click "create trigger" button.\
&nbsp;&nbsp;6. Click "Then that". Click on the desired action. In this case "Google Sheets". You will be prompted to link your Google Drive account to IFTTT.\
&nbsp;&nbsp;7. Choose "Add row to spreadsheet". You may choose to make certain edits to the rows or leave the default as is. Click "Create Action".\
&nbsp;&nbsp;8. In your IFTTT dashboard, click the round profile avatar in the upper right. Then click "My Services". Choose "Webhooks". Click "Documentation".\
&nbsp;&nbsp;9. Replace {event} in the first box with the event name that you gave in Step 5. Then copy the curl command.\
&nbsp;&nbsp;10. Create a basic workflow .yml file. Go to actions then click "set up a workflow yourself". \
&nbsp;&nbsp;11. Update the bottom of your yml file by pasting the curl command. Commit changes. \






