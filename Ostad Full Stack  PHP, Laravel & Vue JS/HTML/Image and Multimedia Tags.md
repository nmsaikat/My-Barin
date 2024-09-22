### ``<img>``
- **This tag is used for embedding an image in the HTML page. The ``src`` attribute specifies the path to the image file, and the ``alt`` attribute provides alternative text for the image if it cannot be displayed. The width attribute specifies the ``width`` of the image.**

### ``<video>``
- **The ``<video>`` tag is used to embed video content. It can contain one or more <source> elements to specify multiple video ``sources`` for different formats. The ``controls`` attribute adds video controls, like play, pause, and volume.**

### ``<audio>``
- **Similar to ``<video>`` , the ``<audio>`` tag is used for embedding audio content and can contain multiple ``<source>`` elements. The ``controls`` attribute adds audio controls.**

### ``<iframe>``
- **This tag is used to embed another HTML document within the current page. In this example, it's used to embed a YouTube video. The ``src`` attribute specifies the URL of the page to embed.**

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Image and Multimedia Tags Example</title>
  </head>
  <body>
    <h2>Image Tag</h2>
    <img src="example.jpg" alt="Example Image" width="300" />
    <h2>Video Tag</h2>
    <video width="320" height="240" controls>
      <source src="movie.mp4" type="video/mp4" />
      <source src="movie.ogg" type="video/ogg" />
      Your browser does not support the video tag.
    </video>
    <h2>Audio Tag</h2>
    <audio controls>
      <source src="audio.mp3" type="audio/mpeg" />
      <source src="audio.ogg" type="audio/ogg" />
      Your browser does not support the audio tag.
    </audio>
    <h2>Embedded YouTube Video</h2>
    <iframe
      width="560"
      height="315"
      src="https://www.youtube.com/embed/dQw4w9WgXcQ"
      frameborder="0"
      allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-
picture"
      allowfullscreen></iframe>
  </body>
</html>
```