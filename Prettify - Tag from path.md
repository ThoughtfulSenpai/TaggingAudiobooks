## **Prettify - Tags from path**
Say your audiobook has no embedded tags, or that they are a complete mess. But the folder structure is indeed nicely formatted. You may use the file path and set as tags.


### **Prettify - Tags from path : Set name of folder to Book name**
So, all of your folders are neatly set, but the actual tags are a mess. In this case, you could set the name of the folder to become the name of the book (album tag).  Works best with directories named as follows. Simply apply the action to the main folder, in this case Charles Dickens, and each book will be processed accordingly. Ech book will get the correct name from its immediate parent directory.


```
├── Charles Dickens/
├── ├─ Great Expectations/
│   ├── Great expectations 01.mp3
│   ├── Great expectations 02.mp3
│   ├── Great expectations 03.mp3
│   ├── Great expectations 04.mp3
│   ├── Great expectations 05.mp3
│   ├── Great expectations 06.mp3
│   └── Great expectations 07.mp3
├── ├─ David Copperfield/
│   └── David Copperfield.m4b
├── ├─ Oliver Twist/
└── ├─ Bleak House/
```

https://github.com/ThoughtfulSenpai/TaggingAudiobooks/blob/main/Actions/01_Book%20name%20from%20Folder%23%26%25artist%25%20-%20%25album%25.mta
