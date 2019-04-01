Each folder contains a unique README.md file with specific details regarding the Experience Target (the URL that is entered into the Monitor to... section when configuring a Web App Group - see image below) as well as any specific variables that will need to be defined for the script to work. Please note, variables are already included in the provided scripts so it is imperative that the variables be defined exactly as written to be valid when used by the script.

![Image of Web App Group Creation](https://github.com/appneta/experience-scripts/blob/master/Images/Web%20App%20Group%20Target%20Example.png)

![Image of Transposing the Target URL](https://github.com/appneta/experience-scripts/blob/master/Images/Transposing%20Target%20URL.png)

The html files in each folder contain the script described by the title pre-formatted to be copy and pasted straight into the AppNeta Performance Manager Workflow creation screen. 

**HOW TO USE THE SCRIPTS PROVIDED**

To insert the scripts, simply select the entire body of the appropriate .html file here in GitHub and copy that data to your clipboard.

![Gif of Script Copy](https://github.com/appneta/experience-scripts/blob/master/Images/Copying%20the%20Script%20Large.gif)

Once that data is in your clipboard, navigate to the Web App Group page in APM and select Configure and then click on the Workflows... section (see image below) to enter the workflow editor.

![Image of Web App Group Workflow Example](https://github.com/appneta/experience-scripts/blob/master/Images/Web%20App%20Group%20Workflow%20Example.png)

Once in the editor screen, you'll be presented with a tabular view with just a single entry that says open:
![Image of Workflow Default Page](https://github.com/appneta/experience-scripts/blob/master/Images/Workflow%20Initial%20Screen.png)

On this page, you'll want to click on the Source tab in order to get to the xml view of the script. From the Source tab, select all of the items inside of the code box by either highlighting or clicking and performing a Select All command to highlight the full body of the code. You can then simply paste the copied script (from the earlier step indicated above) over the selected text. Once done, switching back to the Table tab will show multiple inputs as indicated in the below gif.

![Gif of Pasting the Script](https://github.com/appneta/experience-scripts/blob/master/Images/Pasting%20the%20workflow%20Large.gif)

The next steps in the process include renaming the workflow to be something meaningful (which is especially useful if you are going to be configuring multiple workflows for a single application) and then defining the variables as outlined in the README.md files for each of the script groups.

Renaming the script:
![Image of rename the script](https://github.com/appneta/experience-scripts/blob/master/Images/Rename%20the%20Workflow.png)


Defining variables:

![Gif of defining variables](https://github.com/appneta/experience-scripts/blob/master/Images/Defining%20Variables%20Large.gif)

*When defining variables, it is extremely critical that the name of the variable (i.e. username, password, etc) match the case of the variables listed in the script README.md files. The script will fail if the case and spelling do not match exactly.*

![Image of Transposing Variables](https://github.com/appneta/experience-scripts/blob/master/Images/Transposing%20Variables.png)




