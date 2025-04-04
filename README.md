# Windows Terminal in Context Menu

A collection of windows registry files that better integrate windows terminal into the explorer context menus.

It's a good idea to back up your registry before applying any of these (including the uninstallers), in case they are out of date or incorrect for your system.

## add-wsl-wt-to-context-menu.reg

A windows registry file that opens WSL through windows terminal in context menus, and cds to the target directory.

`remove-wsl-wt.reg` removes the context menu items.

## add-git-bash-wt-to-context-menu.reg

A windows registry file that changes the git bash context menu item to open in the target directory through wt.

`remove-git-bash-wt.reg` restores default git bash behaviour.