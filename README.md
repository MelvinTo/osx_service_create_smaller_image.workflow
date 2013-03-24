Purpose
-----

Sometimes you may want to post a photo to twitter, instagram, Path or other SNS, but if the photo is taken by DSLR, the size of the image file will be too large for uploading. 

So I create a simple OSX service to convert the photo to a smaller one. The width of the converted image will be 1024.

This service won't alter your original image, it creates a copy of your existing image.

Installation
----
1. Clone the project
2. Double-click the project to install the service.

The project folder will be automatically copied to folder **~/Library/Services**

Usage
----
1. Select any image file in Finder
2. Click menu "Finder"->"Services"->"Create a smaller image copy"

 ![image](http://d1zjcuqflbd5k.cloudfront.net/files/acc_113533/DhHX?response-content-disposition=inline;%20filename=Screen%20Shot%202013-03-24%20at%201.56.45%20PM.png;%20filename*=UTF-8%27%27Screen%20Shot%202013-03-24%20at%201.56.45%20PM.png&Expires=1364105167&Signature=Cc8pWd~w-O1k2w9FFrKET5Yqh9xvRgA7LBa9MVvxm~afg343PELZrVlni65PTFzjp33XGSloqy44DCeiiW9p0VMmofbaBgz9XHsKDK~b-nfAAS9cZ5MoNy2x0XcLVXQOk13Uie2yH1RpyGNMLy1dlBSvwtzQ~5zpOMTdEjv0Jyg_&Key-Pair-Id=APKAJTEIOJM3LSMN33SA)


You can add keyboard shortcut for this service in Keyboard Preference Panel.

Note
----
You can find the source code in file **Contents/document.wflow**


This service uses a OSX builtin command line tool "sips" to do the conversion.
