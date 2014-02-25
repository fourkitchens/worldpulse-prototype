# World Pulse prototype

Prototype built with Jekyll and Bootstrap to explore the new approach to landing pages and navigation.

## Navigation

### Mega menu

Mega Menus are implemented using the Yamm (Yet Another Mega Menu) plugin for Bootstrap.

https://github.com/geedmo/yamm3

### Hover

:warning: We are not currently using hover menus

Main navigation dropdown menus expand on hover for desktop users. This is implemeneted via the [bootstrap-hover-dropdown][plugin] plugin. The plugin does not support clickable top-level menu items, so [this workaround][workaround] was used ([original issue thread][issue thread]).

Mobile users see a simplified menu with only links to the top-level items.

Note: Tablet users currently see the dropdown arrows even though they cannot expand them since they are hover-only.

[plugin]:       https://github.com/CWSpear/bootstrap-hover-dropdown
[workaround]:   https://github.com/CWSpear/bootstrap-hover-dropdown/issues/27#issuecomment-25760826
[issue thread]: https://github.com/CWSpear/bootstrap-hover-dropdown/issues/16
