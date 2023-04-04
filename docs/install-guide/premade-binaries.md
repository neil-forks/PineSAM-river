# Easy Install

* Easiest way to install PineSAM is using a premade binary package.
* This does not require installation of python, node.js, or other dependencies.
* Just download the latest [release](https://github.com/builder555/PineSAM/releases/latest) for a specific OS and follow the steps below.

## Mac or Linux

   * Extract the downloaded zip file for Mac or Linux from [here](https://github.com/builder555/PineSAM/releases/latest).
   ```sh
   # Run in a terminal
   ./start.sh
   ```
   * On MacOS, http://localhost:8080/ opens in your browser automatically.
   * Some Linux distros may need http://localhost:8080/ opened manually.
   * User guide [here](https://github.com/builder555/PineSAM/wiki).


## Windows
   * right click on the zip, properties> general, check the Unblock box if it is present, then extract ([reference](https://github.com/builder555/PineSAM/discussions/106#discussion-4960445)).
   * Run [powershell](https://learn.microsoft.com/en-us/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.3) as admin, cd to the pinesam folder and `.\start.ps1`
   * Allow and accept any pop-up warnings about "serve.exe" and "main_sever.exe".
   * If you get errors in powershell, set the permissions to RemoteSigned to allow scripts.
     * ```C:\> Set-ExecutionPolicy RemoteSigned  #([reference](https://lazyadmin.nl/powershell/running-scripts-is-disabled-on-this-system/)).```
   * Browser will automatically open http://localhost:8080
   * User guide [here](https://github.com/builder555/PineSAM/wiki).
