ImpressNotes
============

A Simple Javascript extension to [ImpressJS](https://github.com/bartaz/impress.js "ImpressJs") by [Bartek Szopka](https://github.com/bartaz "Bartek Szopka") that allows you to include notes with 
your presentation.

This was originally developed by [David Souther](https://github.com/DavidSouther "David Souther"), and was modified by myself to be a bit
less intrusive to the library, which follows a more Aspect Oriented approach.

To use this, just include the impress-notes.js tag after your require of the impress.js tag and then at any point in your
presentation, if you hit the "n" key on your keyboard, this will provide you with a popup window
that will have the notes in it.  To use your notes, just store the html in a hidden "notes" div (contained 
within each step of the presentation).

For an example of how this works, please feel free to use the code found in my [gitDemo project](https://github.com/jlgrock/gitDemo "Git Demo").
