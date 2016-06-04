# coex-plugin-task-skypewin
A Forensic plug-in for Skype. Just run the application. The program resides in the source directory.

Requirements: Qt5

## Build plugin for coex:
	
	$ ./build_lib.sh

## Build single app:

	$ ./build_app.sh
	
### run single app:

	$ ./bin/coex-skype-win 

	Task is search logs of Skype for WINDOWS

	  Usage: ./bin/coex-skype-win [OPTIONS] 

	  OPTIONS:

		--input-folder <fullpath>       - required parameter
		--output-folder <fullpath>      - required parameter
		--help                          - this help
	  
	  Version: 0.1.0
	  Author: Igor Polyakov

	$ ./bin/coex-skype-win --input-folder ../coex-testdata/Windows7_Ult/ --output-folder ../output 

	===============TaskSkypeWin================


	Debug mode ON

	InputFolder:  "../coex-testdata/Windows7_Ult/" 


	 :: ../coex-testdata/Windows7_Ult//Users/UserVlad/AppData/Roaming/Skype/fox.user.3/main.dbConnected!
