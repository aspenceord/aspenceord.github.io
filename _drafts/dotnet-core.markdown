---
layout: post
title:  ".NET Core on Mac OS X"
---

I'm transitioning from using a Windows 10 desktop to a Macbook Pro as my main personal machine at the moment. While I don't get Visual Studio, I do get to use C# in the form of [.NET Core](https://www.microsoft.com/net/core).

Following the instructions it was all very easy to get installed and a simple Hello, World running. There was a bit more work getting it working in Visual Studio Code however. It should just be a matter of installing the [OmniSharp C# addon for VSCode](https://github.com/OmniSharp/omnisharp-vscode), but I immediately got an error saying that the .NET CLI tools could not be found. This of course meant the debugger wouldn't work from within VSCode. Luckily it turned out all I needed to do was quit VSCode (not just close it) and restart to get it to pick up the new path. 