# Android Video Compressor
- Fork from https://github.com/lalongooo/VideoCompressor.git
- Video Compressor based&update in the [**Telegram for Android**](https://github.com/DrKLO/Telegram) [![Telegram for Android](https://raw.githubusercontent.com/lalongooo/VideoCompressor/master/images/ic_launcher.png)](https://github.com/DrKLO/Telegram) app source code.

## Setup
```groovy
  compile 'com.yovenny.VideoCompress:videocompress:1.0.0'
  
  compile project(':videocompress')
```

## Usage

```java
   //in a new Thread
   boolean isCompressSuccess=MediaController.getInstance().convertVideo(inPath,outPath);
```

## Log

- add api<18 `convertVideoFrame` jni support
**2016-6-22**