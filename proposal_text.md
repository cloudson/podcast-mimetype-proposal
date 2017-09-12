# Raw text 

### Summary 

It's inspired on the subtitle file format generate by [SubRip](https://en.wikipedia.org/wiki/SubRip). 

### File format 

Each sentence is followed by 4 parts
1. An incremental numeric number
2. The interval when the metadata appears 
3. The metadata type. Can be a `Link`, a raw `Text` or a `seek` to other point of audio.
4. The data itself separeted 

```text
1
00:10:41 --> 00:10:45
link
http://github.com/cloudson

2
00:12:00 --> 00:12:31
text
This is a comment about the book's author. 

3
00:13:01 --> 00:15:00
seek
00:15:00

```

### Gains
Simple, can be write in any text editor. It's easy to learn. 

### Drawbacks
