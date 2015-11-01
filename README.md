##What is UploadX?

UploadX is a student project aiming to bring the functionality of the ShareX platform to Linux through Python.

##Why?

We enjoy the ease at which ShareX and services like it allow users to upload and distribute images from their computers. We found a lack of such service on Linux distributions and decided to create our own service using Python as a rapid-prototyping platform.

##Features

UploadX supports many features that user will find helpful such as custom screen capturing, automatic uploading of local files, and automatic QR Code generation. UploadX is also integrated with popular platforms such as imgur, Dropbox, and Twitter. With this wide variety of options, the user can choose the path that fits their needs.

##Installation

Installation of UploadX is easy, simply download the compressed project folder and extract it to your choice of destination. To start the program, simply run main.py with Python 2.7.

##Project Evolution

UploadX started as a simple tool for uploading images to imgur, then it was merged with another project which let the user define a rectangle on their screen and take a screenshot of that area. This combination is the core of UploadX, allowing the user to define an area and upload the screenshot to an image hosting site. After some peer feedback, we decided to add edit functionality to the program so the user could draw on the image similar to Snapchat. We also started work on integrating multiple destinations for our images, and experimented with social media integration. Out of all the social media sites, Twitter was the easiest to implement, and so we added the ability for the user to tweet their image with a message. Although the message is fixed as of now, we have an update pending that allows for user defined messages. At this time we also integrated the ability to manually select functions both for debugging and so that the user would not have to define a workflow for one individual step. As of now, UploadX is capable of uploading images defined by the user to imgur, Dropbox, and Twitter, as well as generating QR codes of the links for the images.

##Dependencies

UploadX depends on several libraries
1. Asynchronous File Reader
2. pyxhook
3. qrcode
4. pygtk
5. tweetpony
