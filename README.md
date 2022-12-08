# Build a portfolio website with Blazor Web Assembly, GitHub Codespaces y Azure Static Web Apps

> Workshop at Terasoft 2022

## Table of Contents
- [About this repo](#about-this-repo)
  - [What was the .NET Conf Student Zone?](#what-was-the-net-conf-student-zone)
  - [Digital Swag for the .NET Conf Student Zone 🎁🎉](#digital-swag-for-the-net-conf-student-zone-)
- [Setup Information](#setup-information)
  - [Using this repo and development container](#using-this-repo-and-development-container)
    - [GitHub Codespaces](#github-codespaces)
    - [VS Code Remote - Containers](#vs-code-remote---containers)
- [Student Resources](#student-resources)
- [Learning Resources](#learning-resources)
- [Trademarks](#trademarks)

# About this repo

This repo is a fork of the [dotnetconf-studentzone](https://github.com/microsoft/dotnetconf-studentzone). You will find that some projects have been deleted and only what is necessary to follow the workshop has been kept.

More details on this project can be found below.

| Session Title | Speaker(s) | Tools | Session Code | Video | Presentation |
|-------|---------|-----------|---|---|---|
| Build your Project Portfolio website with .NET | Matt Soucoup | Blazor | [Project Portfolio with Blazor Session](https://github.com/microsoft/dotnetconf-studentzone/tree/main/Build%20your%20Project%20Portfolio%20website%20with%20.NET/README.md) | [Watch On-Demand](https://youtu.be/SCJu7YPNtdQ?t=2596) |[Presentation](https://github.com/microsoft/dotnetconf-studentzone/blob/main/decks/Build-a-portfolio-using-blazor.pdf) |

## What was the .NET Conf Student Zone?
As part of [.NET Conf this year](https://www.dotnetconf.net/), we are hosting a .NET Student Zone on Monday, November 7! This is a livestreamed event where experts will introduce you to .NET and and build awesome, follow-along projects. You will walk away with a project portfolio on your very own portfolio website. In total the event will be 4+ hours of content.

## Digital Swag for the .NET Conf Student Zone 🎁🎉
[Download .NET Bot digital pet for VSCode](https://aka.ms/vscodepet)

![DotNetPet](/images/dotnetbotpet.jpg)

Puts a small, .NET Bot, bored cat, an enthusiastic dog, a feisty snake, a rubber duck, or Clippy 📎 in your VS Code editor to boost productivity.

# Setup Information

## Using this repo and development container

### GitHub Codespaces

Follow these steps to open this sample in a Codespace:
1. Click the Code drop-down menu and select the **Open with Codespaces** option.
1. Select **+ New codespace** at the bottom on the pane.

For more info, check out the [GitHub documentation](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces/creating-a-codespace#creating-a-codespace).

### VS Code Remote - Containers
Follow these steps to open this sample in a container using the VS Code Remote - Containers extension:

1. If this is your first time using a development container, please ensure your system meets the pre-reqs (i.e. have Docker installed) in the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started).

2. To use this repository, you can either open the repository in an isolated Docker volume:

    - Press <kbd>F1</kbd> and select the **Remote-Containers: Try a Sample...** command.
    - Choose the "Python" sample, wait for the container to start, and try things out!
        > **Note:** Under the hood, this will use the **Remote-Containers: Clone Repository in Container Volume...** command to clone the source code in a Docker volume instead of the local filesystem. [Volumes](https://docs.docker.com/storage/volumes/) are the preferred mechanism for persisting container data.   

   Or open a locally cloned copy of the code:

   - Clone this repository to your local filesystem.
   - Press <kbd>F1</kbd> and select the **Remote-Containers: Open Folder in Container...** command.
   - Select the cloned copy of this folder, wait for the container to start, and try things out!

3. **Rebuild or update your container**

   You may want to make changes to your container, such as installing a different version of a software or forwarding a new port. You'll rebuild your container for your changes to take effect. 

   **Open browser automatically:** As an example change, let's update the `portsAttributes` in the `.devcontainer/devcontainer.json` file to open a browser when our port is automatically forwarded.
   
   - Open the `.devcontainer/devcontainer.json` file.
   - Modify the `"onAutoForward"` attribute in your `portsAttributes` from `"notify"` to `"openBrowser"`.
   - Press <kbd>F1</kbd> and select the **Remote-Containers: Rebuild Container** or **Codespaces: Rebuild Container** command so the modifications are picked up.  

# Student Resources 
1. [Microsoft Student Resources](https://learn.microsoft.com/en-gb/training/student-hub/?wt.mc_id=studentamb_118941)   
2. [Azure for Student](https://azure.microsoft.com/es-es/free/students/?wt.mc_id=studentamb_118941) 
3. [GitHub Student Developer Pack](https://education.github.com/pack?wt.mc_id=studentamb_118941) 

# Learning Resources
Want more .NET Learning resources?
1. [Learn more C# and .NET](https://aka.ms/mslearn-dotnet)    
2. [Beginner video series](https://aka.ms/dotnetvideos)
3. [.NET Learning Paths on Microsoft Learn](https://aka.ms/mslearn-dotnet) 
4. [Beginner Videos on Blazor, .NET MAUI, ML.NET, and more](http://aka.ms/blazorvideos)
5. [.NET Documentation](http://aka.ms/dotnetdoc) 
6. [.NET MAUI](http://aka.ms/MAUIcrossplat) 
7. [Blazor Web Applications](http://aka.ms/blazorwebapp) 
8. [Minimal APIs](http://aka.ms/dotnetminimalapi) 
9. [ML.NET](http://aka.ms/trainmldotnet) 
10. [.NET IoT](http://aka.ms/dotnetIOT) 


Watch [.NET Conf](https://www.dotnetconf.net/)! Sessions start November 8th.

# Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
