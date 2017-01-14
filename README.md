# &micro;C++ Syntax Highlighting for Sublime Text 2
Inspired by [&micro;C++ Syntax Highlighting for Vim](https://github.com/flxf/uCpp.vim).

Syntax definitions for &micro;C++ source code. Automatically highlights `.ucpp` and `.uh` files. (You can also tell Sublime to highlight `.cc` and `.h` files.)

# Contents
  * [Installation](#installation)
      * [Method 1: Clone this Repository](#method-1-clone-this-repository)
          * [(Optional) Rebuilding the `.tmLanguage` File](#optional-rebuilding-the-tmlanguage-file)
      * [Method 2: Download the Grammar File](#method-2-download)
      * [(Optional) Set Up Highlighting for `.cc` and `.h` Files](#optional-set-up-highlighting-for-cc-and-h-files)
  * [Usage](#usage)

# Installation
Note: this builds off of Sublime's default C++ highlighting, so make sure you haven't destroyed that somehow...

## Method 1: Clone this Repository
1. Open Sublime and navigate to `Preferences > Browse Packages...`. Your Sublime Packages folder should open
2. Clone this repo, placing it inside the `Packages` folder. 
   ```
   git clone https://github.com/poduncan/ucpp-subl2-syntax.git
   ```

Opening any `.ucpp` or `.uh` file will automatically highlight &micro;C++ source code. If you want Sublime to highlight &micro;C++ source code in `.cc` and `.h` files as well, refer to the [(Optional) Set Up Highlighting for `.cc` and `.h` Files](#optional-set-up-highlighting-for-cc-and-h-files) section.

### (Optional) Rebuilding the `.tmLanguage` File
You only need to do this if you want to contribute to this project, or to make it easier to make changes to the existing grammar (editing YAML is easier than XML).

1. Install [PackageDev](https://github.com/SublimeText/PackageDev)
2. Open `ucpp.YAML-tmLanguage` in Sublime
3. Press `F7` to build. The `.tmLanguage` file will be created/overwritten. Sublime refer to this file when highlighting &micro;C++ source code in `.ucpp` and `.uh` files. (Ensure that `Tools > Build System` is set to `Automatic`)
4. Edit and Rebuild as desired

## Method 2: Download
1. Download and unzip the [latest release](https://github.com/poduncan/ucpp-subl2-syntax/releases/download/v0.3.0/uCpp.zip)
2. Open Sublime and navigate to `Preferences > Browse Packages...`. Your Sublime Packages folder should open
4. Move the unzipped `uCpp` folder into the `Packages` folder

## (Optional) Set Up Highlighting for `.cc` and `.h` Files

1. Open any `.cc` file in Sublime
2. Navigate to `View > Syntax > Open all with current extension as... > uC++`
3. Repeat steps 1 and 2 for `.h` files

Now it works with `.cc` and `.h` files too! You can always change it back by resetting the default for each extension to `C++`.

# Usage

Open &micro;C++ source code in Sublime, and bask in the overwhelming warmth of its beauty.

