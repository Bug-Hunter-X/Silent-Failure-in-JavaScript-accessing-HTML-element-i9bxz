# Silent HTML Element Access
This repository demonstrates a subtle bug in JavaScript interacting with the HTML DOM. The script attempts to access an element that does not exist.  Instead of throwing an error, the script silently fails, making it harder to debug. 
The solution involves robust error handling using try...catch blocks to gracefully handle such situations.