
## Start with an Album

You'll need to fetch this from localstorage or firebase or ?
But images will need to stay on the device until you get network again.


## Photos

[Be Inspired by Cheese](https://polymer-cheese.firebaseapp.com/)

[Great article](https://developers.google.com/web/fundamentals/media/capturing-images/) covers basics.

You could start with a basic:

```
<input type="file" accept="image/*" capture>
```

and let the user choose. Or you could be specific:

```
<input type="file" accept="image/*" capture="user">
```

for the selfie camera, or the main camera 

```
<input type="file" accept="image/*" capture="environment">
```

But that only works on phones. Desktops will prompt for an upload.

## Working with Fullscreen Mode


## Applying Instagram Image Filters

Via CSS is quick ala [CSSgram](https://una.im/CSSgram/)
Or something [more serious](https://github.com/girliemac/filterous-2) which alters the image itself

## Asking permission to record stuff

Give a compelling reason, and in the right context. Not too early.

## Selecting Available Devices

If you're using a PC, microphone will matter

## Showing a Video element, Capturing to a Canvas

You could rework our Photo capture to use this technique. 
Remember: ask for permission appropriately.

Start progressive.
```
<input type="file" accept="video/*" capture>
```
Then pipe that into an <video> element and you're off


## Recording an Audio stream

Sample principles as video.

Start progressive.
```
<input type="file" accept="audio/*" capture>
```
Then pipe that into an <audio> element and you're off

Visualise on a cool audio element




