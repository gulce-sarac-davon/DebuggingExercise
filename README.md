# DebuggingExercise

I have first search a appropriate debugging tool for cordova .
The extension that I'll be using https://marketplace.visualstudio.com/items?itemName=Msjsdiag.cordova-tools .
After I have configured the environment .(Note :I had to change the java_home path in local .profile file).

I have learned the basic debugging with this tutorial .
https://www.youtube.com/watch?v=7qZBwhSlfOo

Basics about:
-Step over: moves on to next statement . DOES NOT go into call procesures
-Step into:if the statement includes a call procudure . Goes into the call procedure . Changing call stack adding current call
-Step out:Pops the call stack .Return execution to outer scope .

Debugging also helps with having in depth variable value knowledge . For example I wanted to see what ımageUri was by watching variable I learned that current assigned value was "file:///data/user/0/com.pvpoyer.cameraplugintesting/cache/1641983334759.jpg"

Some screenshots below to see debugging environment of cordova within vscode.

![Screenshot from 2022-01-12 13-22-30](https://user-images.githubusercontent.com/96186474/149125718-2960688b-3f99-46db-805a-e417a46240ad.png)

![Screenshot from 2022-01-12 13-23-09](https://user-images.githubusercontent.com/96186474/149125722-00f0daba-660f-42b0-96e4-9e36a61adde4.png)

![Screenshot from 2022-01-12 13-30-11](https://user-images.githubusercontent.com/96186474/149125726-21ef393d-850c-47aa-8e3f-d645293c1cc7.png)
