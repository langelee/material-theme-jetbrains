# Material Theme UI for Jetbrains 

This is a [Material Theme](https://github.com/equinusocio/material-theme) port of both the IDE and Color scheme for JetBrains products.

**Please note:** This is a work in progress. There are some work to be done before this can be considered stable.

Special thanks to [@mallowigi](https://github.com/mallowigi) for doing a fantastic job keeping the plugin alive and extending it with some very nice features. Well done!

Buy me a beer: 
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=LSF7K29JBPMWU&lc=US&item_name=Material%20Theme%20JetBrains%20Development&item_number=m1&currency_code=NOK&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)

## Plugin
* [Support](#supported-ides)
* [Installation](#installation)
* [Contribution](#contribution)
* [Screenshots](#screenshots)
* [Author](#author)

## Supported IDEs

Thanks to the awesome guys at [JetBrains](https://www.jetbrains.com/) the plugin is now supported on pretty much all IDEs from the same company. There are still some work to do to get it perfect on all IDEs, but we're close.

* Any JetBrains IDE (I haven't tested all of them, but I'm pretty certain it should work on the majority)
* Android Studio is partly supported

## Installation
1. [Open the Settings/Preferences dialog](https://www.jetbrains.com/idea/help/accessing-settings.html#openIdeSettings) (OSX/Unix: <kbd>⌘,</kbd>, Windows: <kbd>Ctrl+Alt+S</kbd>)
2. In the left-hand pane, select **Plugins**.
3. Click **Browse repositories...** and search for `Material Theme UI`
4. Click **Install plugin** and confirm your intention to download and install the plugin.
5. Click **OK** in the **Settings** dialog and restart for the changes to take effect.
6. To switch the IDE theme (not the code color scheme), go to **Tools** -> **Material Theme** and choose 'Darker Theme', 'Default Theme' or 'Lighter Theme'.

### Set color scheme (code)
This plugin will not set the new color scheme for you, as that would cause a couple problems. You need to set the new color scheme manually:

1. Open the **Settings/Preferences** dialog again.
2. In the left-hand pane, select **Editor** -> **Colors & Fonts**.
3. In the **Scheme** dropdown, you'll find 3 new schemes: `Material Theme - Default`, `Material Theme - Darker` and `Material Theme - Lighter`. 
4. Choose the scheme you like and hit **Apply** and **OK**.

Shortcut: <kbd>Ctrl+\`</kbd> (that's a backtick) then hit `1. Color scheme` and select your desired color scheme. 

## Development

### Requirements

* JDK 1.8

### Building from the command line

`./gradlew clean build`

### Running a test instance with the plugin

`./gradlew runIde`

### Developing using IntelliJ

Import the project from the `build.gradle` file and develop as normal.  Make
sure you select JDK 8 in the import wizard.  The other defaults are fine.  You
can run the above mentioned CLI Gradle tasks directly in the "Gradle" Tool
Window, which expands from the right side of the screen.  To debug, find
"runIdea" in the list, right-click it, and choose Debug.

## Contribution

I would love to get some help on the colour schemes. Send me a pull request!

## Screenshots
#### Darker theme
![Darker theme](https://plugins.jetbrains.com/files/9377/screenshot_16889.png)

#### Default theme
![Default theme](https://plugins.jetbrains.com/files/9377/screenshot_16890.png)

#### Palenight theme
![Palenight theme](https://plugins.jetbrains.com/files/9377/screenshot_16892.png)

#### Lighter theme
![Lighter theme](https://plugins.jetbrains.com/files/9377/screenshot_16891.png)

#### Contrast Mode
![Choose theme](https://plugins.jetbrains.com/files/9377/screenshot_16888.png)

# Author
Twitter: [@crmag](https://twitter.com/crmag)

**Thanks to [@equinusocio](https://github.com/equinusocio/material-theme) for making the Color Scheme.**

Thanks to all [contributors](https://github.com/ChrisRM/material-theme-jetbrains/graphs/contributors) and a special thanks to the guys at [JetBrains](https://www.jetbrains.com/) for contributing and showing interest in the project!