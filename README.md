Reset Sharepoint CSS
===========

Author: jarrett drouillard ( @kuatsure )

Description: This file resets the Core.css file in Sharepoint. Core.css has a bunch of random styles that interfered with prettier styles that were created by better people.

Usage: Include this file in your masterpage (before or after your main theme styles).

````html
<link href="https://raw.github.com/kuatsure/Reset-Sharepoint-CSS/master/reset_sp.css" rel="stylesheet" type="text/css">
````

Author's Note: If you're using this reset, chances are you have a general reset anyways. But if you don't, might I suggest Eric Meyer's [CSS Reset](http://meyerweb.com/eric/tools/css/reset/)