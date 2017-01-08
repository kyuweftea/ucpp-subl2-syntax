# &micro;C++ Syntax Highlighting for Sublime Text 2
Based off of [&micro;C++ Syntax Highlighting for Vim](https://github.com/flxf/uCpp.vim).

Syntax definitions for &micro;C++ source code. Automatically highlights `.ucpp` and `.uh` files. (You can also tell Sublime to highlight `.cc` and `.h` files.)

## Installation
Note: this builds off of Sublime's default C++ highlighting, so make sure you haven't destroyed that somehow...

### Method 1: For Users
1. Download and unzip the [latest release](https://github.com/poduncan/ucpp-subl2-syntax/releases/download/v0.1.0/ucpp.tmLanguage.zip)
2. Open Sublime and navigate to `Preferences > Browse Packages...`. Your Sublime Packages folder should open
3. Create a new folder called `uC++` inside the `Packages` folder
4. Move the unzipped `ucpp.tmLanguage` file into the new `Packages/uC++` folder

Now, opening any `.ucpp` or `.uh` file will automatically highlight &micro;C++ source code.

#### (Optional) Set up highlighting for `.cc` and `.h` files

1. Open any `.cc` file in Sublime
2. Navigate to `View > Syntax > Open all with current extension as... > uC++`
3. Repeat steps 1 and 2 for `.h` files

Now it works with `.cc` and `.h` files too! You can always change it back by resetting the default for each extension to `C++`.

### Method 2: For Developers
1. Open Sublime and navigate to `Preferences > Browse Packages...`. Your Sublime Packages folder should open
2. Clone this repo inside the `Packages` folder. i.e. 
   ```
   git clone https://github.com/poduncan/ucpp-subl2-syntax.git
   ```

#### How to Build
1. Install [PackageDev](https://github.com/SublimeText/PackageDev)
2. Open `ucpp.YAML-tmLanguage` in Sublime
3. Press `F7` to build. The `.tmLanguage` file will be created/overwritten in the same folder as the `.YAML-tmLanguage` file, which allows Sublime to highlight &micro;C++ source code for `.ucpp` and `.uh` files. (Ensure that `Tools > Build System` is set to `Automatic`)
