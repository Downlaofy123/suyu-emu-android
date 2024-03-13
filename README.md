Building For Android
Note: These build instructions are a work-in-progress.

Dependencies
Android Studio
NDK 25.2.9519653 and CMake 3.22.1
Git

WINDOWS ONLY - Additional Dependencies
Visual Studio 2022 Community - Make sure to select "Desktop development with C++" support in the installer. Make sure to update to the latest version if already installed.
Vulkan SDK - Make sure to select Latest SDK.

Cloning suyu with Git
git clone --recursive https://gitlab.com/suyu-emu/suyu
suyu by default will be cloned into -

C:\Users\<user-name>\suyu on Windows
~/suyu on Linux

And wherever on macOS

Building
Start Android Studio, on the startup dialog select Open.
Navigate to the suyu/src/android directory and click on OK.
In Build > Select Build Variant, select release or relWithDebInfo as the "Active build variant".
Build the project with Build > Make Project or run it on an Android device with Run > Run 'app'.

Additional Resources

https://developer.android.com/studio/intro
