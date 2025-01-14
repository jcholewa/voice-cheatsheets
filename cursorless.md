- Useful links
    - Paired delimiters https://github.com/cursorless-dev/cursorless/tree/main/packages/cursorless-org-docs/src/docs/user/#paired-delimiters40

- General
    - show cursorless sidebar - cursorless bar
    - open the documentation in chrome - cursorless help
    - collapse/un collapse a block - fold/unfold \[target\]
    - visualise all of a scope - visualise [funk]
    - hide the visualisation - visualise nothing
    
- Searching
    - search the document for a target - scout [target]
    - search the workspace for a target - scout all [target]
    - search the workspace for the highlighted target - scout all this

- Commenting
    - comment a line - comment down/up \[line number\]
    - comment multiple lines - comment two lines [target] and [target]
    - comment multiple selected lines - comment this
    - of two lines, reverse which one is commented out - comment line [target] and [target]

- Selecting and deselecting
    - select a function - take funk \[gust\]
    - select the block you're in - take block
    - select the block you're in, stopping at the boundary of a surrounding pair - take short block
    - select line containing specified token - take line \[red gust\]
    - select from the cursor to the start/end of the line - take head/tail
    - selects from the mark to the start or end of the line - take head \[air\]/take tail \[air\]
    - expand from the mark forwards or backwards to include all adjacent non whitespace characters - take paint \[red gust\]
    - deselect the given target - give
    - select every instance of target - take every instance \[target\] e.g. take every instance dash
    - select multiple targets at once - take \[target\] and \[target\]
    - select a range (if the first target is omitted then the start will be the current selection) - take [target] past [target], take past [target], take past end of line, take past start of line, take funk [target] past [target], take past before [target]
    - select a target and its surrounding paired delimiters - take [box] [target]

- Copying and cloning
    - copy from the second word to the end of the line - copy tail line second token
    - copy a line - copy up/down \[line number\] or clone \[line number\]
    - clone target before the target - clone up \[target\] e.g. clone up funk inserts a copy of the current function
    - clone target after the target - clone \[target\]
    - clone a statement - clone state \[target\]
    - copy an item or scope to cursor position - bring [state] [target]
    - copy a target to another target position - bring [target] to [value] [red]

- Deleting
    Lines
    - delete the contents of the current line without removing the line ending - chuck just line
    - delete line entirely with no blank line remaining - chuck line
    - delete the previous line - chuck previous line
    - delete the next line - chuck next line
    - delete the leading line - chuck leading line
    - delete the trailing line - chuck trailing line
    - delete a particular row - chuck row [number]
    Other
    - delete sentence - chuck sentence
    - delete a character - \[nth\] char \[token\] - e.g. chuck second char air
    - remove leading and trailing space - chuck leading odd and trailing odd
    - change a target (i.e. delete the target and leave the cursor where it used to be) - change \[blue air\]
    - clear the end of a function name starting from x word - clear last \[two\] words \[funk name\]
    - remove paired delimiters from a target - chuck bounds \[token\]

- Moving around
    - place the cursor before the given target - pre
    - place the cursor after the given target - post
    - place the cursor before a class/function etc - pre class / pre next funk
    - go to a specific line - go \[line number\]
    - move the cursor after the closest pair - post pair
    - go to the function being called - follow \[func name\]
    - go to the start of a sentence - pre sentence

- Scrolling
    - scroll the target to the top/centre/bottom - crown/centre/bottom \[target\]

- Swapping
    - swap two targets - swap \[blue air\] with \[green bat\]
    - swap two function calls with their arguments - swap call \[blue air\] with \[green bat\] or swap arg \[blue air\] with \[green bat\]
    - swap two strings - swap string \[arch\] \[whale\]

- Inserting
    - insert a function snippet - snippet funk \[.hello world\]
    - add a new line above the line with the token - drink \[red gust\]
    - add a new line underneath the line with the token - pour \[red gust\]

- Editing
    - rename the end of a function name starting from x word - rename last \[two\] words \[funk name\]
    - delete a word and move the cursor to where it was - change [blue gust]
    
- Wrapping (see also https://www.cursorless.org/docs/#paired-delimiters)
    - surround the line/target with single quotes - twin wrap line/target
    - surround the line/target with brackets/square brackets/curly brackets - round/box/curly wrap line/\[target\]
    - rewrap a target with different pair of symbols - \[curly\] repack 
    \[token\]
    - wrap with an escape - escaped \[box\] wrap line/target

- Formatting
    - apply formatting to a token - format \[title\] at \[air\]
    - formatting terminator - \[snake\] this is a test over \[dot\] ts
    - delete a sentence and rewrite it with the formatter you specify - nope that was \[formatter\]
    - make a token lowercase - format all down at \[token\]
    - indent or remove indent - indent this or dedent this

- Moving text
    - move an item after a target - move item [target] after [target]