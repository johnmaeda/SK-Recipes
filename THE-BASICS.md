# 😱 Never used GitHub or Visual Studio Code before? No problem. We've got you.

## A few definitions

First, here are a few definitions of concepts you will need to move forward:

* "GitHub repo" refers to this web page you're currently visiting [https://github.com/johnmaeda/SK-Recipes](https://github.com/johnmaeda/Recipes).
* "Visual Studio Code" is an application that runs on your computer. It lets you edit the various text files that create runnable software systems.
* "Visual Studio Code Extensions" are special "apps" that you can install into Visual Studio Code to extend its capabilities.
* "Polyglot Notebooks for VS Code" is a VS Code Extension — it's necessary for displaying the various `.ipnyb` files within VS Code.
* "Download the GitHub repo locally" means using GitHub.com to transfer the files being managed by GitHub as a ZIP file downloaded to your computer.
* "OpenAI or Azure OpenAI Service key" refers to a secret credential that only you have access to after you've signed up for either service.

## More notes on GitHub terminology

Next, because you're using GitHub it's useful to know the following:

* "Download the GitHub repo again" is something you will need to do if you used a ZIP file download because the directory does not stay in sync with what's on GitHub.com.
* "Clone the GitHub repo" means keeping a local copy of what's up on GitHub generally in sync with your local copy. If you're feeling ambitious to do so, instructions are [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).

## The steps you need to take to run the notebooks locally

We're going to go step-by-step through what you'll need to do:

1. Download and install [Visual Studio Code](https://code.visualstudio.com/Download)
2. Download and install [.Net 7.0 SDK](https://dotnet.microsoft.com/en-us/download)
3. Install [Polyglot Notebooks for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode) extension by hitting the green "Install" button. This will launch Visual Studio Code and put it in the right place.
4. Download the GitHub repo locally by clicking on the big green "<>Code" button and selecting "Download ZIP" or by [going here](https://github.com/johnmaeda/SK-How-Tos/zipball/main).
5. Unzip the file and you should have a brand new folder of files.
6. In Visual Studio Code choose "File > Open Folder ..." and select the folder you've freshly unzipped
7. Select the `notebook.ipnyb` that's inside the `s1e1-ez-starter-notebook` folder. It should display like a nicely formatted document.
8. Be sure to have your OpenAI or Azure OpenAI Service key ready. You can access your API key on OpenAI with [these instructions](https://help.openai.com/en/articles/4936850-where-do-i-find-my-secret-api-key), or on Azure Open AI Service with [these instructions](https://learn.microsoft.com/en-us/azure/cognitive-services/openai/reference).

🎉 You are now done with your set up to run Semantic Kernel completely from within VS Code's notebooks. There's no need to view files from GitHub.com anymore — you should be viewing them locally from your computer on VS Code. Good luck!