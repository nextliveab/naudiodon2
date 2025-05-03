Building portaudio for naudiodon on Windows:

Download the ASIO SDK from Steinberg (https://www.steinberg.net/en/company/developer.html).
Create a folder named `asiosdk` inside `portaudio\build\msvc` and place the contents of the downloaded ASIO SDK into it.

Copy build.bat, portaudio.vcxproj and portaudio.def into portaudio\build\msvc directory.
Ensure the `asiosdk` folder is also present in this directory.
Run build.bat
Copy portaudio_x64.dll and portaudio_x64.lib from portaudio\build\msvc\X64\Release to naudiodon\portaudio\bin directory

