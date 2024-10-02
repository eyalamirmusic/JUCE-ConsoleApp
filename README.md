# JUCE Console App Example
A very basic example to create a JUCE console app.

The app is also set up to run the message thread, spawn timers, etc.

To configure, you can use CMake to generate a project.

So for example, from the root of the repo
```
CMake -G Ninja -B build
cmake --build build
./build/App/ConsoleAppMessageThread_artefacts/ConsoleAppMessageThread
```

For Xcode, replace the first command with:
```
CMake -G Ninja -B build
```

Or for Visual Studio:
```
CMake -G "Visual Studio 17 2022" -B build
```