# MacOS-Finder-Tool-bar-App---open-in-visual-studio-code
open script "open-in-visual-studio-code.scpt"

```
tell application "Finder"
	set theWin to window 1
	set thePath to (POSIX path of (target of theWin as alias)) as text
end tell

tell application "Terminal"
	set f to "code " & thePath
	do script f
	do script "exit"
	delay 2
	quit
end tell	
```

and then File -> Export

![image](https://user-images.githubusercontent.com/51815522/162179216-2bc8d27c-7e4b-49cf-a2a5-79fce256ea76.png)

name the app

Where set as "Application" Folder

File Format Chose "Application"

Click "Save"

![image](https://user-images.githubusercontent.com/51815522/162168007-95f0efef-3fb1-4dd1-a1f6-b9aa058a492f.png)

Press "Option" key then drag App to Finder Tool bar

![image](https://user-images.githubusercontent.com/51815522/162170312-4b73db23-4b23-4ddc-8d37-b35e3ff71387.png)

Finished! "Press App" to open vscode in current folder
