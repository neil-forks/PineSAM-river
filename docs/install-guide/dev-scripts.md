#  Install Dev version from scripts

Use this dev version if there is an issue with the premade binaries or you want to do development.
 
## Dependencies

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [python 3](https://www.python.org/downloads/) (tested with 3.10/3.11)
- [pipenv](https://pipenv.pypa.io/en/latest/installation/)
- [node+npm](https://nodejs.org/en/download/)


## Mac or Linux install

#### Setup
First, install all packages linked above in Dependencies.

Then, get the files.
```shell
git clone https://github.com/builder555/PineSAM
cd PineSAM
chmod +x setup-dev.sh
chmod +x run-dev.sh
./setup-dev.sh
```

#### Run
```shell
./run-dev.sh
# press CTRL+C in the terminal window to stop
```
* On a Mac http://localhost:8080 will open in your browser automatically.
* Some Linux distros may need http://localhost:8080 opened manually. Debian12 hints [here](https://github.com/builder555/PineSAM/discussions/47#discussion-4884758).
<br>
  
## Windows dev install

#### Setup
First, install all packages linked above in Dependencies. Skip to 4 if you did this already.

1. Python install notes
    * Check "Add python.exe to PATH" and select "Customize Installation"
    * Check "Add Python to environment variables" option
    * Screenshots of options to select [are here](https://github.com/builder555/PineSAM/discussions/7#discussion-4862766).
2. Install [NodeJS here](https://nodejs.org/en/download/), accept all prompts to add packages during install including a prompt in the terminal that opens.
3. After installing packages listed for backend script ([reference](https://github.com/builder555/PineSAM/issues/131#issuecomment-1489711241)), go to System Environment variables to check paths ([image](https://github.com/builder555/PineSAM/discussions/130#discussion-5011624)).
4. Download the Source-all-__.zip from the [latest release](https://github.com/builder555/PineSAM/releases/latest).
5. If the zip has an Unblock option, then unblock and extract ([example](https://github.com/builder555/PineSAM/discussions/106#discussion-4960445)).
6. Run powershell as administrator, set permissions to RemoteSigned ([image here](https://github.com/builder555/PineSAM/discussions/106)).
```shell
# setting this one time in powershell normally persists on reboots.
C:\Set-ExecutionPolicy RemoteSigned
```
#### Run
1. change directory, `cd` into the PineSAM folder that was extracted above.
```shell
.\setup-dev.bat   # only need to run this one time for each new version
.\run-dev.bat     # run this command every time to start PineSAM (do not need to run as admin)
```
