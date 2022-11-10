# Windows-Sandbox-with-VSCODE
Script to launch Windows Sandbox with latest VS Code installed

Windows Sandbox needs PRO version of the OS.   
Also need to be enabled from `Turn Windows features on or off`, for this to work.

```shell
# Switch to root of c:
cd c:\

# Git clone with the folder name as sandbox
git clone https://github.com/sukesh-ak/Windows-Sandbox-with-VSCODE.git sandbox

# Run Windows Sandbox with this config
c:\sandbox\vscode.wsb
```

Once Windows Sandbox is launched, it will download and install the latest version of Visual Studio Code.  
Also the `C:\sandbox\Projects` folder will be available inside Windows Sandbox under `Documents/Projects`
