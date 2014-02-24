# World Pulse prototype

Prototype built with Jekyll and Bootstrap to explore the new approach to landing pages and navigation.

## Navigation

Main navigation dropdown menus expand on hover for desktop users. This is implemeneted via the [bootstrap-hover-dropdown](https://github.com/CWSpear/bootstrap-hover-dropdown) plugin. The plugin does not support clickable top-level menu items, so the following workaround was used.

* https://github.com/CWSpear/bootstrap-hover-dropdown/issues/27#issuecomment-25760826
* Related discussions in [this issue thread](https://github.com/CWSpear/bootstrap-hover-dropdown/issues/16)

Mobile users see a simplified menu with only links to the top-level items.

Note: Tablet users currently see the dropdown arrows even though they cannot expand them since they are hover-only.
