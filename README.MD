# Poison Girl Theme for Oh My Posh

Welcome to the **Poison Girl** theme for Oh My Posh! This theme is designed to provide a stylish and distinctive prompt for your terminal.

## Features

- Customizable prompt colors and icons.
- Distinctive styling for Git repositories.
- Compatible with various terminal emulators.

## Installation

### Option 1: Download the JSON File

1. **Download the Theme File**:
   - Click [here](URL_TO_JSON_FILE) to download the `poison-girl.json` theme file.

2. **Move the File to Your Oh My Posh Configuration Directory**:
   - Place the downloaded `poison-girl.json` file in your Oh My Posh configuration directory. The location of this directory may vary based on your terminal setup.

3. **Update Your Oh My Posh Configuration**:
   - Open your Oh My Posh configuration file (e.g., `oh-my-posh.json` or similar).
   - Set the theme path to the downloaded file:
     ```json
     {
       "theme": "path/to/poison-girl.json"
     }
     ```

4. **Apply the Changes**:
   - Restart your terminal or reload your Oh My Posh configuration to apply the new theme.

### Option 2: Directly Set the Theme via URL in `$PROFILE`

1. **Open Your Profile Configuration File**:
   - Edit your PowerShell profile configuration file. You can find or create this file at `$PROFILE`.

2. **Add the Theme Configuration**:
   - Add the following lines to your `$PROFILE` to set the theme directly via URL:
     ```powershell
     $themeUrl = "URL_TO_JSON_FILE"
     Set-PoshPrompt -Theme (Invoke-RestMethod -Uri $themeUrl)
     ```

3. **Save and Apply the Changes**:
   - Save your `$PROFILE` file and restart your terminal or run `& $PROFILE` to apply the new theme.

## Customization

Feel free to modify the `poison-girl.json` file to suit your preferences. You can adjust colors, icons, and other settings to create a personalized terminal prompt.

## Support

For any issues or questions, please open an issue on the [GitHub repository](GITHUB_REPO_URL) or contact the maintainer.

## License

This theme is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

Enjoy your new terminal theme with **Poison Girl**!
