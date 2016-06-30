Adding this NuGet package to your project will add a 'Project.targets' MSBuild file to your project, 
and automatically include that file in command line and Visual Studio builds.

Tip:  if you have common targets you want to apply across numerous projects in your solution, 
edit the Project.targets file to simply <Import Project="$(SolutionDir)\Common.targets" /> or
something similar.