# MANAGING VSCODE EXTENSIONS

## **Table of Content**
[Vs Code Extensions](#vs-code-extensions)

[Installing Extensions ](#installing-extensions)

[Extension Details Page](#extensions-details-page)


[Extension Pack and Dependencies](#extension-pack-and-dependencies)

[Disable and Enable](#disable-and-enable-extension)

[Conclusion](#conclusion)

## **VS Code Extensions**
Visual Studio Code (VS Code) is an open source and cross-platform editor made by Microsoft with the Electron Framework, for windows, Linux and macOS. VS Code have features that support syntax highlighting, intelligent code completion, debugging, snippets, code refactoring and embedded Git. Users can install extensions to increase and add functionality to VS code. With Vs code extensions you can add debuggers, languages and tools to support your development workflow. VS Code Marketplace has thousands of extensions that support hundreds of tasks and programming language. You can find simple extensions that create GUIDs,change the color theme, check code errors and also extensions that support languages like Java, Go, Python, Javascript, Typescrpit.

## **Installing Extensions**
You can install extensions from within VS Code. Click on the extensions icon in the Activity Bar which is located on the left side of the Vs Code. You can use Command (ctrl+shift+X).

![pull mockup](./images/Screenshot%20(3).png)

The first page of the Marketplace would be either list of popular Vs code Extensions or recommended  extensions. You can select the extension of your choice from the list to display the extensions details page to learn more about the extension.

![pull mockup](./images/Screenshot%20(5).png)

To install an extension, click the install button. Once installation is complete, the install button will change to manage button.

For example lets install the Live server extension.  This is an extension that hosts a local server for you to preview your web projects.

![pull mockup](./images/Screenshot%20(4).png)

When you open the extension view type `live server` in the search box. You would see the live server extension in the list. Select the extension and click install button. 

![pull mockup](./images/Screenshot%20(5).png)

When the installation is complete the install button will change to Disable and uninstall.

![pull mockup](./images/Screenshot%20(6).png)

Firstly open a source code file were you are writing a web development program or an empty file. I have an opened HTML file 

![pull mockup](./images/Screenshot%20(10).png)

You will see the `GO live` at the foot status bar. Click on it and it will change to starting. Your default browser will open in another window showing you the live preview of your code. Mine has shown me the live preview of my HTML project

![pull mockup](./images/Screenshot%20(13).png)

![pull mockup](./images/Screenshot%20(14).png)

The extension provides settings for rendering its behavior, which you can find in the settings editor or hold (ctrl+,). You can also type in Live server in your command palette (ctrl+shift+P) this will show a drop down menu that lets you turn live server off or on and change some settings.

![pull mockup](./images/Screenshot%20(8).png)

When an extension does not give you the functionality you want you can always uninstall.

![pull mockup](./images/Screenshot%20(6).png)

## **Extensions Details page**
For every extension there are details about how to use and manage the extension and the include;
- Details on shortcuts for easy use of the extensions
- Details on the features and Functionality of the extensions
- Details on how to install and disable the extension 
- settings details, the different versions and whats new about each recent version 

![pull mockup](./images/Screenshot%20(15).png)

![pull mockup](./images/Screenshot%20(16).png)

`Note` that kind details found on an extensions details page varies from one extension to another.

## **Extension Pack and Dependencies**
An extension packs is a group of extensions which are installed together. They are a group or list of extensions dependent on each other or used together. Different extensions can be bundled together into one extension pack because the serve the same development purpose. An extension pack bundles other extensions using `extensionpack` attribute inside the `package.json` file. If an extension is an extension pack, the extension pack will show you which extension will installed when you install the pack. Anyone can bring together all there list of favorite extensions currently installed on their Vs code and publish it to the Marketplace for others to download. To create an extension pack, you can use the `yo code` Yeoman generator and choose the New Extension Pack option.

![pull mockup](./images/Screenshot%20(22).png)

Example of an extension pack is the `Python Extension Pack` bundled together by Don Jayamanne. Don has put together good tools for making cloud and application development with Python language easier. There are other packs like that on the Marketplace for other languages and Frameworks.

![pull mockup](./images/Screenshot%20(20).png)

![pull mockup](./images/Screenshot%20(21).png)

## **Disable and Enable Extension**
You can disable your extension either globally or for your current workspace. You do not need to uninstall an extension if you do not need it for a current project. To disable an extension go to the extension marketplace view page and under the installed extension view select the extension you do not wish to work with and when the details page of the extension opens up, then you can click the disable button. The same procedure is used to Enable and extension that has been disabled. 

![pull mockup](./images/Screenshot%20(23).png)

![pull mockup](./images/Screenshot%20(25).png)

If you want to disable all installed extensions, there is a `Disable All Installed Extensions` command in the `More Actions`(...) dropdown menu in the Extension view page. Extensions will remain disable for all VS Code projects until re-enabled. The same could be done to `Enable All Extensions`.  

![pull mockup](./images/Screenshot%20(24).png)


## **Conclusion**
Extensions make working with VS Code easier, faster, fun and less daunting. There are lots of extensions the Marketplace. Choosing extensions for your workspace depends on the framework, programming language and what you want to achieve with your project. There are also extensions that beautifies your workspace, gives your nice icons and so many other functions. You could open up the Extension Marketplace and play around with more extension and know what the are used for

What has been explained in this article are the basic knowledge for managing extensions there is more to know which will be presented in future articles.