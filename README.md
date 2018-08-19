# chrome-bookmark-to-mht
i just write a small script to save my bookmark in case the url out-of-date, the mht save module is chilkat

## tips
because of the special symbol is cannot parse by XML, you should replace the *&* by *&amp\;*, and drop the head like this:
```angular2html
<!DOCTYPE NETSCAPE-Bookmark-file-1>
<!-- This is an automatically generated file.
     It will be read and overwritten.
     DO NOT EDIT! -->
<META HTTP-EQUIV="Content-Type" CONTENT="text/html; charset=UTF-8">
<TITLE>Bookmarks</TITLE>
<H1>Bookmarks</H1>
```
that is all, tks