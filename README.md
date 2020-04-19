# artillery-vscode-extension

This is a VSCode Extension to use while writing Artillery.io Tests.

## Features

- Provides snippets for all hooks, so you don't have to remember the right function signature;
- Provides snippets for config, a basic scenario, and a scenario with all hooks, so you don't have to remember all the correct YAML indentation:

![](./images/functionSignatures.gif)

![](./images/artilleryScenarios.gif)

## Extension Settings

To be able to use the quick suggestions in a YAML file, you can use `ctrl + space` to get to the list of snippets. 

Or, you can alter your yaml settings by running the global command `Preferences: Configure Language Specific Settings`, choosing YAML, and then adding this setting:

```
    "editor.quickSuggestions": {
        "other": true,
        "comments": false,
        "strings": true
    }
```