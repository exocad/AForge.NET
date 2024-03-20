# AForge.NET

This is a fork of https://github.com/andrewkirillov/AForge.NET by Andrew Kirillov which adds .NET6 support to projects used within exocad. These projects are

 - Core
 - Video
 - Video.DirectShow

 The project files have been renamed to match the namespaces, so they are now named AForge, AForge.Video and AForge.Video.DirectShow.
 
## Compiling the migrated projects

A VS2022 solution containing only the migrated projects can be found in the root folder: `Exocad.AForge.Video.sln`. Since `WindowsForms` is used
in some projects the generated assemblies are currently limited to Windows.

## Important Note

Projects not used by exocad were removed.
