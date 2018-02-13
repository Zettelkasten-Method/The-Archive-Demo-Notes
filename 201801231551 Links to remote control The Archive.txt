# 201801231551 Links to remote control The Archive
#automation

First, remember that we suggest to stick to the plain text approach and use IDs to reference your Zettel notes from external sources, like digital Mind-Maps or spreadsheets. Sticking to IDs instead of application-specific features prevents you from suffering from app lock-in effects. See [[201705120915 Software-agnostic programming]].

That being said, if you want to write scripts that remote control *The Archive*, or if you want to insert clickable links in other applications to open a note in this app, you can use the built-in URL scheme for these purposes:

- `thearchive://search/SEARCH_TERM` will filter your list of notes just like a manual search for "SEARCH_TERM" would; it behaves like clicking on `#hashtags`.
- `thearchive://match/TERM` will filter your list of notes *and* open a note that starts with "TERM", if any; it behaves like clicking on `[[WikiLinks]]`.
- `thearchive://matchOrCreate/TERM` will behave like `match` but creates a note called "TERM" if no match was found; it behaves like searching for "TERM" and then hitting return to create a new note.
