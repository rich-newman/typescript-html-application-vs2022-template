# Changelog

These are the changes to each version that have been released
on the official Visual Studio Marketplace.

## 1.1

**2022-09-22**

- Disambiguate setInterval.  Previously VS could get confused if there was anything node-related in the vicinity of the project, and refuse to compile because it thought we were using a node function.
- Run code through Prettier so the [TypeScript Analyzer](https://marketplace.visualstudio.com/items?itemName=RichNewman.TypeScriptAnalyzerEslintPrettier) doesn't show warnings.
- Update text on [Marketplace entry](https://marketplace.visualstudio.com/items?itemName=Rich-Newman.TypeScriptHTMLApplicationTemplate2022) on release to reference the old version of this extension for [Visual Studio 2019 and 2017](https://marketplace.visualstudio.com/items?itemName=Rich-Newman.TypeScriptHTMLApplicationTemplate)

## 1.0

**2022-09-21**

- Initial version of Visual Studio 2022 template, upgraded from the Visual Studio 2017/19 template, primarily to include TypeScript as a NuGet package as it's not included in Visual Studio 2022.