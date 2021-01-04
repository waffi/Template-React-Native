# Template-React-Native

### Steps:
Install npx
> npm install -g npx

Init react-native
> npx react-native init MyTestApp
> npx react-native init <projectName> --template react-native@^0.63.2

### Run Instruction ( https://microsoft.github.io/react-native-windows/ )

Get Started with Windows

    Navigate into this newly created directory
	> cd projectName

	Install the Windows extension
	> npx react-native-windows-init --overwrite
	
	Install system requirement
	https://microsoft.github.io/react-native-windows/docs/rnw-dependencies
	> Set-ExecutionPolicy Unrestricted -Scope Process -Force; iex (New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/microsoft/react-native-windows/master/vnext/Scripts/rnw-dependencies.ps1')
	
	Running a React Native Windows App	
	- Open solution ( AwesomeProject/windows/AwesomeProject.sln )	
	- Run yarn start from your project directory
	- Click the Run button 