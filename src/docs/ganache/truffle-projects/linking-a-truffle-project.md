---
title: Ganache | Linking a Truffle Project
layout: docs.hbs
---
# Linking a Truffle Project

To link a project, enter the settings by clicking the gear icon in the upper right.

![Settings Icon](https://truffleframework.com/img/docs/ganache/v2-shared-seese/settings-icon.png)

You should be seeing the `WORKSPACE` settings pane; if not, you can get there by clicking the `WORKSPACE` tab in the top left.

![Workspaces Settings Pane Tab](https://truffleframework.com/img/docs/ganache/v2-shared-seese/workspaces-pane-tab.png)

From here, there is a section labeled `TRUFFLE PROJECTS`. Beneath this box, click the button `ADD PROJECT`. A file selection popup will appear. Navigate to the folder of your Truffle project, and select the `truffle-config.js` or `truffle.js` configuration file. The file you pick **must** be either named `truffle-config.js` or `truffle.js` for Ganache to correctly load it.

After selecting the file, you'll see it listed in the `TRUFFLE PROJECTS` section.

![Project Listed](https://truffleframework.com/img/docs/ganache/v2-shared-seese/project-listed.png)

You can add multiple projects to a workspace. After you're finished with adding projects you can click the `SAVE AND RESTART` (`SAVE WORKSPACE` if this is a new workspace) button in the top right.