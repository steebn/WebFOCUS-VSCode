# Change Log
All notable changes to the "webfocus" extension.
### 0.6.0 - 0.6.2

- Updated snippets
    - Better readability and descriptions in the snippet window.
    - [Query Command](https://webfocusinfocenter.informationbuilders.com/wfappent/TLs/TL_lang/source/testing66.htm) Snippets
        - Additional query commands
        - Type `wf?` in the editor to access all available snippets
    - `SET` and `ON TABLE SET` Snippets
        - Added more snippets
        - Combined them into the same snippet with a selection to choose which one to use.
        - Type `SET` to access all available snippets
    - Functions
        - Fixed readability in snippet popup
        - Removed dummy functions

### 0.5.1 - 0.5.4

- Security patches.

### 0.4.7

- 'event-stream' security vulnerability patch. More info here: [https://code.visualstudio.com/blogs/2018/11/26/event-stream](https://code.visualstudio.com/blogs/2018/11/26/event-stream)

### 0.4.6

- Fix for the FTOA and PTOA function snippets. They were missing 2 of the required parameters

### 0.4.5

- Added in configuration defaults to remove the ampersand special character from:
    - editor.wordSeparator
        - This will highlight the entire variable, including the '&' when double clicking on it
    - editor.wordWrapBreakAfterCharacters
        - This not leave the amper on online while the varaiable name is on the next line up when word wrap is on.

### 0.4.4

- Added in keybindings for quick transform to upper/lower case
    - ctrl+alt+u = UPPERCASE
    - ctrl+alt+l = lowercase

### 0.4.2 - 0.4.3

- Comment Bug fixes

### 0.4.1

- Dependencies update

### 0.4.0
- Added HTML syntax highlighting for -HTMLFORM blocks

- Added in an ON TABLE SET STYLE * code block and started adding in styling snippets

- Added in -QUIT snippet/highlighting

- Added in some missing syntax highlighting.

- Fixed DECODE snippet

### 0.3.1

- Correction to the README.md file for the WHENCE prefix. Now has the correct prefix of 'locate' 

- Icon update

- Removed duplicate entry in the changelog for v0.2.3

### 0.3.0

- Removed the WebFOCUS icon pending permission to use. Replaced with a creative commons licensed BI Logo 

- Added disclaimer to the README.md 

- Changed the prefix for the WHENCE snippet to 'locate' as to not to bring up the snippet everytime that you are typing a WHERE filter

### 0.2.3

Updated the Icon

### 0.2.2

Flagging as 'Preview'

### 0.2.1

Bug fixes

### 0.2.0

Published to the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=steebn.webfocus)

### 0.0.2

Bug fixes

### 0.0.1

Initial release (preview). 

This has not yet been published in the VS Code Extensions Market Place. If you would like to preview this extension, you need to download this repository, unzip it and place the whole unzipped folder in your VS Code extensions folder .vscode/extensions. 

Depending on your platform, it is located in the following folders:

- **Windows:** %USERPROFILE%\\.vscode\extensions
- **macOS:** ~/.vscode/extensions
- **Linux:** ~/.vscode/extensions

## [Unreleased]
