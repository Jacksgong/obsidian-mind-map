# Obsidian Mind Map

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/lynchjames/obsidian-mind-map/Release%20Build?logo=github&style=for-the-badge) ![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/lynchjames/obsidian-mind-map?style=for-the-badge&sort=semver)


This repository contains a plugin for [Obsidian](https://obsidian.md/) for viewing Markdown notes as Mind Maps using [Markmap](https://markmap.js.org/). 

A similar plugin is available for [Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=gera2ld.markmap-vscode).

## Something diffrents from the souce

This project is fork from [lynchjames/obsidian-mind-map](https://github.com/lynchjames/obsidian-mind-map), so what's new?


I add a settings to keeping the position and scale of the mindmap svg when you edit the some markdown file:


![](https://raw.githubusercontent.com/Jacksgong/obsidian-mind-map/main/images/not-adapt-size-all-the-time.gif)

If you don't need this feature, you can close(turn the `Readapt all the time` to `on`) it on the settings:

![](https://raw.githubusercontent.com/Jacksgong/obsidian-mind-map/main/images/mind-map-adaptallthetime-setting.png)

So if you tune the button up, you will get the same experience of the origin plugin:

![](https://raw.githubusercontent.com/Jacksgong/obsidian-mind-map/main/images/adapt-size-all-the-time.gif)

## Manual installation

1. Download the latest release
2. Extract the obsidian-enhancing-mindmap folder from the zip to your vault's plugins folder: /.obsidian/plugins/
3. Note: On some machines the .obsidian folder may be hidden. On MacOS you should be able to press Command+Shift+Dot to show the folder in Finder.
4. Run: `npm install` and `npm run build` onthe folder of the project.
5. Reload Obsidian
If prompted about Safe Mode, you can disable safe mode and enable the plugin.
