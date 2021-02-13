# Undo Close Tab Replacement

An updated version of [DarkTrojan](https://www.darktrojan.net)'s bootstrapped extension to replace the Undo Close Tab context menu item in Firefox (78+) with the Recently Closed Tabs menu.

In Firefox Developer Edition (as of 86.0) a userChrome.css addition is required to display the Undo Close Tab menu item in the first place:

`#toolbar-context-undoCloseTab {
	display: block !important;
}`
