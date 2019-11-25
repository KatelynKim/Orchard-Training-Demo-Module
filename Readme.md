# Orchard Core Training Demo module



## Project description

Demo Orchard Core module for training purposes guiding you to become an Orchard developer. Note that this module also has an Orchard 1.x version in the [dev branch of the repository](https://github.com/Lombiq/Orchard-Training-Demo-Module/tree/dev).

**If you are interested in training materials and Orchard trainings please visit [Orchard Dojo](https://orcharddojo.net/).**


## How to start

You can use (and are recommended to use) this module as part of a vanilla Orchard Core source that includes the full source code. You can also use it as part of a solution that uses Orchard Core NuGet packages. Note that it is harder to inspect Orchard Core features.

Demo Orchard Core module depends on **[Lombiq.VueJs](https://github.com/Lombiq/Orchard-Vue.js)**, so you must download Lombiq.VueJs and place it next to this module.

The module assumes that you have a good understanding of basic Orchard concepts and are familiar with the Orchard admin area (the [official documentation](https://orchardcore.readthedocs.io/en/latest/) may help you with that), Visual Studio, C#, and the concepts of ASP.NET Core MVC.


### Using a full Orchard Core source

1. Open an Orchard Core solution. You can download or `git clone` Orchard from [GitHub](https://github.com/OrchardCMS/OrchardCore/).
2. Add this project and the Lombiq.VueJs project to the solution (place the projects **next to each other** in any folder).
3. Add these two projects as references to the `OrchardCore.Application.Cms.Targets` project (this project is in the *src/Targets* solution folder).
4. Set the `OrchardCore.Cms.Web` project as the startup project if it isn't already and run it (F5 or CTRL+F5).
5. Setup the website using the "Training Demo" recipe.


### Using NuGet packages

1. Open a web project that uses Orchard Core NuGet packages or create one (see: https://orchardcore.readthedocs.io/en/latest/Templates/README/#generate-an-orchard-cms-web-application).
2. Add this project and Lombiq.VueJs to the solution.
3. Add these projects as references to the web project.
4. Run the web project (F5 or CTRL+F5).
5. Set up the website using the "Training Demo" recipe.


## Using this module for training purposes

If your module compiles and is enabled on the dashboard, then go to the **[StartLearningHere.md](StartLearningHere.md)** file and explore all the features of Orchard Core.

If you are brave enough to not follow any guide or you want to start the guide from somewhere else, then go to the **Map.cs** file and jump to any class of your interest.


## Contribution and feedback

The module's source is available in two public source repositories, automatically mirrored in both directions with [Git-hg Mirror](https://githgmirror.com):

- [https://bitbucket.org/Lombiq/orchard-training-demo-module](https://bitbucket.org/Lombiq/orchard-training-demo-module) (Mercurial repository)
- [https://github.com/Lombiq/Orchard-Training-Demo-Module](https://github.com/Lombiq/Orchard-Training-Demo-Module) (Git repository)

Bug reports, feature requests and comments are warmly welcome, **please do so via GitHub**. Feel free to send pull requests too, no matter which source repository you choose for this purpose.

This project is developed by [Lombiq Technologies Ltd](https://lombiq.com/). Commercial-grade support is available through Lombiq.
