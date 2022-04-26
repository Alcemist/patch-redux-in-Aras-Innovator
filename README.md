# patch-redux-in-Aras-Innovator

### It is patch file for redux.js library in Aras Innovator Client

Aras Innovator Client has the memory leak problem by using the wrong custom redux library. 
This will patch the memory leak.

It has tested in Aras Innovator 12 SP9 and version of "redux.js" is based on 4.2.0.

## How to Use

1. Going in "{Your Setup Folder}\Innovator\Client\vendors"
2. Backup your original "redux.js".
3. Replace "redux.js" file to new File.
4. Restart IIS.
5. If you have a problem, then restore it.
