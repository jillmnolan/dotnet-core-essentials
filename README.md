# README


## Introduction

The premise of the **.NET Core Essentials** is to allow the .NET Core developer to have all the essential plugins at their disposal to extend the features and functionality of VSCode with the convenience of a **one-click installation** process.  The ultimate goal for this extension pack is: **convenience**.  After all, the main inspiration is to help .NET developers and the vocational teachers at my place of employment to have a one-stop place for all the necessary extension.

* **Please be advised that this is an "off-the-clock" passion side project. :-)**

* **Please be advised that the README file will be reformatted and better descriptions inserted in the near future. Cheers!**

* **Please do not hesitate to make suggestions on how to improve this extension pack in the [Issues section](https://github.com/jillmnolan/dotnet-core-essentials/issues).  Your feedback and suggestions are appreciated immensely.**


## Extensions


### Themes

* [**Community Material Theme**](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-community-material-theme): A **VS Code plugin** featuring the Material Theme with 'legacy' color schemes that has been embarced by the developer community.

* [**Studio Icons**](https://marketplace.visualstudio.com/items?itemName=jtlowe.vscode-icon-theme): A **VSCode plugin** featuring official icons from the **Visual Studio Image Library**. **Note**: These icons have been color optimized to work well for dark, light, and high contrast themes.


### C# Support

* [**C#**](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp): A **VSCode plugin** that provides support for:
  * Lightweight development tools for **.NET Core**.

  * **C# editing support**, including but not limited to **Syntax Highlighting**, **IntelliSense**, **Go To Definition**, and **Find All References**, respectively.

  * **Debugging support for .NET Core (CoreCLR)**. NOTE: **Mono debugging** is not supported; whereas, **Desktop CLR debugging** has limited support.

  * Support for **project.json** and **csproj projects** on **Windows**, **macOS**, and **Linux**.

* [**C# IL Viewer**](https://marketplace.visualstudio.com/items?itemName=josephwoodward.vscodeilviewer): A **VSCode plugin** for **IL (Intermediate Language) Viewer** that allows the rapid inspection of the **IL output** of any given **C# file**.

* [**C# Extensions**](https://marketplace.visualstudio.com/items?itemName=jchannon.csharpextensions): A **VSCode plugin** that provides extensions in an effort to speed up development workflows.

* [**C# Namespace Autocompletion**](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.namespace): A **VSCode plugin** that pulls **namespace autocompletion** for **C#**.

* [**C# XML Documentation Comments**](https://marketplace.visualstudio.com/items?itemName=k--kato.docomment): A **VSCode plugin** that generate **XML documentation comments** for **Visual Studio Code**.


### .NET Framework

* [**ASP.NET Core**](https://marketplace.visualstudio.com/items?itemName=schneiderpat.aspnet-helper): A **VSCode plugin** that parses your project to enable **IntelliSense** for **Razor pages** within an **ASP.NET MVC project**.

* [**.NET Core Test Explorer**](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet-test-explorer): A **VSCode plugin** that serves as **Test Explorer** for **.NET Core**, specifically support for (1) **MSTest**, (2) **xUnit**, and (3) **NUnit**.

* [**.NET Core Tools**](https://marketplace.visualstudio.com/items?itemName=formulahendry.dotnet): A **VSCode plugin** that builds, runs, and tests **.NET Core project**, whether **C#** or **F#**.

* [**.NET Core User Secrets**](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.user-secrets): A **VSCode plugin** that supports right-selecting a **.csproj file** in the **Explorer** and select **Manage User Secrets** from the **context menu** to insert **auto-generated UserSecretsId element** and/or open associated **secrets.json file**.

* [**.NET Core Add Reference**](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.add-reference): A **VSCode plugin** that either adds or removes **references** of your **.NET Core projects**.

* [**VSCode-proto3**](https://marketplace.visualstudio.com/items?itemName=zxh404.vscode-proto3): A **VSCode plugin** that provides **Protobuf 3** support.

* [**Run Terminal Command**](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.terminal-commands): A **VSCode plugin** that runs predefined **terminal commands** from either the **Explorer context menu** or the **Command Palette**, respectively.

* [**Essential ASP.NET Core 3 Snippets**](https://marketplace.visualstudio.com/items?itemName=doggy8088.netcore-snippets): A **VSCode plugin** that boosts high quality code snippets that boost your **ASP.NET Core** development productivity.

* [**ASP.NET Core Switcher**](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.asp-net-core-switcher): A **VSCode plugin** that quickly switch between **views**, **controllers**, **pages**, **page models**, and **Blazor components** in **ASP.NET Core** using **keybindings**, **context menu**, or **command palette**.

* [**LibMan Tools**](https://marketplace.visualstudio.com/items?itemName=adrianwilczynski.libman): A **VSCode plugin** providing **LibMan** support.

* [**Super Sharp**](https://marketplace.visualstudio.com/items?itemName=craigthomas.supersharp): A **VSCode plugin** that adds **constructor injected dependencies** from anywhere inside a **class**. **Note**: The **refactor** is available when the **cursor** is inside a **class** that contains a **constructor**.


### NuGet Functionalities

* [**MSBuild Project Tools**](https://marketplace.visualstudio.com/items?itemName=tintoy.msbuild-project-tools): A **VSCode plugin** that provides **Intellisense** for **MSBuild project files**, including **auto-complete** for **<PackageReference>** elements.

* [**NuGet Package Manager**](https://marketplace.visualstudio.com/items?itemName=jmrog.vscode-nuget-package-manager): A **VSCode plugin** that allows for add or remove **.NET Core 1.1+ package references** to and from your project's **.csproj** or **.fsproj files** using **Command Palette**.

* [**Path Intellisense**](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense): A **VSCode plugin** that *autocomplete* **filenames**.

* [**Version Lens**](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens): A **VSCode plugin** displaying **version information** when opening a **package** or **project** for either:

  * [**dotnet](https://www.dotnetfoundation.org/);

  * [**dub**](https://code.dlang.org/);

  * [**jspm**](https://jspm.io/);

  * [**maven**](https://maven.apache.org/);

  * [**npm**](https://www.npmjs.com/);

  * [**pub**](https://pub.dev/); and,

  * [**composer**](https://getcomposer.org/).

* [**NuGet Reverse Package Search**](https://marketplace.visualstudio.com/items?itemName=jesschadwick.nuget-reverse-package-search): A **VSCode plugin** that adds the **reverse .NET Core package lookup support** such as the **Add Package** context menu item in full **Visual Studio**.


### Support

* [**Better Comments**](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments): A **VSCode plugin** whose premise is to create more human-friendly comments in your code, whereby you will be able to *categorize* your **annotations** into:

  * Alerts.

  * Queries.

  * TODOs.

  * Highlights.

  * Commented out code can be styled to make it clear the code should not be there.

  * Any other comment styles you'd like can be specified in the settings.

* [**Copy Text**](https://marketplace.visualstudio.com/items?itemName=salbert.copy-text): A VSCode plugin offers that copies text without colors, optionally adds metainfo such as the document name and its date.

* [##EditorConfig for VS Code##](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig): A VSCode plugin that provides ##EditorConfig Support## for VSCode.

* [##GitIgnore##](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore): A VSCode plugin that provides language support for .gitignore files, whereby allowing you to pull .gitignore files from the [##gitignore##](https://github.com/github/gitignore) repository.

* [##GitLens — Git supercharged##](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens): A VSCode plugin that supercharges its off-the-shelf Git capabilities, including but not limited to (1) visualize code authorship at a glance via Git blame annotations and code lens, (2) seamlessly navigate and explore Git repositories, and (3) gain valuable insights via powerful comparison commands.

* [##Live Share Extension Pack##](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack): A VSCode extension pack, which includes:

  * [##Live Share##](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare): A VSCode extension that supports real-time collaborative development.

  * [##Live Share Audio##](https://marketplace.visualstudio.com/items?itemName=ms-vsliveshare.vsliveshare-audio): A VSCode extension that adds audio calling capabilities to ##Live Share##.

* [##MSSQL##](https://marketplace.visualstudio.com/items?itemName=ms-mssql.mssql): A VSCode plugin that supports developing ##Microsoft SQL Server##, ##Azure SQL Database##, and ##SQL Data Warehouse##, whose functionalities including but not limited to:

  * Connect to Microsoft SQL Server, Azure SQL Database and SQL Data Warehouses.

  * Create and manage connection profiles and most recently used connections.

  * Write T-SQL script with IntelliSense, Go to Definition, T-SQL snippets, syntax colorizations, T-SQL error validations and GO batch separator.

  * Execute your scripts and view results in a simple to use grid.

  * Save the result to json or csv file format and view in the editor.

  * Customizable extension options including command shortcuts and more.

* [##Quokka.js##](https://marketplace.visualstudio.com/items?itemName=WallabyJS.quokka-vscode): A VSCode plugin that supports rapid both ##JavaScript## and ##TypeScript## prototyping. ##Note##: ##Runtime values## are updated and displayed in the IDE next to your code, as you type.

* [##Paste JSON as Code##](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype): A VSCode plugin that supports such languages as TypeScript, C#, JavaScript, and JSON Schema:

  * Interactively generate types and (de-)serialization code from JSON, JSON Schema, and TypeScript.

  * Paste JSON/JSON Schema/TypeScript as code.

* [##TODO Highlight##](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight): A VSCode plugin that highlights TODO, FIXME, and other annotations within your code.

* [##Visual Studio Keymap##](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vs-keybindings): A VSCode plugin that ports popular VS keyboard shortcuts. ##Note##: After installing the extension and restarting VSCode, your favorite keyboard shortcuts from VS are now available.

* [##Highlight Trailing White Spaces##](https://marketplace.visualstudio.com/items?itemName=ybaumes.highlight-trailing-white-spaces): A VSCode plugin that highlights in red color trailing white spaces.

* [##Quick and Simple Text Selection##](https://marketplace.visualstudio.com/items?itemName=dbankier.vscode-quick-select): A VSCode plugin that selects between including but not limited to quote, brackets, and tags.

* [##Bracket Pair Colorizer 2##](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2): A VSCode plugin that allows matching brackets to be identified with colours. The user can define which tokens to match, and which colours to use.

* [##MarkdownLint##](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint): A VSCode plugin that serves as its Markdown linting and style checking.


### Azure Support

* [##Azure Serverless Tools##](https://marketplace.visualstudio.com/items?itemName=MarcusLyons.azure-serverless-tools): A VSCode extension pack that includes these plugins:

    * [##Azure Functions##](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions), which is a plugin that quickly create, debug, manage, and deploy serverless apps directly from VS Code.

    * [##Azure Databases##](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-cosmosdb), which is a plugin that browses and queries your Azure databases both locally and in the cloud using #scrapbooks# with rich Intellisense then connect to Azure to manage your PostgreSQL and Cosmos DB databases with support for MongoDB, Graph (Gremlin), and SQL.

    * [##Azure Terraform##](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azureterraform), which is a plugin that is designed to increase developer productivity authoring, testing and using Terraform with Azure. ##Note##: This plugin provides terraform command support, resource graph visualization and CloudShell integration inside VSCode.

    * [##Azure Pipelines##](https://marketplace.visualstudio.com/items?itemName=ms-azure-devops.azure-pipelines), which is a plugin that adds syntax highlighting and autocompletion for Azure Pipelines YAML to VS Code. Likewise, this plugin allows you set up continuous build and deployment for Azure Web Apps without leaving VSCode.

    * [##Azure Storage##](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurestorage), which is a Microsoft-managed service providing cloud storage that is highly available, secure, durable, scalable, and redundant. ##Note##: Use the extension to deploy static websites and Single Page Apps (SPAs) and browse Azure Blob Containers, File Shares, Tables, and Queues.

    * [##Azure Account##](https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account), which provides a single Azure sign-in and subscription filtering experience for all other Azure extensions. ##Note##: This plugin makes Azure's Cloud Shell service available in VSCode's integrated terminal.
