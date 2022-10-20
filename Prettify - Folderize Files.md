## Prettify - Folderize Files

This action will prettify the folder structure by leveraging your tags. This helps when managing a large library and for importing into plex, jellyfin, etc. Having a pretty folder structure can help you stay sane when adding large numbers of audiobooks. When downloading audiobooks, their folder structure is rarely ideal, so having a quick way to turn that mess into a coherent directory, is a must have if you intend to build a sizeable library.

<br> **This action will map the following fields:**
<br> %ALBUMARTIST% -> Author
<br> %ALBUM% -> Book
<br> %TITLE% -> Filename
<br> %TRACK% -> Padding

into something like: 
 
<img width="301" alt="image" src="https://user-images.githubusercontent.com/100229664/196858308-7497c98b-1543-4802-92bc-1bf4c4008af3.png">

A great folder structure to have is: 

```
Author/
├─ Book/
├─ Book/
├─ Book/
├─ Saga/
│  ├─ First Book of Saga/
│  ├─ Second Book of Saga/
│  ├─ Third Book of Saga/
Another Author/
```
