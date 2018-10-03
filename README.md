#Cordova YoutubeVideoPlayer Plugin Fix for android-cordova >= 7.0.0

**Fork plugin @ihadeed**

Install 

**Play Youtube Videos in a native Video Player on Android &amp; iOS.**

##Installation

```sh
cordova plugin add https://github.com/adrianowead/CordovaYoutubeVideoPlayer
```

##Usage

```javascript
YoutubeVideoPlayer.openVideo('YOUTUBE_VIDEO_ID', function(result) { console.log('YoutubeVideoPlayer result = ' + result); });
```

For Android 5.0+ you will need to add the following to config.xml

```xml
<preference name="YouTubeDataApiKey" value="[YOUR YOUTUBE API]" />
```
with your own YouTube Key.

 For more information: https://developers.google.com/youtube/v3/getting-started

The callback is called when the video window is closed.  (Work in Progress - should be working for IOS).

##Author

**Adrien Glitchbone**

+ [https://twitter.com/glitchbone](https://twitter.com/glitchbone)
+ [http://github.com/Glitchbone](http://github.com/Glitchbone)

**d0cz**
+ [http://github.com/d0cz](http://github.com/d0cz)

**trakout**
+ [https://github.com/trakout](https://github.com/trakout)

##License

CordovaYoutubeVideoPlayer is available under the MIT license. See the [LICENSE](LICENSE) file for more information.  
XCDYouTubeKit is available under the MIT license.  
OpenYoutubeActivity is available under the Apache License 2.0.  
