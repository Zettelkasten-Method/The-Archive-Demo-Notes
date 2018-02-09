# 201801232029 Note identifiers and The Archive
#id #archiveapp-demo

To create links between notes, you need to define how to *target* a note first. On the web, it is simple: each website has its own unique address that you can copy from the address bar of your web browser.

When you work with plain text files [[201705120913]], it might sound obvious to use the file names. And if you want to have clickable links, you might use the full path to a note, like `file:///Users/JaneDoe/Archive/some-note.txt`. But that's fragile, since the links break when you rename the note or move your archive to a different path.

This is how we do it: every Zettel note gets its own unique ID. We choose the timestamp-like IDs like `201402260939` which would be based on the date and time "2014-02-26 9:39a.m." Moments in time a unique and offer a guaranteed uniqueness. The ID is fixed, the title may change over time.

When you reference a note from someplace else, you paste the ID there. You will soon learn to recognize such sequences of digits as IDs because of the way they look. Then you know, "there's a Zettel with this ID, I should check it out!"

*The Archive* tries to be helpful and offers these nifty [[201705091535 Direct Links as Wiki-Links]]. Adhering to the double-square-bracket convention of wikis, you get clickable links using Zettel IDs without buying into any proprietary file format or fragile file paths.

Further reading on our blog: https://zettelkasten.de/posts/add-identity/
