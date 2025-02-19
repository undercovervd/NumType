# NumType
Full on keyboard in a 3x3 numpad grid,

# Usage
Its all but perfect, but this is how it works:
- The keyboars is split into 9 segments
- Every row of the keyboard is split into 3 (for example the top row is "qwer" "rtyu" and "uiop") The letters overlap to allow for some error
- typing "hello" goes like this: "h" is middle middle row, "e" is top left row, "l" is middle right row, "o" is top right row. combine those and oyu will get "57669". My program uses 3 kinds of algorithms to decypher what should mean. To find what is the most obvious word it will first load a dictonary, then it will load another dictionary containing ranked words. It will compare them and find the most obvious word. It will not always get this right tho. Thats why there is a file called "bigrams.json" included in this project. It looks for word combinations to find what the user is probably trying to find. If this is still wrong, you can change the words by hovering over them.

# Connectivity
This system could run completely offline if you would include the dictonary's in the project.
