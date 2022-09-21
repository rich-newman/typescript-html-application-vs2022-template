# TypeScript HTML Application Template
A [template for new projects in Visual Studio 2022](https://marketplace.visualstudio.com/items?itemName=Rich-Newman.TypeScriptHTMLApplicationTemplate2022) that creates an HTML application with TypeScript.  This is the same template that that used to be in Visual Studio 2015.  A [separate template is available for Visual Studio 2017 or Visual Studio 2019](https://marketplace.visualstudio.com/items?itemName=Rich-Newman.TypeScriptHTMLApplicationTemplate).

The project contains an HTML file, a CSS file and a TypeScript file with some basic sample code.

One advantage of this template is that **it allows debugging from Visual Studio** in Chrome, Edge and Internet Explorer.  Just create a project with the template, set a breakpoint in Visual Studio, and hit F5.  There is no need to install packages or bring up browser development tools.  This makes the template useful as an HTML plus TypeScript playground.

The built template can be installed from [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=Rich-Newman.TypeScriptHTMLApplicationTemplate2022), or from within Visual Studio.  Search for 'TypeScript HTML Application Template' in the extensions dialog.

In the Visual Studio New Project dialog the easiest way to find it is to filter by Language=TypeScript, and then it will appear at or towards the bottom of the list.  In both cases it appears as 'HTML Application with TypeScript'.

When started with F5 it will start a web server, by default IIS Express, and show a ticking time in the selected web browser.  The code to show the time is in a TypeScript class.  If the browser is Internet Explorer, Edge or Chrome the code will break at breakpoints directly in Visual Studio, and the usual Visual Studio debug tools and windows will be available.  Note that if you are using Chrome you may need to hit refresh in the browser for breakpoints in startup code to be hit.

This template is based on ASP.NET, so you **will need the ASP.NET workload installed in Visual Studio**.  If the workload is not there the template will not appear.  It does not need Node.js development or .Net desktop development workloads.

This template installs TypeScript locally to the project on project creation, using a NuGet package.  This is because TypeScript is no longer included in Visual Studio by default.