# Betterbird UserChrome

This repository contains a custom UserChrome script for [Betterbird](https://betterbird.eu/), a fork of Mozilla Thunderbird.

- Combines the tab bar and toolbar into a single line for a cleaner look.
- Removes shadows and border-radius effects for a flat, minimalistic UI.
- Default theme background is `/chrome/image/ff-1.png`, which can be replaced with your own.
- You can modify CSS properties in the `/chrome/css/config.css` file.

![betterbird-userchrome-00](https://github.com/user-attachments/assets/818cb49e-3824-453b-b862-b53349e9d189)

![betterbird-userchrome-01](https://github.com/user-attachments/assets/380b951c-d886-4986-a1ec-499fa4a2b8ef)

![betterbird-userchrome-02](https://github.com/user-attachments/assets/3a9e4a67-b185-481d-9eea-462f457ba09a)

## Installation

1. Copy the `chrome` folder from this repository into your Betterbird profile directory.
2. Enable UserChrome.css in Betterbird by following the usual steps for enabling custom themes in Thunderbird.
3. Restart Betterbird to ensure that the changes take effect.

### Steps to Enable UserChrome in Betterbird

1. **Open Betterbird**: Launch your Betterbird application.

2. **Access Configuration Editor**:
   - Click on the **menu button** (three horizontal lines) in the upper-right corner of the Betterbird window.
   - Select **"Settings"** from the dropdown menu.

3. **Open the `about:config` Page**:
   - In the Settings window, enter `about:config` in the search box.
   - Click on the **"Config Editor"** button that appears.

4. **Proceed with Warning**:
   - You might see a warning message saying "This might void your warranty!" Click **"Accept the Risk and Continue"** to proceed.

5. **Search for the Setting**:
   - In the `about:config` page, use the search box to find `toolkit.legacyUserProfileCustomizations.stylesheets`.

6. **Modify the Setting**:
   - Double-click on the `toolkit.legacyUserProfileCustomizations.stylesheets` preference to change its value from `false` to `true`.

7. **Close and Restart**:
   - Close the `about:config` tab and restart Betterbird to apply the changes.

## Note

This UserChrome script is only compatible with Betterbird 115 and is not yet complete; many elements are still unmodified. Contributions and feedback are welcome to help improve this theme.
