#phpstorm-theme-github-remixed

Get GitHub's syntax highlighting / color scheme and fonts within PHPStorm. In this theme I tried to be as close as
possible on the original GitHub PHP colours, but switched the red comments (seriously GitHub, RED? :)) to a decent grey.
The theme contains also basic colours for JS, HTML, CSS etc. and uses - exactly like GitHub - the `Consolas` font
which is installed by default on Windows systems and can be downloaded for free for Mac OS and Linux.
This is an experimental repo, not sure if this looks like it should look everywhere on every platform.

![Screenshot](screenshot.png)

### Installation on Windows (PHPStorm 7/8/9/10)

Close PHPStorm if open.
Go to `C:\Users\XXXXXX\.WebIde70\config\colors` and place the .icls file there.
Open PHPStorm, go to *View -> Quick Switch Theme -> Switch Color Scheme* and select *GitHub Remixed*.

### Installation on Mac OS (PHPStorm 7/8/9/10)

Same as above, but path is `~/Library/Preferences/WebIde70/colors/`.

### Installation on Linux (PHPStorm 7/8/9/10)

Same as above, but path is `~/Library/Preferences/WebIde70/colors`.

Please note that the folder name will be .WedIde70 if you use PHPStorm 7, .WebIde100 if you use PHPStorm 10 etc.! If you cannot see the new theme then please go to Settings > Editor > Colors & Fonts and try to save the current theme, which will make PHPStorm create a new file like `Default copy.icls` inside the theme folder. Don't know why, but somehow this triggers a rescan of the the theme folder, usually fixing any "theme not found" issues.
