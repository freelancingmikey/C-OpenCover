# C-OpenCover
UnitTestTargetProject is our Class project which contains methods that we need to add to unit test.
MyUnitTests contains unit test cases for above mentioned Project.
Compile solution and run the file RunTests.bat in case you are building on your desktop and don't want to use AppVeyor. This batch file contains command to execute test cases and generate file for codecoverage.
Project uses Nuget Package of Open Cover : 4.6.166
The root directory contains .yml file to be used by AppVeyor. AppVeyor doesn't need the batch file mentioned above.
