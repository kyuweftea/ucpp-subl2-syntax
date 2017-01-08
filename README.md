# &micro;C++ Syntax Highlighting for Sublime Text 2
Based off of [&micro;C++ Syntax Highlighting for Vim](https://github.com/flxf/uCpp.vim).

Syntax definitions for &micro;C++ source code. Automatically highlights `.ucpp` and `.uh` files. (You can also tell Sublime to highlight `.cc` and `.h` files.)

## General Installation
Note: this builds off of Sublime's default C++ highlighting, so make sure you haven't destroyed that somehow...

1. Download and unzip the [latest release](https://github.com/poduncan/ucpp-subl2-syntax/releases/download/v0.1.0/ucpp.tmLanguage.zip)
2. Open Sublime Text 2 and navigate to `Preferences > Browse Packages...`
3. Create a new folder called `uC++` inside the `Packages` folder
4. Move or Copy the unzipped `ucpp.tmLanguage` file into the new `Packages/uC++` folder

Now, opening any `.ucpp` or `.uh` file will automatically highlight &micro;C++ source code.

### (Optional) Set up highlighting for `.cc` and `.h` files

1. Open any `.cc` file in Sublime
2. Navigate to `View > Syntax > Open all with current extension as... > uC++`
3. Repeat steps 1 and 2 for `.h` files

Now it works with `.cc` and `.h` files too! You can always change it back by resetting the default for each extension to `C++`.

## Installation for Development
1. Install [PackageDev](https://github.com/SublimeText/PackageDev)
2. Clone this repository, i.e.
   ```
   git clone https://github.com/poduncan/ucpp-subl2-syntax.git
   ```
3. Open Sublime Text 2 and navigate to `Preferences > Browse Packages...`
4. Copy `ucpp.YAML-tmLanguage` from the repository into the `Packages/User` folder
5. Open the `Packages/User/ucpp.YAML-tmLanguage` file in Sublime
6. Press `F7` to build. A `.tmLanguage` file will be created in the same folder, which allows Sublime to highlight &micro;C++ source code for `.ucpp` and `.uh` files. (Ensure that `Tools > Build System` is set to `Automatic`)
7. Edit `ucpp.YAML-tmLanguage` and Rebuild as desired :)
