Description
-----

Sometimes you may want to post a photo to twitter, instagram, Path or other SNS, but if the photo is taken by DSLR, the size of the image file will be too large for uploading. 

So I create a simple OSX service to convert the photo to a smaller one.

Installation
----
1. Clone the project
2. Double-click the project to install the service.

The project folder will be copied to folder **~/Library/Services**

Usage
----
1. Select any image file in Finder
2. Click menu "Finder"->"Services"->"Create a smaller image copy"

You can add keyboard shortcut for this service in Keyboard Preference Panel.

Note
----
You can find the source code in file **Contents/document.wflow**


This service uses a OSX builtin command line tool "sips" to do the conversion.
