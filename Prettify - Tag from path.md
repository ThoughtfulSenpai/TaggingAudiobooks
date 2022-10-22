## **Files to tags**
Say your audiobook has no embedded tags, or that they are a complete mess. But the folder structure/filename is indeed nicely formatted. You may use the file path and set as tags.


### **Files to tags : Set name of folder to Book name**
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

### **Files to tags : Set filename to track number and title of chapter**
Say your files are numerated and that each file contains the name of the chapter. 

```
└── この素晴らしい世界に祝福を！ あぁ、駄女神さま 上/
    ├── [1] この素晴らしい世界に祝福を！.m4a
    ├── [2] この素晴らしい世界に祝福を！.m4a
    ├── [3] この素晴らしい世界に祝福を！.m4a
    ├── [4] この素晴らしい世界に祝福を！.m4a
    ├── [5] この素晴らしい世界に祝福を！.m4a
    └── [6] この素晴らしい世界に祝福を！.m4a
```
or

```
└── この素晴らしい世界に祝福を！ あぁ、駄女神さま 上/
    ├── (1) この素晴らしい世界に祝福を！.m4a
    ├── (2) この素晴らしい世界に祝福を！.m4a
    ├── (3) この素晴らしい世界に祝福を！.m4a
    ├── (4) この素晴らしい世界に祝福を！.m4a
    ├── (5) この素晴らしい世界に祝福を！.m4a
    └── (6) この素晴らしい世界に祝福を！.m4a
```

or any similar pattern of a number followed by a name of chapter.
