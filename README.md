# Undo Close Tab Replacement

An updated version of [DarkTrojan](https://www.darktrojan.net)'s bootstrapped extension to replace the Undo Close Tab context menu item for Waterfox G3 & Firefox (78+ with [userChromeJS](https://github.com/xiaoxiaoflood/firefox-scripts) or [bootstrapLoader](https://github.com/xiaoxiaoflood/firefox-scripts/tree/master/extensions/bootstrapLoader)) with the Recently Closed Tabs menu.

In Firefox Developer Edition (as of 86.0) a userChrome.css addition is required to display the Undo Close Tab menu item in the first place:

`#toolbar-context-undoCloseTab {
	display: block !important;
}`
