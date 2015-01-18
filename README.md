# Video Quote

Annotate timestamps of video, and share them as video clips for embedding or social media. Built in tandem with the [videopizza](https://github.com/amontalenti/videopizza) project.

Runs on the [OpenVideoAnnotation](http://openvideoannotation.org/) plugin.

### Features

- Annotate with richtext, images, or videos
- Geolocation option
- Splice and create subclips for embedding in social media
- Annotation analytics
- Easy to add user permissions, auth, etc.

### Setup

- Install [elasticsearch](http://elasticsearch.org)
- Clone, install, and run [this fork](https://github.com/mailbackwards/annotator-store) of the OKFN's annotator-store. This stores and interacts with the annotations.
- Run a local server on this folder
- ???
- Profit

### Use

Navigate to localhost to see the video player. You'll see three controls in the bottom right corner:
![annotator-controls](https://cloud.githubusercontent.com/assets/1697151/5793792/3af96fbc-9f1f-11e4-84ac-42f655bcbf54.png)

- On the left, make a new annotation.
- In the center, view a graph of recent annotations. Click on any of them to view the clip.
- On the right, view a high-level graph of analytics.

When you view an annotation, you have the option of storing a clip from it on Amazon S3 for embedding/sharing:

![share-controls](https://cloud.githubusercontent.com/assets/1697151/5793839/6294952c-9f21-11e4-8392-012ee446fbe4.png)

Future feature: overlay the annotation's text onto the video itself.