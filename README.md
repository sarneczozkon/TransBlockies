## Trans Blockies-Convert shape ##
 This is a casual game about color. There are many colored blocks. Players rely on their self-understanding of color to arrange squares according to their color depth. Many difficulties are waiting for you to challenge, so come and try it!
![](https://upload-images.jianshu.io/upload_images/10258469-c7b0c3e75477a32f.png)
![](https://upload-images.jianshu.io/upload_images/10258469-fd8daf037daa03b7.png)
![](https://upload-images.jianshu.io/upload_images/10258469-6dee54d8d64ca3ae.png)
![](https://upload-images.jianshu.io/upload_images/10258469-f1402e9a97452457.png)
### Level controller ###
There are a lot of repetitive functions, here we extract in accordance with the properties of different levels of several public parent class, each level according to their own needs to choose to inherit the appropriate controller, and ViewDidLoad function initialization of each level of different attributes .

WNXBaseGameViewController is a base class controller for all level ViewController that provides basic property settings for each level of the game and the initialization of each level is encapsulated here and each level only needs to call the buildStageInfo () function in its own ViewDidLoad method , Add to build their own UI can override the parent class method to complete each of the different operations.

Common attributes

WNXGameGuideType guideType Each time you enter the level for the first time, the game gesture hint style

WNXGameGuideTypeNone Silent

WNXGameGuideTypeOneFingerClick Single finger click

WNXGameGuideTypeReplaceClick left and right buttons alternately click

WNXGameGuideTypeMultiPointClick Multiple fingers click simultaneously
