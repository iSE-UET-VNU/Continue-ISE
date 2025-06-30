# Prequisite
- Node version: 20.19.0
# Installation
1. `git clone https://github.com/iSE-UET-VNU/Continue-ISE.git`
2. `cd Continue-ISE/continue-ise`
3. Open the VS Code command pallet (cmd/ctrl+shift+p) and select `Tasks: Run Task` and then select `install-all-dependencies`
4. Start debugging:
    1. Switch to Run and Debug view
    2. Select Launch extension from drop down
    3. Hit play button
    4. This will start the extension in debug mode and open a new VS Code window with it installed
        1. The new VS Code window with the extension is referred to as the Host VS Code
        2. The window you started debugging from is referred to as the Main VS Code
5. To package the extension, run `npm run package` in the `continue-ise/extensions/vscode directory`. This will generate `continue-ise/extensions/vscode/build/continue-{VERSION}.vsix`, which you can install by right-clicking and selecting "Install Extension VSIX".