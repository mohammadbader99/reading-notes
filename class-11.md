# Audio, Video, Images

## Images

You can add **images** to web pages with *HTML* by using `<img>` element and specifying an `src` attribute to put the url or the source of the image.

Also you need to add an `alt` attribute to tell the content of the image.

```
<img src="pic.jpg" alt="Picture">
<img src="URL" alt="Picture">
```

The dimensions of images can be specified using **CSS**, also they can be aligned horizontally or vertically.

Images can be also used as a background behind the boxes or elements.

## Video and Audio

![Audio and Video in HTML](https://img.webnots.com/2016/02/Embed-Audio-and-Video-in-HTML.png)

The `<video>` and `<audio>` elements allow us to load videoes and audioes in our web pages just like images.

```
<video controls>
  <source src="video.mp4" type="video/mp4">
</video>
```

This for example will create a video player with native controls inside of your page.

This native video or audio player can be hidden by removing the `control` element, after that you can control how to show the player controls by using the `HTMLMediaElement` API, for example:

```
HTMLMediaElement.play();
HTMLMediaElement.pause();
```
This interface is available for both audio and video elements.