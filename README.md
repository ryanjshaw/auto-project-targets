# auto-project-targets
NuGet package to automatically import an MSBuild targets file without manually editing your project files

Adding this NuGet package to your project will add a 'Project.targets' MSBuild file to your project, 
and automatically include that file in command line and Visual Studio builds.

This allows you to hook into the full range of MSBuild events and use the full power of MSBuild, e.g.:
* Create a custom version number based on source control properties
* Write out that version number to a file that is automatically included in the build
* Notify the build server of the version number
* Package your application using the version number