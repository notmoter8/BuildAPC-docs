in the <head> </head>

<link href="//vjs.zencdn.net/4.9/video-js.css" rel="stylesheet">
<script src="//vjs.zencdn.net/4.9/video.js"></script>

in the reST


.. raw:: html

<video id="example_video_1" class="video-js vjs-default-skin"
  controls preload="auto" width="640" height="264"
  poster="/videos/file1.png"
  data-setup='{"example_option":true}'>
 <source src="/videos/file1.mp4" type='video/mp4' />
 <source src="/videos/file1.webm" type='video/webm' />
 <source src="/videos/file1.ogg" type='video/ogg' />
 <p class="vjs-no-js">To view this video please enable JavaScript, and consider upgrading to a web browser that <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a></p>
</video>