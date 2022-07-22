# Vision
Cross framework, cross platform computer vision library for Haxe.

The goal of this library is to provide computer vision functionality to Haxe projects, but naturally:

### What Does That Mean?

Basically, if you're using HaxeFlixel for example, you should be able to easily use an FlxSprite as
an image to process, or if youre using OpenFL you should be able to use bitmaps and sprites to process.

### Why Does This Library Exist?

One of the problems i have with Haxe is the lack of non-game utilities and libraries. my goal is to provide those utilities, and make app development in Haxe easier.

### Roadmap

Here is a roadmap of all features added/planned for the future:

> **Bold** means high priority,  
> Regular means medium priority,  
> *Italic* means low priority.  
> 


#### class `Vision`:
 
 - [x] grayscaling
 - [x] black and white
 - [x] inverting
 - [x] Contrast image (exaggerated colors)
 - [ ] **Line detection (hough method)**
 - [x] Line detection (recursive method)
 - [ ] *Circle detection (hough method)*
 - [ ] *Rectangle detection (recursive method)*
 - [ ] *Triangle detection (recursive method)*
 - [x] edge detection (perwitt method)
 - [x] edge detection (sobel method)
 - [ ] *edge detection (canny method)*
 - [x] nearest-neighbor style blur
 - [x] gaussian blur 

#### algorithms:

 - Hough Transform
    - [x] hough space generation
    - [ ] *adaptive hough space generation*
    - [ ] line segment finder
    - [ ] *Circle finder*

 - Gaussian
   - [x] 5x5 kernal generation
   - [ ] *3x3 kernal generation*
   
#### class `Image`:

 - [x] `getPixel()`
 - [x] `setPixel()`
 - [x] `hasPixel()`
 - [x] `paintPixel()`
 - [x] matrix access
 - [x] floodfill
 - Drawing:
   - [x] `drawLine()`
   - [x] `drawRect()`
   - [x] `drawCircle()`
   - [ ] `drawCurve()`
   - [ ] `drawBezierCurve()`
   - [x] `drawLineWithLerp()`
   - [x] `fillRect()`
   - [ ] `fillCircle()`
   - [x] `callDrawSequence()`
 - Copying:
   - [x] `clone()`
   - [x] `getImagePortion()`
   - [x] `setImagePortion()`
   - [x] `copyPixel()`