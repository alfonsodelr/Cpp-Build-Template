Cpp-Build-Template

Description: Easy way to build project files in VS2022 without having to go through the process of Creating a Project from scratch.


Instructions:

1. Copy and Paste any files that are part of the project inside the "Project-Name" folder and inside its src folder.
2. Run the GenerateProjects.bat file by double clicking. This will generate a solution(.sln) file which you will double click.
3. Visual Studio (version) will open if done correctly.
4. Simply run/debug within VS to generate the binary and object files. 
5. Finished.



Important Notes:

1. If you want to change the "Project-Name" in the root directory, make sure you also change any instance of "Project-Name" within the .lua file, which can be opened using any text editor.
2. If you are running a version that is not VS2022, you must edit GenerateProjects.bat and change "vs2022" to the correct version of the application.
