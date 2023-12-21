# Description

ZedGraph is a class library, user control, and web control for .net, written in C#, for drawing 2D Line, Bar, and Pie Charts. It features full, detailed customization capabilities, but most options have defaults for ease of use.

This is a port to .NET 8 of the original ZedGraph package <https://github.com/ZedGraph/ZedGraph>, all credits to the original author John Champion, RIP in 2009 <https://www.legacy.com/us/obituaries/orangecounty/name/john-champion-obituary?id=23084919>.

Also thanks to the guys who ported this from sourceforge to github.

The original tutorial about how to use the library is
<https://www.codeproject.com/Articles/5431/A-flexible-charting-library-for-NET> and another one with lots of useful links <https://swharden.com/csdv/plotting-free/zedgraph/>

To use this you can clone this repo, and then include the 2 projects in your solution and add a project reference to the WinForms project. Or you should be able to build and add a reference to the dll if you prefer. If anyone has the time to put that on nuget that would be great so it will be easier for people to use the library.

Note that this is only the winforms part of the project, I excluded the web based part as there are many better frameworks now, and the tests project because I don't have time to port them. Also I excluded the signing key as I am using this locally only.

I haven't done extensive testing so there might be some bugs but it seems to work for me.
