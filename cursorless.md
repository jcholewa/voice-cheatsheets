- General
    - show cursorless sidebar - cursorless bar
    - open the documentation in chrome - cursorless help

- Commenting
    - comment a line - comment down/up \[line number\]

- Selecting and deselecting
    - select a function - take funk \[gust\]
    - select the block you're in - take block
    - select line containing specified token - take line \[red gust\]
    - select from the cursor to the start/end of the line - take head/tail
    - selects from the mark to the start or end of the line - take head \[air\]/take tail \[air\]
    - expand from the mark back forwards or backwards to include all adjacent non whitespace characters - take paint \[red gust\]
    - deselect the given target - give

- Copying and cloning
    - copy from the second word to the end of the line - copy tail line second token
    - copy a line - copy up/down \[line number\] or clone \[line number\]
    - clone target before the target - clone up \[target\] e.g. clone up funk inserts a copy of the current function
    - clone target after the target - clone \[target\]

- Deleting
    - delete the contents of the current line without removing the line ending - chuck just line
    - delete line entirely with no blank line remaining - chuck line
    - delete a character - \[nth\] char \[token\] - e.g. chuck second char air
    - remove leading and trailing space - chuck leading odd and trailing odd
    - change a target (i.e. delete the target and leave the cursor where it used to be) - change \[blue air\]
    - clear the end of a function name starting from x word - clear last \[two\] words \[funk name\]

- Moving around
    - place the cursor before the given target - pre
    - place the cursor after the given target - post
    - place the cursor before a class/function etc - pre class / pre next funk
    - go to a specific line - go \[line number\]
    - move the cursor after the closest pair - post pair
    - go to the function being called - follow \[func name\]

- Swapping
    - swap two targets - swap \[blue air\] with \[green bat\]

- Inserting
    - insert a function snippet - snippet funk \[.hello world\]
    - add a new line above the line with the token - drink \[red gust\]
    - add a new line underneath the line with the token - pour \[red gust\]

- Editing
    - rename the end of a function name starting from x word - rename last \[two\] words \[funk name\]

- Formatting
    - apply formatting to a token - form \[title\] at \[air\]
    - formatting terminator - \[snake\] this is a test over \[dot\] ts
    - delete a sentence and rewrite it with the formatter you specify - nope that was \[formatter\]
    - make a token lowercase - format all down at \[token\]
