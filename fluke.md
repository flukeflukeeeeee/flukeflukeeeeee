# How to use simple regression test with Katalon recorder

 Hi! My name is Fluke, QA Engineer of the product development department at Anymind Group.<br>
In this article, 
I’m going to introduce to you what is a Katalon recorder in a software automation test just record and playback,make repeat and regression test to faster!!!

## What is a Katalon?
Katalon Recorder is a free, Selenium IDE alternative, lightweight web extension for automating actions and automated testing on the browser.<br>
it will record whatever activities you will do on your browser and it will once you stop the recording you can playback activities again. <br>
Currently,it’s available on Chrome, Firefox and Edge browsers.<br>

## Why i choose Katalon recorder for regression test?
Katalon recorder are easy to install,easy to learn,easy to use.<br>
You can change the test execution order depending on your requirement so it will allow you to generate edit and execute test cases quickly,<br>
just record and playback.


## How to use Katalon recorder?
1. First have to install extension on your web browser,it easy to install on chrome extension,just go to chrome store and **[search katalon recorder](https://chrome.google.com/webstore/search/katalon%20recorder)** after that click add to chrome.
2. Click puzzle icon on the right corner then click katalon recorder icon, the screen default will appear.
<img src="./images/s1.png" alt="graph" style="width: 200px"/>
3. Click record button on screen and then every interaction on web will recorded by katalon recorder or you can write script on command and click add for adding step
4. if need to finish recording,click on katalon recorder icon and click stop recorder like  to create new test case
5. Click play button to playback the test case, you can see all actions is perfectly recorded are in green,it mean steps are pass but if not perfectly action in red mean steps are fail.
6. You can see the execution log on log section


  
### Test sample :
I will sample record with my project Anytag
Define test step of Create Account of Instagram and Youtube Analytics
* Login and Click Analytic menu on Anytag<br>
#### Look at screen command will auto generate when we click record and interaction with website,we can modify command or delete step by step
* Click add account for create IG Analytics account
* Check UI of Analytic Account
* Click add account for create YT Analytics account

