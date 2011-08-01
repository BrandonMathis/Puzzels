
Take in a text string and produce two arrays which will then be stored in the archive. The first array will contain all the unique words in the original text. Thus, if you start with this text.  

    "This specification is the specification for a specification"

Then the first array would contain all the words found in the text, with no repeats, like this:

    [“This”, “specification”, “is”, “the”, “for”, “a”]

The second array will contain integer indexes. There will be one index in this second array for each work in the original document. In our example, the second array would contain this:

    [0, 1, 2, 3, 1, 4, 5, 1]

You have access to the following methods

**str.split**

>divides str into substrings based on a delimiter, return an array of these substrings ie: 
      
      "This test is a test”.split #=> [“This”, “test”, “is”, “a”, “test”]
