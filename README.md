# TurqoiseHallucinogen Theme
    * Dark color theme turqoise buttons.
    * All Text buttons have grey text to provide less distractions.

## Languages
    * Microsoft Visual Studio dark theme c++ syntax highlighting.
    * Other languages are probably not going to get updated for the theme.

## Customizing Settings
    Getting the brackets and paranthesis to be the same color requires some customizations. (font & ligatures optional)

    * <Ctrl+Shift+P> -> User Settings JSON
        * "editor.fontFamily": "'Cascadia Code', 'Courier New', monospace",
        * "editor.fontLigatures": true,
        * "editor.bracketPairColorization.enabled": false

## Editing
    Go To the extensions folder for vscode.
        * Windows -> %USERPROFILE%\.vscode\extensions\
        * macOS   -> ~/.vscode/extensions/
        * Linux   -> ~/.vscode/extensions/

    Find the latest version of the extension.
        * xexaaron.th-<version>/Themes/TurqoiseHallucinogen-color-theme.json

    Edit the theme.
        * <Ctrl+Shift+P> -> Developer : Inspect Editor Tokens and Scopes.
            * Use this tool to inspect the token and scope you wish to change.
            * After editing use the -> Developer : Reload Window tool.

    It will probably overwrite if the extension is updated.
    Save changes in a new file just in case.
    


