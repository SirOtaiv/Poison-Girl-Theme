# Poison Girl Theme for Oh My Posh

Welcome to the **Poison Girl** theme for Oh My Posh! This theme is designed to provide a stylish and distinctive prompt for your terminal.

## Features

- Customizable prompt colors and icons.
- Distinctive styling for Git repositories.
- Compatible with various terminal emulators.

## Installation

### Download the JSON File

1. **Download the Theme File**:
   - Click [here](https://raw.githubusercontent.com/SirOtaiv/poison-girl-theme/main/themes/poison-girl.omp.json) to download the `poison-girl.omp.json` theme file.

2. **Move the File to Your Oh My Posh Configuration Directory**:
   - Place the downloaded `poison-girl.omp.json` file in your theme directory of Oh My Posh configuration directory. The location of this directory may vary based on your terminal setup.

3. **Update Your Oh My Posh Configuration**:
   - Open your Oh My Posh theme directory (e.g., `.../oh-my-posh/theme/` or similar).
   - Paste the file `poison-girl.omp.json` on that directory.
   - Set the theme path to the downloaded file:
     ```powershell
       --config "$env:POSH_THEMES_PATH/poison-girl.omp.json"
     ```

4. **Apply the Changes**:
   - Restart your terminal or reload your Oh My Posh configuration to apply the new theme.

### Directly Set the Theme via URL in `$PROFILE`

1. **Open Your Profile Configuration File**:
   - Edit your PowerShell profile configuration file. You can find or create this setting the command:
     ```powershell
     notepad $PROFILE
     ```

2. **Add the Theme Configuration**:
   - Add the following lines to your `$PROFILE` to set the theme directly via URL:
     ```powershell
     --config "https://raw.githubusercontent.com/SirOtaiv/poison-girl-theme/main/themes/poison-girl.omp.json"
     ```

3. **Save and Apply the Changes**:
   - Save your `$PROFILE` file and restart your terminal or run 
     ``` powershell
     . $PROFILE
     ``` 
   to apply the new theme.

## Customization

Feel free to modify the `poison-girl.omp.json` file to suit your preferences. You can adjust colors, icons, and other settings to create a personalized terminal prompt.

## Support

For any issues or questions, please open an issue on the [GitHub repository](https://github.com/SirOtaiv/poison-girl-theme) or contact the maintainer.

Enjoy your new terminal theme with **Poison Girl**!

