# Trackables (releases)

Structured journaling for Obsidian period notes. A trackable is a markdown section, such as a Five-Minute Journal, that lives in your daily, weekly, monthly, quarterly or yearly notes and can be drawn anywhere as an editable table, with rollup and rolldown views. The markdown stays the source of truth.

This repo holds the release builds. The source is developed in a separate private repo, so issues here may not get a reply.

## Install with BRAT

1. In Obsidian, install and enable **BRAT** from Community plugins.
2. In BRAT's settings, choose **Add beta plugin**.
3. Enter `masonroyal/trackables-releases` and pick the latest version.
4. Enable **Trackables** under Community plugins.

No GitHub token is needed. BRAT can keep the plugin up to date from here.

## First run

In the plugin's settings, add a preset (Five-Minute Journal or Weekly Review), and check where it expects your period notes. Then put a `trackable` code block wherever you want the table.

## Install by hand

Download `main.js`, `manifest.json` and `styles.css` from the latest release into `<your vault>/.obsidian/plugins/trackables-plugin/`, then enable the plugin.

This is beta software. Back up your vault before trying it.
