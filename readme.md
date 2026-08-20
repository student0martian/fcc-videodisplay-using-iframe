# Build a Video Display Using iframe

Exercises are based on the [freeCodeCamp.org](https://freecodecamp.org) curriculum. All solutions are my own work.  
  
  
### Step 1  
In this workshop, you will use the `iframe` element to display a video.
The basic HTML boilerplate has been prepared for you.  
```html
<!DOCTYPE html>
 <html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>
     Display Videos in an iframe
     </title>
   </head>
  <body>
   </body>
 </html>
```  

Begin by creating an `h1` element with the text `iframe Video Display`.  


### Step 2  
Now, create an `iframe` element.  
Don't put anything in it yet.  


### Step 3  
In the first lesson on the `iframe` element, you learned it's a replaced element just like `img`. That means it can also take the `width` and `height` attributes to determine how tall and wide it should be.  

Give your `iframe` element a `width` of `560` and a `height` of `315`.  


### Step 4  
The `iframe` element also takes an `src` attribute with a value that indicates the URL or the path of the resource to display.  

Add an `src` attribute of `https://www.youtube.com/embed/I0_951_MPE0` to your `iframe` element.  

At this point, you should see the video displaying on the page, but there are some more attributes you need to add.  


### Step 5  
One of the attributes is `allow`. It's like a permission list that tells the browser what features the `iframe` is allowed to use.  

Here's an `iframe` element with the `allow` attribute:  

**Example Code**  
```html
<iframe allow="accelerometer autoplay 
clipboard-write encrypted-media gyroscope picture-in-picture web-share">
</iframe>
```  

Add the `allow` attribute with the value `accelerometer`, `autoplay`, and `clipboard-write`.  

`accelerometer` lets the `iframe` use motion sensors so it can detect things like device tilting and rotation. `autoplay` lets the video start playing automatically, and `clipboard-write` lets the `iframe` write data to the user's clipboard.  


### Step 6  
Add `encrypted-media`, `gyroscope`, and `web-share` to the existing values in the `allow` attribute.  

These three will allow the use of encrypted media extensions to protect the video, grant access to the device's motion and orientation
sensors, and allow sharing the `iframe`
content through the device's native share dialogs.  


[**Click the link to see my work https://student0martian.github.io/fcc-videodisplay-using-iframe/**](https://student0martian.github.io/fcc-videodisplay-using-iframe/)  
  
  
[*Check out this book I'm reading*](https://www.freecodecamp.org/news/learn-to-code-book/)
