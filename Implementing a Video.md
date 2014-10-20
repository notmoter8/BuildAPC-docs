#Embeding a Youtube or Vimeo video:


.. raw:: html

< code youtube or vimeo will give you after clicking embedding >

Done!

-

##Embedding a html5/native/self-hosted video:

In the reStructuredText file, we edit in our `<video></video>` tag after declaring html code with `.. raw:: html`

Example:

`.. raw:: html

<video id="example_video_1" class="video-js vjs-default-skin"
  controls preload="auto" width="640" height="264"
  poster="/videos/file1.png"
  data-setup='{"example_option":true}'>
 <source src="/videos/file1.mp4" type='video/mp4' />
 <source src="/videos/file1.webm" type='video/webm' />
 <source src="/videos/file1.ogg" type='video/ogg' />
 <p class="vjs-no-js">To view this video please enable JavaScript, and consider upgrading to a web browser that <a href="http://videojs.com/html5-video-support/" target="_blank">supports HTML5 video</a></p>
</video>`