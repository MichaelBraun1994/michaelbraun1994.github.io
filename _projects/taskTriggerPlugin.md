---
title: Task Trigger VSCode Extension 
description: A VSCode extension to display and trigger tasks in the explorer view.
layout: project
image: /assets/images/tasktrigger/icon.png
links:
    - name: Github Repo
      url: https://github.com/MichaelBraun1994/vscode-task-trigger
    - name: VSCode Marketplace
      url: https://marketplace.visualstudio.com/items?itemName=MichaelBraun1994.task-trigger
---

Task trigger is a VSCode extension that groups all available tasks in a workspace and displays them in the explorer view.

<p>
<img src="/assets/images/tasktrigger/screenshot.png" alt="Example image" style="float:left; margin:0 1rem 1rem 0; width:150px; border-radius:8px;" />
Tasks are grouped by sources and subfolders within the sources, based on a configurable separator regular expression. For example, the task name `FolderA: TaskA` creates a `FolderA` containing a `TaskA` (with separator regex set to `":"`).

Clicking on any displayed task triggers the execution of the configured command in VSCode’s tasks.json file.

</p>
<div style="clear:both;"></div>

The extension can be installed via the VSCode extension marketplace with the ID *MichaelBraun1994.task-trigger*.