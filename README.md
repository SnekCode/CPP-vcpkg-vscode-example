Example of a simple CLI application utilizing the vcpkg manager.


# Setup
### Install extensions for VSCODE:
* [C/C++ Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-extension-pack)

### Install VCPKG
* Follow [install steps](https://learn.microsoft.com/en-us/vcpkg/get_started/get-started?pivots=shell-cmd)
* Set the `VCPKG_ROOT`env variable.  
  * It is referenced in `CMakeUserPresets.json` and `CMakePresets.json`

# Running
* Command Palette `CMake: Build` to build.
* Command Palette `CMake: Run Without Debugging` to build and then run the target.
* Command Palette `CMake: Debug` to build and then run the target in debug.

Alternatively the CMake Extension offers quick action buttons at the bottom of VSCode in the status bar.