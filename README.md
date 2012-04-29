cooved
======

ooc IDE written in ooc
Dependencies:
- [rock](http://github.com/nddrylliog/rock)
- [ooc-gtk](http://github.com/nddrylliog/ooc-gtk)

Here are some ideas on which I will start working:

MUST SUPPORT
------------

- Support for ooc packaging through reincarnate GUI
- Automatic completion (source parsed, not realtime, after the user finishes his editing, only edited region should be parsed) triggered through a special key combination
- Project files saving information about rock options used to compile (with a nice GUI explaining them and editing them), project files, etc.
- Configuration saves OOC_LIBS environmental variable etc.
- Custom themes/colors
- Optional embedded command line and hotkeys to switch between editing and writing commands to the command line
- The command line should also be able to be filtered to show only stdout/stderr/other... and unmangle ooc symbols from exception stack traces
- Integrated search/replace; no popup window (popups are annoying)
- Of course hotkeys to build or build/run
- Jump to class/function/method/operator definition in specific files or even the whole project
- Multiple tabs (duh) and easy way to switch between them (Ctrl+Tab ?) as well as to open new ones and close them
- Basic text editing capabilities/shortcuts
- Expand/collapse class/function/operator declarations
- Optional bracket/parenthesis/[(char1 -> char2) <- configurable] completion
- Keep track of TODOs/FIXMEs
- Make a project easily by scanning a folder
- Scan project files to find libraries use-d and then check for their existance on libpath and reincarnate repo, notify user to download them from there if they exist

SOULD SUPPORT
-------------

- Git(hub) easy repository management / versioning support
- Plugins (? using the modular oc model)
- Custom hotkey layouts
- Browse open-source projects hosted on github
- Debugging with gdb (gdb-ooc ?) through a simple UI
