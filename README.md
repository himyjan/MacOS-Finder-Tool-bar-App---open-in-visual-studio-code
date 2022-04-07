# MacOS-Finder-Tool-bar-App---open-in-visual-studio-code
open script "open-in-visual-studio-code"

```
tell application "Terminal"
	do script "code .;exit"
	delay 2
	quit
end tell
```

and then File -> Export

![image](https://user-images.githubusercontent.com/51815522/162167124-7a8a8dd2-268f-4d17-9cb0-a72ba1f3c337.png)

name the app

Where set as "Application" Folder

File Format Chose "Application"

Click "Save"

![image](https://user-images.githubusercontent.com/51815522/162168007-95f0efef-3fb1-4dd1-a1f6-b9aa058a492f.png)

Press "Option" key then drag App to Finder Tool bar

![image](https://user-images.githubusercontent.com/51815522/162170312-4b73db23-4b23-4ddc-8d37-b35e3ff71387.png)

Finished!
"Press App" to open vscode in current folder
