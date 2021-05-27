---
title: Minecraft Attributes
layout: page
parent: Minecraft Project
---

This file stores any of the settings/attribtues related to the project. If none attributes are specified, the plugin will fall back onto plugin settings. Make sure the file is
located at the root of your workspace and named: `.mcattributes`

**Example**

```ini
diagnose=true
diagnose.objectives=true
diagnose.tags=true
diagnose.mcfunctions=true
```

## Settings

This vscode plugin responds to the following settings/attributes/

| Attribute               | Description                                                  |
| ----------------------- | ------------------------------------------------------------ |
| `education.enable`      | Disable or enable education edition for this project         |
| `diagnostic.enable`     | Disable or enable diagnostics for this project               |
| `diagnostic.json`       | Disable or enable diagnostics for json in this project       |
| `diagnostic.lang`       | Disable or enable diagnostics for language in this project   |
| `diagnostic.mcfunction` | Disable or enable diagnostics for mcfunction in this project |
| `diagnostic.objective`  | Disable or enable diagnostics for objectives in this project |
| `diagnostic.tag`        | Disable or enable diagnostics for tags in this project       |
