# How to create a new win32 C++ project in Visual Studio 2017
Guide goes here 
1. Launch Visual Studio
2. Select File -> New -> Project
    1. On the left hand side click Visual C++ 
	2. Down to general then make an Empty Project
	3. Title project and select the bin folder
3. Right click project title and go down to properties
	1. Check the SDK version. Make sure it is on the latest version.
	2. Go to the Linker Configuration Properties
		1. Down to system and Select Console under SubSystem
4. Right click Source Files -> Add -> New Item
	1. Select C++ File and name it for example, main.cpp
5. To Run
	1. Use either F5 to debug or CTRL+F5 to run without debugging