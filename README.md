avprobe-node
=======

This is node module for fetch music meta tag, with avprobe(ffprobe)

There is same project ffprobe-node, but it is not comfortable for me, and just fetch mp3 meta tag.

Usage
-----
It is easy to use it, but at first, u need install avconv(ffmpeg),it include avprobe.

```js
> var avprobe = require('avprobe-node');
> avprobe('music file', function(meta){
> 
> });
