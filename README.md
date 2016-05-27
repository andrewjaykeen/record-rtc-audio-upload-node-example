# record-rtc-audio-upload-node-example
An example of using recordRTC to capture audio via the browser and upload to a simple node.js backend.


![Screenshot](screenshot.png?raw=true "Screenshot")


This project is a simple example of recording audio via a web browser with the recordRTC library, and 
then uploading it to a node.js backend that saves the file on the file system.  

This is essentially just a trimmed down copy of muaz-khan's audio+video capture example.
(see here: https://github.com/muaz-khan/RecordRTC/tree/master/RecordRTC-to-Nodejs). 

The intention of this is to simply provide a working example of audio only, without the need for ffmpeg on the backend.

This has been minimally tested in Chrome and Firefox, but no guarentees are provided. 

To run: 
```
node index.js
```

Open a browser to: 
```
http://localhost:8000
```

Uploaded recordings should appear on the server in the uploads folder

It currently records *.wav in chrome, and *.ogg in firefox by default.


