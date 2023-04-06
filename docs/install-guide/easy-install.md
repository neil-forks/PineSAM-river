
# Easy Install

Easiest way to install PineSAM is using a premade binary package. This does not require installation of python, node.js, or other dependencies. Just download the latest [release](https://github.com/builder555/PineSAM/releases/latest) for a specific OS and follow the steps below.

## Mac or Linux

   * Extract the downloaded zip file for Mac or Linux from [here](https://github.com/builder555/PineSAM/releases/latest).
   ```
    # run in a terminal
    ./start.sh
   ```

   * On MacOS, http://localhost:8080/ opens in your browser automatically.
   * Some Linux distros may need http://localhost:8080/ opened manually.
   * User guide [here](user-guide/usage).


## Windows
   * Right click on the zip, properties> general, check the Unblock box if it is present, then extract ([reference](https://github.com/builder555/PineSAM/discussions/106#discussion-4960445)).
   * Run [Powershell](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.3) as admin, cd to the pinesam folder and 
   
      `C:\>   .\start.ps1`

   * Allow and accept any pop-up warnings about "serve.exe" and "main_sever.exe".
   * For errors in powershell: use this command to set permissions to RemoteSigned to allow pwsh to execute scripts ([reference](https://lazyadmin.nl/powershell/running-scripts-is-disabled-on-this-system/)). 

   
      `C:\> Set-ExecutionPolicy RemoteSigned`
   
   * Browser will automatically open http://localhost:8080
   * User guide [here](user-guide/usage.md)