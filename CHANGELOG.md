# Change Log  
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/).

## [2020-02-09] - 2020-02-09
### Changed
- Renamed app HighlightJump to signal both highlight and jump features
- Big code rework
- Fixed compatibility with new SumatraPDF "A" annotation key
- Changed mouse shortcuts (see Readme)
- Changed shortcut: A = yellow, or hold to cycle color
- Changed shortcut: D ("dot") = blue rectangular dot
- Changed shortcut: E ("erase") = remove all highlighting under mouse
- Changed shortcut: Control + Delete = remove all highlighting on page
- Changed shortcut: R = red (Overrides SumatraPDF "reload". Replacement: Ctrl+R)
- Changed shortcut: G = green (Overrides SumatraPDF "go to". Use Ctrl+G instead)
- Changed jump shortcuts to be shorter (see Readme)
- Use SendMessage to make SumatraPDF save annotations, refresh, and goto page
- Fixed blue rectangle annotation position in .epub
- Fixed blue rectangle annotation works even if no .smx exists yet

### Added
- Quick jump: temporarily store and jump to pagenumber. Shortcuts 1 2 3 4 5. Cleared on app close.
- Show tray icon also when running .ahk uncompiled
- option: experimental SendMessage methods to silently get filepath and canvas position (requires SumatraPDF C++ edits)
- .ini file

## [2017-05-23] - 2017-05-23
### Added
- First GitHub release (then named sumatra_highlight_helper)