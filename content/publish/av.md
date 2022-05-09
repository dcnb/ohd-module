---
section: Publish and Connect
nav_order: 3
title: Connect Audio or Video
---

### Optional: Connect the transcript to an audio or video file using `av_source`

{:.alert .alert-info .mt-3}
You may want to connect transcript to a audio or video recording. The tool has built in connections to YouTube, Vimeo, Soundcloud, and plain mp3 files.  You'll need to incorporate some simple information in the header of your markdown file to make these connections possible. To provide users navigation to certain moments in the recording, you'll also need to provide timestamps in the data file. 

- Look in the header of your markdown file. You'll see that there is a space for av_source. Here you have four options, using OHD: `mp3, youtube,  soundcloud, or vimeo`. 

Using all lowercase letters, type the platform's name where your file is uploaded. 
{% include bootstrap/figure.md img="howto/avid1.png" caption="" alt="opened file, ready for editing" class="w-50" %}
- Below av_source, you'll see a space for your file's audiovideo-id. Fill in this information. 
{% include bootstrap/figure.md img="howto/avid2.png" caption="" alt="opened file, ready for editing" class="w-50" %}
- Below are pictures indicating the location of various audiovideo-id locations on different platforms. 
{% include bootstrap/figure.md img="howto/youtubeid.png" caption="location of your youtube audiovideo-id" alt="opened file, ready for editing" class="w-50" %}
{% include bootstrap/figure.md img="howto/vimeoid2.png" caption="location of your vimeo audiovideo-id" alt="opened file, ready for editing" class="w-50" %}
{% include bootstrap/figure.md img="howto/soundcloud_path_copy.png" caption="location of your the URL path" alt="opened file, ready for editing" class="w-50" %}


{:.alert .alert-warning .mb-4}
NOTE: if you want to utilize an mp3 file, you can create also create a webpage to house your file and link the URL, in quotation marks, in the audiovideo-id. You can store mp3s in your GitHub repository, but be aware that GitHub only allows a small amount of space to each repository. It's probably best practice to link them from elsewhere. You will also need to change av_source to "mp3". Follow the visualizations below for instruction. 

- If you have a page for your mp3 file copy the URL. 

{% include bootstrap/figure.md img="howto/url_mp3_final.png" caption="" alt="mp3 page URL" %}

- Copy and paste URL with quotation marks included. 

{% include bootstrap/figure.md img="howto/final_source.png" caption="" alt="Included URL for mp3 feature" %}

- Change *av_source* to "mp3". 

