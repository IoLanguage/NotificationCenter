# NotificationCenter 
An NotificationCenter similar to the one found in Apple's FoundationKit.

Example use:
```Io
// in listener
listener := NotificationListener clone setTarget(self) setName("FeedDownloadedFile") start

// in sender
Notification clone setSender(self) setName("FeedDownloadedFile") post

// note: notifications can also be reused, and any extra data can be added in it's slots

// to stop listening
listener stop
```

# Installation
```
eerie install https://github.com/IoLanguage/NotificationCenter.git
```
