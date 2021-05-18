Flutter Notes

In case flutter SDK not works:

Open Library in Enclosing finder.
Delete existing flutter folder, Extract latest SDK Zip file and place the flutter folder in user/name/path
Once extracted, open terminal and run following commands:
export PATH="$PATH:`pwd`/flutter/bin" (Temporary path)
 flutter (To check flutter working or not)

For create permanent path, use following commands:
1. Create new zhrc file using this command:
	touch .zshrc

2. Open the file with text edit and paste following:
	export PATH="$PATH:[PATH_OF_FLUTTER_GIT_DIRECTORY]/bin"
	(Replace braces path string with your sdk path.)

3. Save the file and exit.
4. Close and reopen terminal and run command: flutter

In case of show and accept Android license, use this command:
flutter doctor --android-licenses

Demo to setup update path:
https://www.youtube.com/watch?v=9GuzMsZQUYs&ab_channel=FlutterExplained
