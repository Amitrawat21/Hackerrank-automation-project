# automation-project
This application performs automation on hackerrank website ,which uses user credentials i.e username and password(existing account) . Then the program rendered itself on each page until it foundc the all contests list and then it added a moderator in each contest on each page
# Why Automation 
Automation reduces time, effort and cost, whilst reducing manual errors, giving your business more time to focus on your primary objectives. Repetitive tasks can be completed faster. Automating processes ensures high quality results as each task is performed identically, without human error. 
# Purpose 
The purpose of this project is to:-

-> To manage the exciting contest on the user account.

-> To add the moderator to each contest.

-> Each page consists of 10 contests , so I have to manage every contest on every page till the end.

-> Moderator should be an exciting user and the program has to type it's username then add it to the contest.

-> Improve process control and significantly reduce lead times compared to outsourcing or going overseas. 
# Requirements  
 Download and install VS-code

Download and install node.js

Install Minimist :- To process input arguments.

npm i minimist

Install puppeteer :- To perform automation
npm install puppeteer 
# language used 
JavaScript was used as it offers efficiency with its well built and structured patterns and functions, making the script more compact.
Node.js as it allows you to run JavaScript on the server.It opens a file on the server and returns the content to the clien. 
# procedure 
Steps 	Description.
Require	Require - install libraries.
Read sourc -	Create JS-object-notation & read config.json file.
Parse JSON -	Create a JS-object and manipulate the data.
Function	 - create async function to run the program.
Browser    -	Use puppeteer to launch browser.
Tab-	Get and open one tab for process.
Url-	Fetch url from input and goto page url.
Login1-	wait and then click on login on page1.
Login2	-wait and then click on login on page2.
Type -userid	Read user id from configJSON & type in input-tag.
Type -password	Read password from configJSON & type in input-tag.
Click Login -	To login in user account.
Click COMPETE-	Open compete section.
Manage Contest-	Click on Manage Contest.
Pages length	-Perform below steps till pages length.
All contest-	Collect all contest url in array.
Url loop-	Use it to save moderator in each contest.
New Tab-	Open new tab for moderators.
Moderator-	Add moderator in each contest.
Close Tab-	Close new tab.
Last Page-	Program stops after automation completed.
 
 
 
