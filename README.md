# AttrTextView
A custom UI text view that allows # and @ symbols to be separated from the rest of the text
and triggers actions upon selection.

For more information, check out this guide on how to use it: 

https://medium.com/compileswift/clickable-hashtags-and-mentions-in-swift-3-0-c627c7d3dd9d#.p1fkj47g8


TODO:
Known Issues: If the mention or hashtag contains a piece of puntuation, the .word granularity for the tokenizer does not properly work. While I have come up with a pretty terrible solution using a for loop, it is definitely not the way to go. This issue is pretty low priority for my purpose but if anyone knows how to build a custom tokenizer, I would appreciate the help!


Currently using a constant value to perform granularity. This means that while the TextView works great for most common font sizes ie. 6-16 or so, it will not be perfectly accurate for others. I might create a custom algorithm to get the pixel width of specific font sizes.
