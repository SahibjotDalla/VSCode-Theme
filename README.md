## Gruvbox VSCode Theme Setup

Enhance your VSCode experience with a customized theme! Follow these steps to apply your custom VSCode theme using the **_Dark Gruvbox With Italics_** theme and **_Custom CSS and JS Loader_** extension.


![Gruvbox VSCode](https://github.com/user-attachments/assets/fa2c8d97-58b2-4415-90a2-80c934bf4e4d)

![Windowed Grubbox VSCode](https://github.com/user-attachments/assets/fa37a372-f5f2-4da5-a086-02bdc94712ec)


### 🛠️ Prerequisites
1. **Dark Gruvbox With Italics** Theme:  
   Download and install **_Dark Gruvbox With Italics_** theme from the [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=sagaban.dark-gruvbox-with-italics).

2. **Custom CSS and JS Loader**:  
   Download and install **_Custom CSS and JS Loader_** from the [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css).

2. **Try's Icon Pack**:  
   Download and install **_Try's Icon Pack_** from the [VSCode Marketplace](https://marketplace.visualstudio.com/items?itemName=rafapaulin.try-material-icon-theme).

### 📂 Setup Instructions

1. **Move Files:**
   - **On Windows**:
     - Move your `settings.json` and `custom-vscode.css` files to `%APPDATA%\Code\User\`.
   - **On macOS**:
     - Move your `settings.json` and `custom-vscode.css` files to `$HOME/Library/Application Support/Code/User/`.

2. **Configure `settings.json`:**
   - Open `settings.json` in your VSCode configuration folder.
   - Scroll to the bottom of the file (around line 72).
   - Add the path to your `custom-vscode.css` file. Use the following format:
     - **Example For Windows**:  
       ```json
       "vscode_custom_css.imports": [
       "file:///C:/Users/YourUsername/AppData/Roaming/Code/User/custom-vscode.css"
       ],
       ```
     - **Example For macOS**:  
       ```json
       "vscode_custom_css.imports": [
       "file:///Users/YourUsername/Library/Application%20Support/Code/User/custom-vscode.css"
       ],
       ```

3. **Enable Custom CSS and JS:**
   - Open VSCode and press `Ctrl + Shift + P` to open the Command Palette.
   - Type `Enable Custom CSS and JS` and press `Enter`.
   - Restart VSCode to apply the changes.

4. **Reload Custom CSS and JS (if necessary):**
   - If you don’t see the changes immediately, press `Ctrl + Shift + P` again.
   - Type `Reload Custom CSS and JS` and press `Enter`.
   - Restart VSCode to apply the changes.
   - If the issue persists, double-check that the file path in `settings.json` is correct.

If you’re still having issues with the **_Custom CSS and JS Loader_**, check out the [official troubleshooting guide](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) for additional help.

And that's it! Your custom VSCode theme should now be active and looking great. Enjoy your personalized coding environment!
