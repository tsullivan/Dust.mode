Dust.mode
=========

A [Coda](http://panic.com/coda) syntax mode for [Dustjs](http://linkedin.github.io/dustjs/)
copied from the Smarty mode built into Coda and modified by [Tim Sullivan](http://github.com/tsullivan).



Installation
------------

Drop `Dust.mode` into `~Library/Application Support/Coda 2/Modes` (or `.../Coda/Modes`
if you're not using Coda 2). If that folder doesn't exist, create it.

 

Usage
-----

 1. Install.

 2. Open a file with a `.dust` extension in Coda or SubEthaEdit.
 
 3. To turn on highlighting manually in Coda go to `Text -> Syntax Mode -> Dust`.
 
 4. To make all dust files use this syntax by default in Coda, go to `Coda -> Preferences -> Custom Syntax Modes` and add an entry with values `Extension`: `dust` and `Syntax Mode`: `Dust`



Known Issues
------------

- Dust tokens containing quotes aren't highlighting correctly
- Autocomplete for Dust syntax isn't really implemented
