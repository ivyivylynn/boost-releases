# Boost releases

## Download link

[Latest](https://github.com/BoostIO/boost-releases/releases/latest)

## Changelog

## 0.8.15 (2017/9/23)

# Features
- Add file drop on NoteList https://github.com/BoostIO/Boostnote/pull/793
- Support for extended table markdown syntax https://github.com/BoostIO/Boostnote/pull/811
- Add markdown-it-named-headers and adjust to use Japanese or Chinese https://github.com/BoostIO/Boostnote/pull/812
- Add wordcount and lettercount to InfoPanel https://github.com/BoostIO/Boostnote/pull/815
- Make pasting an image in CodeEditor work https://github.com/BoostIO/Boostnote/pull/818
- Add RealtimeNotification https://github.com/BoostIO/Boostnote/pull/877
- iss #832 Make :q work in vim mode https://github.com/BoostIO/Boostnote/pull/885
- Add link for cloud integration https://github.com/BoostIO/Boostnote/pull/889

# Bug Fix
- Fix note creation in All Notes https://github.com/BoostIO/Boostnote/pull/803
- Fix typo regarding fullscreen https://github.com/BoostIO/Boostnote/pull/805
- Fix app name and icon on linux https://github.com/BoostIO/Boostnote/pull/806
- iss #809 normalize text works only in img tag https://github.com/BoostIO/Boostnote/pull/816
- Fix image insesration problem https://github.com/BoostIO/Boostnote/pull/820

# Dev
- Componentnize NewNoteButton https://github.com/BoostIO/Boostnote/pull/800
- Add eslint plugin react https://github.com/BoostIO/Boostnote/pull/801
- Fix by eslint react https://github.com/BoostIO/Boostnote/pull/802
- Add to specify npm version https://github.com/BoostIO/Boostnote/pull/813

## 0.8.14 (2017/8/12)

# Features
- none

# Bug Fix
- Fix configmanager #787
- Make RcParser ignore errors at JSON.parse() #789

## 0.8.13 (2017/8/10)

## Features
- Fix layout #736
- Change to work ctrl-e and ctrl-w in RIGHTCLICK #753 
- Add Print #754 
- iss #758 Add InfoButton and InfoPanel in Trash #765 
- Context search #766 
- Add boostnoterc revival #783 

## Bug Fix
- Change order for AMA event #749 
- Fix noteCount on a note trashed #764 
- Fixes typo in welcome screen #767 
- Fixed InfoPanel layout in Trash #768 
- Finder UI Fix (My Storage positioning) #777 
- Add Lato font-face definition to main.html #779 
- Add storageKey to MarkdownEditor #780 
- Update application wording #782 

## 0.8.12 (2017/7/29)

## Features
- Add trash can https://github.com/BoostIO/Boostnote/pull/297
- Randomize the image name when it's dropped https://github.com/BoostIO/Boostnote/pull/667
- Componentnize TrashButton https://github.com/BoostIO/Boostnote/pull/672
- Edit initial files https://github.com/BoostIO/Boostnote/pull/681
- Change “Menu” to “Preferences”, and icon.https://github.com/BoostIO/Boostnote/pull/684
- Add search-box https://github.com/BoostIO/Boostnote/pull/686
- Remove the context menu for deletion https://github.com/BoostIO/Boostnote/pull/688
- Fix layout https://github.com/BoostIO/Boostnote/pull/690
- Add info button https://github.com/BoostIO/Boostnote/pull/692
- Feature links among notes https://github.com/BoostIO/Boostnote/pull/693
- Replace cm searchbox to official search addon https://github.com/BoostIO/Boostnote/pull/696
- Update layout https://github.com/BoostIO/Boostnote/pull/698
- Change the keymap of Ctrl-U to Ctrl-K https://github.com/BoostIO/Boostnote/pull/706
- Remove a dialogbox from onTrashButtonClick https://github.com/BoostIO/Boostnote/pull/707
- Change noteHash to noteLink in the input in InfoPanel https://github.com/BoostIO/Boostnote/pull/708
- Add exports to infoPanel https://github.com/BoostIO/Boostnote/pull/709
- Change to create a new directory when storage/images does not exist https://github.com/BoostIO/Boostnote/pull/710
- Add checkbox for ama https://github.com/BoostIO/Boostnote/pull/715
- Change ["title"](note-hash) to [the exact title](note-hash) https://github.com/BoostIO/Boostnote/pull/716 
- Fix typos Dynamit to Dynamic https://github.com/BoostIO/Boostnote/pull/718
- Update readme https://github.com/BoostIO/Boostnote/pull/721
- Fix layout https://github.com/BoostIO/Boostnote/pull/722
- Fix typo in InfoTab https://github.com/BoostIO/Boostnote/pull/723
- Make image path relative https://github.com/BoostIO/Boostnote/pull/730
- Fix layout https://github.com/BoostIO/Boostnote/pull/736

## Bug Fix
- Fix an error on click event https://github.com/BoostIO/Boostnote/pull/695
- Fix a bug on click https://github.com/BoostIO/Boostnote/pull/717
- Fix inseration position https://github.com/BoostIO/Boostnote/pull/719
- Goodbye Ctrl-G https://github.com/BoostIO/Boostnote/pull/720
- Fix hidden button https://github.com/BoostIO/Boostnote/pull/724
- iss #155 Change defaut font on windows https://github.com/BoostIO/Boostnote/pull/726
- iss #727 fix incorrect encoding in link https://github.com/BoostIO/Boostnote/pull/728
- Make it work on windows https://github.com/BoostIO/Boostnote/pull/732

## 0.8.11 (2017/6/24)

## Features
- Add importer which imports files from .md/.txt https://github.com/BoostIO/Boostnote/pull/325
- Make Ctrl-C copy https://github.com/BoostIO/Boostnote/pull/649

## Bug Fix
- Rename `TodolistPercentage.js` to `TodoListPercentage.js`. https://github.com/BoostIO/Boostnote/pull/645
- Fix not to show scroll bar when full screen mode in Windows https://github.com/BoostIO/Boostnote/pull/658

## 0.8.10 (2017/6/13)

## Features
- Move note between folders https://github.com/BoostIO/Boostnote/pull/374
- display percentage of achievement of todo in markdown https://github.com/BoostIO/Boostnote/pull/557
- If there is no tag, narrow the width of NoteList. https://github.com/BoostIO/Boostnote/pull/594
- #595 - Resize an image with markdown https://github.com/BoostIO/Boostnote/pull/598
- change search ux https://github.com/BoostIO/Boostnote/pull/600
- Copy clipboard button for markdown code blocks https://github.com/BoostIO/Boostnote/pull/603
- I improved the dark theme. https://github.com/BoostIO/Boostnote/pull/605
- Feature amazon mobile analytics https://github.com/BoostIO/Boostnote/pull/620
- Add emacs keymap https://github.com/BoostIO/Boostnote/pull/623
- improve searchTextBox UX https://github.com/BoostIO/Boostnote/pull/628
- Handling pull 602 https://github.com/BoostIO/Boostnote/pull/632

## Bug Fix
- Fix incorrect tag completion in code block https://github.com/BoostIO/Boostnote/pull/341
- fix the bug when using markdown syntax h1 https://github.com/BoostIO/Boostnote/pull/510
- Revamp handling of multiple key press https://github.com/BoostIO/Boostnote/pull/545
- Fix for #535: https://github.com/BoostIO/Boostnote/pull/549
- Fix task bar UI https://github.com/BoostIO/Boostnote/pull/587
- Fix copy button layout https://github.com/BoostIO/Boostnote/pull/622
- Fix a bug which is not showing dialog when user tries to export a snippet https://github.com/BoostIO/Boostnote/pull/626
- Fix a rendering bug https://github.com/BoostIO/Boostnote/pull/633

## 0.8.9 (2017/4/29)

## Features

- Improve wordings. https://github.com/BoostIO/Boostnote/pull/480/files
- Added `Shift` on Hints. https://github.com/BoostIO/Boostnote/pull/488
- Fix md viewer line breaks when copying. https://github.com/BoostIO/Boostnote/pull/512
- Add star display on note list. https://github.com/BoostIO/Boostnote/pull/522
- Change design of sidebar. https://github.com/BoostIO/Boostnote/pull/520

## Bug Fix

- Fix package name. https://github.com/BoostIO/Boostnote/pull/477
- Fix a shortcut for deletion. https://github.com/BoostIO/Boostnote/pull/484
- [windows]Scrollbar no longer appears above modal. https://github.com/BoostIO/Boostnote/pull/513

## 0.8.8 (2017/4/22)

## Features

- Design update https://github.com/BoostIO/Boostnote/pull/424
- Improve trash button https://github.com/BoostIO/Boostnote/pull/340
- Remove `ctrl+B` shortcut key https://github.com/BoostIO/Boostnote/pull/399
- Write mark automatically when writing list on Markdown https://github.com/BoostIO/Boostnote/pull/425
- Double click on tab to rename on snippet note https://github.com/BoostIO/Boostnote/pull/453
- Fix behavior of the shortcut key to make text bold on Markdown https://github.com/BoostIO/Boostnote/pull/469
- Add syntax highlight theme preview https://github.com/BoostIO/Boostnote/pull/290
- Remove esc button on initial modal window https://github.com/BoostIO/Boostnote/pull/474
- [macOS]Fix text on menu bar https://github.com/BoostIO/Boostnote/pull/468

## Bug Fix

- Fixed Snippet tabs overwriting other tabs when closed https://github.com/BoostIO/Boostnote/pull/352
- The problem with closing app when fullscreen mode https://github.com/BoostIO/Boostnote/pull/349

## Development

- Fix config of ESLint https://github.com/BoostIO/Boostnote/pull/317
- Add npm script `dev-start` https://github.com/BoostIO/Boostnote/pull/357
- Start using yarn 🐱  https://github.com/BoostIO/Boostnote/pull/393

## 0.8.7 (2017/3/20)

- Changed the tray icon when mouse on.
- The lock icon on markdown note.
- Covert dragged svg into link literal of markdown.
- Ignore `#` in the code block
- Fix the bug for deleting snippet tab.

## 0.8.6 (2017/3/4)
- Image drag fix.
- Fix font color for dark theme rename folder modal.

## 0.8.5 (2017/2/11)
- Fix markdown preview.
- Fix the bug which cannot open finder with using HotKey on Windows.
- Fix App icon on Windows 10 taskbar.

## 0.8.4 (2017/1/28)

- Change shortcut key to blur MarkdownNote.
- Fix design.
- Markdown can't edit under specific state.

## 0.8.3 (2017/1/21)

- Some new shortcuts.
- Exporting markdown note as txt/md.
- More zoom options (140-200%).
- Dropping images into CodeEditor.
- Bug occurs with updating.
- Fixes syntax hilight of inline code on Preview.
- Some markup.

## 0.8.2 (2017/1/15)

- Fix the bug which cannot open finder with using HotKey on macOS.

## 0.8.1 (2017/1/14)

- Renew the URL of official page.
- Add selector of the folder on note detail.
- Remember window size when quit Boostnote.
- Vim keymaps.
- Remove dependencies of `oh-my-cdn`.
- Update information of development.
- Settings for TravisCI and ESLint.
- Fix code theme not found error.
- Design: number of the folder.

## 0.8.0 (2017/1/3)

- Renew the design.
- Remove butto to share the note.
- Remove controll context button on top bar.
- Renew the logo.
- Remove folder selecting on note detail.

## 0.7.4 (2016/12/13)

- Fix error on modal window.

## 0.7.3 (2016/12/13)

- Remove menu bar on windows.
- Improved error messaging.
- Fix syntax error when compiling/running Boostnote.
- Minor accelerator updates for macOS.
- Adding menu back in temporarily to fix shortcuts.

## 0.7.2 (2016/10/18)

- Fix editor bug when using Japanese IME Keyboard.

## 0.7.1 (2016/10/18)

- Fix minor design bugs.

## 0.7.0 (2016/10/17)

- Replace Ace editor with Codemirror
- Improve UI
- Fix minor bugs fix
  - Crush on deleting empty folder
  - Finder shows wrong detail when search keyword is empty.

## 0.6.8 (2016/9/22)

- Fix data parsing error (\u2028)

## 0.6.7 (2016/9/21)

- Fix dataApi bugs
  - Line separator(\u2028) characters doesn't be escaped when stringifying.
  - The app tries to parse `.DS_Store` as a note.
- Fix segfaults error when closing app on Ubuntu

## 0.6.6 (2016/9/20)

- Attempt to recover broken storages
- Fix renaming storage name bug

## 0.6.5 (2016/9/10)

- Infinite scroll
- Confirm on blur when editing color and name of folder.
- Default note option(Snippet/Markdown/Always ask)
- Context menu for notes(`Delete Note`)
- Show dialog when deleting snippet #107
- Improvement folder select #106
- Resizable SideNav
- Strip markdown syntax from title
- Using Immutable
- Refactor for dataApi

## 0.6.4 (2016/8/23)

- App doesn't quit properly on Windows and Linux (with Cinnamon)
- Syntax mode will be automatically detected and set by filename.

## 0.6.3 (2016/8/14)

- Fix error when closing main window on Ubuntu #57
- Finder
- Dark theme (UI customization will be embeded the next update)
- Folder color picker by @dotcs #77
- Fix layout bug #69
- expand/folder sidebar
- Markdown snippet in Snippet note can be rendered just like Markdown note

## 0.6.2 (2016/7/28)

- Improve performance: debounce dispatch
- Footnote
- GFM style checkbox
- Add tooltips to buttons

## 0.6.1 (2016/7/23)

- Hotfix: fix endless loading when user is a newcomer.

## 0.6.0 (2016/7/23)

- Renew app,
- Several features are temporary disabled.(within a week)
  - Finder
  - Dark theme
  - Post exporting

## 0.5.13 (2016/6/12)

- Scroll bar will be hidden when modal opens

## 0.5.12 (2016/5/13)

- Line number for code block in Markdown note

## 0.5.11 (2016/4/25)

- Enable Finder on Cinnamon.
- Add missing features of Dark theme.

## 0.5.10 (2016/4/25)

- Dark theme.
- Editor themes & Preview codeblock themes.

## 0.5.9 (2016/4/11)

- App will quit when main-window closed.
- 'There is no newer version' alert won't show anymore.

## 0.5.8 (2016/4/3)

- Fix editor selection bug
- Fix file drop bug

## 0.5.7 (2016/3/28)

- modify contact links

## 0.5.6 (2016/3/28)

- add announcement about OSS
- replace contact form with contact link

### 0.5.5 (2016/3/16)

- Focus search input when main-window called by hotkey
- Bump up Electron to v0.36.11
- Editor font family also applied title input
- Zoom factor can be configurable by Ctrl+WheelScroll(Windows, Linux only)
- Fix emacs key binding of Ace editor(Ctrl-a, Ctrl-p)
- Long line of tags in Post list will be wrapped

### 0.5.4 (2016/1/25)

- HTML code in code fence won't be sanitized.
- The bug of Ace editor, command ctrl+e on Editor(go to line end),  is fixed.
- Markdown style is improved.
- Anchor with image works well now.

### 0.5.3 (2016/1/19)

- Fixed. Switching preview with ESC key when set switch preview on right click doesn't work well.
- Fixed. Switching preview/editor which doesn't work well after updating v0.5.2.
- Strange behavior of Preferences when setting shortcuts is fixed.

### 0.5.2 (2016/1/18)

- Unintended behavior of switching Preview/Editor when right clicking is fixed
- Opening search form in editor(OSX: ⌘ + F, Win: Ctrl + F) won't fire switching preview.
- 'Right click to toggle Preview/Editor' option will be added.
- Strikethrough syntax `~~` won't be sanitized.
- Checkbox syntax `[ ]`, `[x]` will be added.
- Default key of global shortcut open-main-window will be changed.(OSX: ⌘ + alt + L Wins: Windows + Alt + E)
- \& in Latex block won't be sanitized to &amp;
- Windows Only : Base font-family will be changed(helvetica, arial, sans-serif -> meiryo, 'Microsoft Yahei', helvetica, arial, sans-serif)

### 0.5.1 (2016/1/11)

- Enhanced UI/UX (No more Edit / Save button)
- CommonMark support(HTML available)
- Latex block(`$$`, `$$$`)
- Configurable Font/Indent style
- Insensitive-case Search

### 0.5.0 (2015/12/13)

- Windows app has been released!
- Boostnote has been codesigned properly. (both Windows and Mac app)
- IPC between main window and finder window has been improved.

---

### 0.4.7 (2015/12/13)

We relaunch our app. Boost, therefore, became **OBSOLETE**.
Please re-install from [here](http://b00st.io)! Your data automatically moved to our new app.

### 0.4.6 (2015/12/14)

- Sharing a post via public URL(valid for 7 days) is available
- Hotkey added: Ctrl+p for move cursor up in CodeEditor.
- Debug: Dragging in Finder window is available.
- Debug: Search value of Finder window will be reset automatically.
- Debug: Changing order of the folders will be saved correctly.

### 0.4.5 (2015/12/8)

- Markdown preview will be automatically scrolled to the position of cursor.
- Style of markdown is improved.

### 0.4.4 (2015/12/4)

- The value of search input will be escaped.
- User name(Top-left) is editible now. check the preferences.

> User name is not significant yet.
> It will be needed when git repository based sharing is available.

### 0.4.3 (2015/12/1)

- Discuss Link added.
- When creating a new post without title, creation time will be set to its title.
- new short-cut key, Cmd + p, is available to toggle markdown preview/edit mode.
- new short-cut key, Cmd + n, is available to create a new post.
- 'visible on all workspace' option is unset.
- some trivial problems is fixed.

### 0.4.2 (2015/11/25)

- Finder behaviour fixed.
- Syntax hightlight in code block of markdown is available.
- Emoji is also available.
- Clicking cancel button when editing also causes show alert if there is a unsaved feature.

### 0.4.1-beta.3 (2015/11/22)

- Fix some bugs when creating an post
- Edit default article content
- Fix notification(Node-notifier -> WebNotification)

### 0.4.1-beta.2 (2015/11/21)

We decided to hide our codes.
Actually there is a plan to make our app public, but not now.

- The code in this app has been uglified and pack with Asar.
- Disable to toggle devtools

### 0.4.1-beta.1 (2015/11/18)

- Fixed Unsaved alert modal which appears wrong time.

### 0.4.1-beta (2015/11/16)

- App will check a new update automatically(former: Only checked once when app is just started)
- Editing the order and the color of folders is available.
- When an article is on editing, switching article will be blocked with alert modal.
- Notification icons are fixed properly.
- keydown handling of some input is improved.
(Enter to submit: CreateNewFolder, Preferences/ManageFolder)
- Tag suggest is available when editing tags
