---
layout: main
title: Development
section: development
subsections: [Roadmap, Known Issues, Bug reporting, Changelog, License, Donations]
subsectionsShort: [roadmap,  issues,  bugreporting, changelog, license, donations]
order: 1
---

## Development

The code of the extension is hosted on [Github] (https://github.com/micheleg/dash-to-dock/): get involved in the development, report a bug, contribute!

<ul id="button">
<li>
  <p><a class="star" href="http://github.com/micheleg/dash-to-dock">Get involved </a></p>
  <p>Browse the <a href="http://github.com/micheleg/dash-to-dock">GitHub development page</a> and get involved in the development.</p>
</li>
</ul>

<a name="roadmap"></a>
### Roadmap

1. Keep the extension updated with new upstream versions.
2. Improve integration with the shell, avoiding inconsistencies and taking advantage of new features (like pressure sensitivity) or design.
3. In the long term, rewrite and simplify the code.

There aren't mayor features planned, but many bugs that I would like to see fixed (see below).

Things I'm not going to do:

 * put the dash at the bottom of the screen (unless it proves to be feasible and compatible with the upstream Gnome Shell design)
 * adding random features unrelated to the dash

<a name="issues"></a>
### Known Issues
 * Missing padding for dekstop icons with Nautilus show desktop enabled. See [Issue 17] (https://github.com/micheleg/dash-to-dock/issues/17).
 * In multimonitor configuration when the dock is hidden it slides in the adjacent monitor if any is present. Although the dock is not visible it still steals mouse clicks from other windows. See [Issue 28] (https://github.com/micheleg/dash-to-dock/issues/28).

<a name="bugreporting"></a>
### Bug Reporting
If you experienced a bug please report it by opening an [isssue on github](https://github.com/micheleg/dash-to-dock/issues). You can also send a bug report message in the [extension website](https://extensions.gnome.org/extension/307/dash-to-dock/). Your help is very appreciated.

Please provide as many details as possible and all the steps to reproduce the bug. Include the following information:
 * Extension version
 * Gnome Shell version
 * Linux distribution and version
 * Whether you have a multi-monitor configuration
 * Your settings: include the output of the command <code>dconf dump /org/gnome/shell/extensions/dash-to-dock/</code>.

Before reporting a bug:

 * Check if the bug persists disabling all other extensions. If not, try to find the conflicting extension by enabling each extension one at a time.
 * Check if there are any relevant errors in Looking Glass (<code>ALt-F2 lg</code>, error panel).
 * Reload the shell by typing in a terminal (as normal user) <code>gnome-shell --replace</code> and look for relevant output in that terminal when the bug appears. 
 * Try to reset the extension settings to their default values with the command <code>dconf reset /org/gnome/shell/extensions/dash-to-dock/</code>


<a name="changelog"></a>
### Change log

Version numbering follows the uploads to the extension website.

**Version 18 (13-11-2012)**

  * Rebase the dash code adding the application button

**Version 17 (23-10-2012)**

 * First Gnome Shell 3.6 only release
 * Update to 3.6 API fixing a couple of bugs

**Version 16 (19-10-2012)**

 * Correct syntax error in the previous version

**Version 15 (19-10-2012)**

 * Initial Gnome Shell 3.6 support: just make the extension load

**Version 14 (04-09-2012)**

 * Extend app icons with running and focused indicators (require supporting theme)
 * Add customization of click action
 * Rework vertical positioning: drop uncentered alignment and add an experimental extended mode
 * Bug fixing

**Version 13 (14-08-2012)**

 * bug fixing for multimonitor support

**Version 12 (12-08-2012)**

 * RTL languages support.
 * Add Application based intellihide.
 * Minor improvements to the switch workspace on scroll feature.
 * Bug fixing.

**Version 11 (22-07-2012)**

 * Allow to choose the monitor where the dock is shown.
 * Enable dash accessibility via ctrlAltTab.
 * Directly customize the dash background opacity.

**Version 10 (09-07-2012)**

 * Option to center the dock vertically.
 * Option to increase the maximum dock height.
 * Settings GUI overhaul.

**Version 9 (24-06-2012)**

 * Basic Bolt extensions support.
 * Bug fixing.

**Version 8 (23-06-2012)**

 * Gnome Shell 3.4 only release.
 * Greatly improve multimonitor support.
 * Improve intellihide efficiency.
 * Improve autohide.
 * Improve settings GUI.
 * Add swith workspace on scroll feature.
 * Option to control the maximum icon size.
 * Option to show favorites and/or running application icons.
 * Bug fixing.

**Version 7 (12-06-2012)**

 * Gnome Shell 3.2 only release, last version supporting 3.2.
 * Greatly improve multimonitor support.
 * Bug fixing.

**Version 6 (03-06-2012)**

 * Bug fixing.

**Version 5 (02-06-2012)**

 * Move settings to a gschema for Gnome Shell 3.4.
 * Add settings GUI form Gnome Shell 3.4.
 * Minor improvements.

**Version 4 (29-05-2012)**

 * Minor improvements.
 * Bug fixing.

**Version 3 (23-05-2012)**

 * Basic theme indipendece.
 * Intellihide/autohide settings.
 * Minor improvements.
 * Bug fixing .

**Version 2 (20-05-2012)**

* Inline timing settings.
* Bug fixing.

**Version 1 (12-05-2012)**

* Initial release.
* Basic intellihide functionality.

<a name="license"></a>
### License
Dash to Dock Gnome Shell extension is distributed under the terms of the GNU General Public License,
version 2 or later. See the COPYING file for details.

<a name="donations"></a>
### Donations

<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<p>You can <a href="http://flattr.com/thing/1047592/" target="_blank"> <img src="http://api.flattr.com/button/flattr-badge-large.png" alt="Flattr this" title="Flattr this" border="0" style="vertical-align:middle" /></a> or 
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="T62ZE74K6ST38">
<input type="image" src="https://www.paypalobjects.com/en_GB/i/btn/btn_donate_SM.gif" border="0" name="submit" alt="PayPal – The safer, easier way to pay online." style="vertical-align:middle">
<img alt="" border="0" src="https://www.paypalobjects.com/it_IT/i/scr/pixel.gif" width="1" height="1">.</p></form>