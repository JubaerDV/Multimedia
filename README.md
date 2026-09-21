## 🟤 Level 8 — Multimedia

HTML Multimedia elements are used to add audio, video, embedded content, and other media to a webpage.

### 📌 Topics Covered

1. **Audio — `<audio>`**
   Used to add audio files such as music or sound to a webpage.

2. **Video — `<video>`**
   Used to display video files on a webpage.

3. **Source — `<source>`**
   Defines different media sources for `<audio>` and `<video>` elements.

4. **Iframe — `<iframe>`**
   Used to embed another webpage, video, map, or external content inside a webpage.

5. **YouTube Embed**
   Used to embed YouTube videos into an HTML webpage using `<iframe>`.

6. **Audio Controls**
   The `controls` attribute adds audio controls such as play, pause, and volume.

7. **Video Controls**
   The `controls` attribute adds video controls such as play, pause, volume, and fullscreen.

8. **Autoplay**
   The `autoplay` attribute makes audio or video start automatically.

9. **Loop**
   The `loop` attribute makes audio or video play repeatedly.

10. **Muted**
    The `muted` attribute starts audio or video without sound.

### 💻 Example

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>HTML Multimedia</title>
</head>

<body>

    <h1>HTML Multimedia</h1>


    <!-- Audio -->
    <h2>Audio</h2>

    <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>


    <br><br>


    <!-- Audio with Autoplay, Loop and Muted -->
    <h2>Audio with Attributes</h2>

    <audio controls autoplay loop muted>
        <source src="audio.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>


    <br><br>


    <!-- Video -->
    <h2>Video</h2>

    <video width="500" controls>
        <source src="video.mp4" type="video/mp4">
        Your browser does not support the video element.
    </video>


    <br><br>


    <!-- Video with Autoplay, Loop and Muted -->
    <h2>Video with Attributes</h2>

    <video
        width="500"
        controls
        autoplay
        loop
        muted
    >
        <source src="video.mp4" type="video/mp4">
        Your browser does not support the video element.
    </video>


    <br><br>


    <!-- Iframe -->
    <h2>Iframe</h2>

    <iframe
        src="https://example.com"
        width="600"
        height="400"
        title="Example Website"
    ></iframe>


    <br><br>


    <!-- YouTube Embed -->
    <h2>YouTube Video</h2>

    <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/VIDEO_ID"
        title="YouTube Video"
        allowfullscreen
    ></iframe>

</body>

</html>
```

### 📝 What I Learned

* How to add audio using `<audio>`
* How to add video using `<video>`
* How to provide media files using `<source>`
* How to embed external content using `<iframe>`
* How to embed YouTube videos
* How to add audio and video controls
* How to use `autoplay`
* How to use `loop`
* How to use `muted`
* How HTML supports multimedia content

### 🔑 Important Attributes

| Attribute         | Purpose                                    |
| ----------------- | ------------------------------------------ |
| `controls`        | Shows media controls                       |
| `autoplay`        | Starts media automatically                 |
| `loop`            | Repeats the media                          |
| `muted`           | Starts media without sound                 |
| `src`             | Specifies the media source                 |
| `type`            | Specifies the media file type              |
| `width`           | Sets the width of video/iframe             |
| `height`          | Sets the height of video/iframe            |
| `allowfullscreen` | Allows an iframe video to enter fullscreen |

**Level 8 Completed ✅**
