# Changelog

## 0.8.10
* Restyle of the interface by [Fez Vrasta](https://github.com/FezVrasta)

## 0.8.9
* Do not display 'not a git repo' anymore [#111](https://github.com/zaggino/brackets-git/issues/111)
* Removed obsolete status bar [#110](https://github.com/zaggino/brackets-git/issues/110)

## 0.8.8
* Add toggle panel keyboard shortcut in settings dialog.
* Add amend checkbox to the commit dialog.

## 0.8.7
* Added Brazilian Portuguese translation by [Rodrigo Tavares](https://github.com/rodrigost23)
* Fixed dialog size bug.

## 0.8.6
* Push now asks for origin url when no origin is defined.

## 0.8.5
* Basic branches switching implemented.

## 0.8.4
* Adds an option to disable adding newline at the end of the file.
* Updated Simplified Chinese translation by [Zhi](https://github.com/yfwz100)
* Updated German translation by [Marcel Gerber](https://github.com/SAPlayer)

## 0.8.3
* Git gutters are now clickable.

## 0.8.2
* Basic Git gutter support - you can turn on/off this feature in settings.

## 0.8.1
* Fixes for new Brackets' CodeInspection API (requires Sprint 36).

## 0.8.0
* You can now add files and directory entries to .gitignore file by right clicking.

## 0.7.12
* Minor fix in produced error messages for github bug reports.

## 0.7.11
* Fixes bug when commiting files moved with git mv command.

## 0.7.10
* Fixes of previous release.

## 0.7.9
* Test if project folder is writable before doing Git Init.
* Extended commit now works without extra line breaks.

## 0.7.8
* Do not display files in panel that are hidden by Brackets by default.

## 0.7.7
* Added Simplified Chinese translation by [Zhi](https://github.com/yfwz100)

## 0.7.6
* Fixes buggy releases 0.7.5 & 0.7.4

## 0.7.5
* Button to hide untracked files from panel.

## 0.7.4
* Experimental support for multi-line commit messages.

## 0.7.3
* Git Init now experimentally works in projects that are not a git repository.

## 0.7.2
* Updated German translation by [Marcel Gerber](https://github.com/SAPlayer)

## 0.7.1
* Added bug reporting button to the git panel which prefills some Brackets info.

## 0.7.0
* Improvements towards error handling and reporting.

## 0.6.19
* Fixed issue with corrupting image files [#31](https://github.com/zaggino/brackets-git/issues/31)
* Fixed issue with delete button not working.

## 0.6.18
* Added Git panel to the menu (View > Git) with keyboard shortcut Ctrl+Alt+G.

## 0.6.17
* Changes to move on from deprecated APIs to new ones - requires Brackets 34.

## 0.6.16
* Add box to show commit message length.

## 0.6.15
* Fix the cygwin path conversion using a more reliable method by [Zhi](https://github.com/yfwz100)

## 0.6.14
* Added pull button with fast-forward only mode. (No functionality to resolve merge conflicts)

## 0.6.13
* Some improvements in error handling and logging.
* Fixed a bug when file contained spaces [#21](https://github.com/zaggino/brackets-git/issues/21)

## 0.6.12
* Fix [Extension failed to load](https://github.com/zaggino/brackets-git/issues/19)

## 0.6.11
* Fix a bug when deleting uncommited files from Git panel.

## 0.6.10
* Fix a bug when commit/diff dialogs fail to display when first line of file is modified.
* Fix a bug in diff formatting.

## 0.6.9
* German translation by [Marcel Gerber](https://github.com/SAPlayer)

## 0.6.8
* Fix bug where extension breaks on Linux by [Fabio Massaioli](https://github.com/fbbdev)

## 0.6.7
* Add support for cygwin git by [Zhi](https://github.com/yfwz100)

## 0.6.6
* Removed polyfills for older Brackets, sprint 32 required from now.

## 0.6.5
* Push button will now show if there are any unpushed commits.

## 0.6.4
* Enabled experimental push button. Pushes only to default remote.

## 0.6.3
* Added button to remove unmodified files from working tree.

## 0.6.2
* Fix diff output to use --no-color do avoid having color codes in output on some machines.

## 0.6.1
* Fix bug where whitespace cleanup function corrupts binary files.
* Code checking features delayed for Sprint 32 ([adobe/brackets#5125](https://github.com/adobe/brackets/pull/5125))

## 0.6.0
* Using new CodeInspection API from Brackets to check files for errors before commiting. (Sprint >= 31)
* Current document is now selected in the git panel for easier navigation.
* Added feature (see Git Settings) to cleanup whitespace when commiting.
* Added hover titles to the Git icon when there's a problem.

## 0.5.3
* Fixed issue [#5](https://github.com/zaggino/brackets-git/issues/5)
* Added focus to input when commit dialog is shown.

## 0.5.2
* Added delete button for untracked files
* Untracked files are now shown (instead of untracked directory)

## 0.5.1
* Undo changes now works and is no longer disabled.

## 0.5.0
* Added new diff button to show next to the every modified file.
* Little bit of UX tuning.

## 0.4.6
* Panel now properly disables when switching between projects with and without git repository.

## 0.4.5
* Click in the git panel now opens the file, doubleclick adds file to the working tree.

## 0.4.4
* Great new icon and UI tweaks by [Larz](https://github.com/larz0)
* Commit dialog should be now a bit bigger depending on the screen size.

## 0.4.3
* Settings dialog has now a restore defaults button which restores platform specific defaults (Win, Mac).
* Settings dialog has now a button to show changelog.
* Minor UI tweaks.

## 0.4.2
* Default preferences are different for platforms.

## 0.4.1
* Changelog is not shown on the first startup, when settings are shown.

## 0.4.0
* Added settings panel to File > Git Settings...
* Git Settings dialog will open on first startup after the extension is installed.
* Changelog will open in dialog after the extension is updated.

## 0.3.0
* Added diff displaying to commit dialog.

## 0.2.1
* Added i18n support.
* Fixed styling in commit dialog.

## 0.2.0
* Added shortcut to bash console for msysgit users.
* Added configuration file that is created on the first extension run (thx for idea to [Rajani Karuturi](https://github.com/karuturi))

## 0.1.0
* First real functionality, basic commit from brackets is now available.

## 0.0.3
* Added handlers to refresh branch name on project change or file tree refresh.

## 0.0.2
* Display current branch name in file tree if working folder is a git repository.

## 0.0.1
* Initial release.
* Display current Git version in status bar.
