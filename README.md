# AForge.NET fork

This is a fork of https://github.com/andrewkirillov/AForge.NET by Andrew Kirillov which migrates the projects referenced by DentalCAD to .NET6. These projects are

 - Core
 - Video
 - Video.DirectShow

 The project files have been renamed to match the namespaces, so they are now named AForge, AForge.Video and AForge.Video.DirectShow.
 
## Compiling the migrated projects

A VS2022 solution containing only the migrated projects can be found ins the `Sources` folder at: `./Sources/AForge.Video-Exocad.sln`. Since `WindowsForms` is used
in some projects the generated assemblies are currently limited to Windows (`net6.0-windows`).

## Important Note

Projects not used by exocad were removed.
