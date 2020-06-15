# myfirstapp

Run following commands using Command Prompt as Administrator in Windows 10 64-bit

Install Chocolatey
--------------------
Install Command: @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"

Verification Command: choco --version

Install Node and NPM
--------------------
Install Command: choco install -y nodejs.install

Verification Command: node --version

Verification Command: npm --version

Install Python
--------------------
Install Command: choco install -y python2

Verification Command: python

Install JDK
--------------------
Install Command: choco install -y jdk8

Verification Command: java -version 

Verification Command: javac -version

Install Reach-Native
--------------------
Install Command: npm install -g react-native-cli

Verification Command: react-native -version

Install Expo (For IOS & Android Development)
--------------------
Install Command: npm install -g expo-cli

Verification Command: expo --version

Create Application
--------------------
Command: expo init myfirstapp or Pull code from GitHub

Start App Command: npm start
