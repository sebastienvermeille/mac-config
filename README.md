# mac-config
files to keep synchronized between my two macs

The goal of this project is to share in a clever way settings and conveniences between multiple macOS machines.

## Setup

Add the following in your cron:

crontab -e
````bash
TODO
```

## Doc
### Scheduled tasks (cron)

In order to avoid the write of a lot in crontab, all the scheduled tasks are placed into `tasks/<freq dir>`.
By example if you place the task cleanDownloadsDirectory.sh in `tasks/every-2-hours/` then it will be called every two hoursl

List of scheduled tasks:
* autoclean-downloads-dir.sh -- delete files aged with more than 7 days in the Downloads directory

## Todolist

* sync-bashrc.sh -- synchronize .bashrc
* sync-tmuxinator-projects.sh -- synchronize tmux saved projects
* automove-desktop-stuff-to-dirty-directory.sh -- all desktop files age with more than 7 days (not shortcut) will be placed in a directory "Desktop/dirty".

TODO


