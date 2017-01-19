# &micro;C++ Syntax Highlighting for Sublime Text 2

Syntax definitions for &micro;C++ source code. Automatically highlights `.ucpp` and `.uh` files. (You can tell Sublime to highlight `.cc` and `.h` files as well.) Autocompletes some &micro;C++ language constructs.

# Contents
  * [Installation](#installation)
      * [Method 1: Clone this Repository](#method-1-clone-this-repository)
      * [Method 2: Download](#method-2-download)
      * [(Optional) Set Up Highlighting for `.cc` and `.h` Files](#optional-set-up-highlighting-for-cc-and-h-files)
  * [Usage](#usage)
  * [References](#references)

# Installation

## Method 1: Clone this Repository
1. Open Sublime and navigate to `Preferences > Browse Packages...`. Your Sublime Packages folder should open
2. Clone this repo, placing it inside the `Packages` folder. 
   ```
   git clone https://github.com/poduncan/ucpp-subl2-syntax.git
   ```

Opening any `.ucpp` or `.uh` file will automatically highlight &micro;C++ source code. If you want Sublime to highlight &micro;C++ source code in `.cc` and `.h` files as well, refer to the [(Optional) Set Up Highlighting for `.cc` and `.h` Files](#optional-set-up-highlighting-for-cc-and-h-files) section.

## Method 2: Download
1. Download and unzip the [latest release](https://github.com/poduncan/ucpp-subl2-syntax/releases/download/v0.5.2/uCpp.zip)
2. Open Sublime and navigate to `Preferences > Browse Packages...`. Your Sublime Packages folder should open
4. Move the unzipped `uCpp` folder into the `Packages` folder

## (Optional) Set Up Highlighting for `.cc` and `.h` Files

1. Open any `.cc` file in Sublime
2. Navigate to `View > Syntax > Open all with current extension as... > uC++`
3. Repeat steps 1 and 2 for `.h` files

Now it works with `.cc` and `.h` files too! You can always change it back by resetting the default for each extension to `C++`.

# Usage

Open &micro;C++ source code in Sublime, and bask in the overwhelming warmth of its beauty.

# References

- Inspired by [&micro;C++ Syntax Highlighting for Vim](https://github.com/flxf/uCpp.vim)
- C and C++ language files adapted from [their sublime package](https://github.com/cj/sublime)
- &micro;C++ language features taken from the [&micro;C++ Annotated Reference Manual](https://plg.uwaterloo.ca/~usystem/pub/uSystem/uC++.pdf), Version 7.0.0
