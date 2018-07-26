---
permalink: /tutorials/simple-rectangle/
title: A simple Rectangle
last_modfied_at: 2018-07-26
excerpt: "Creating a simple Satin Stitch on a rectangle"
image: "/assets/images/tutorials/rectangle/rectangle15.png"

tutorial-type:
  - Text
stitch-type:
  - Satin Stitch
user-level: Beginner
---

## Introduction
In this getting started tutorial, you'll be taken through the steps to make a simple satin stitch around a rectangle. This takes you through all the basic steps of turning a shape into the correct paths and subpaths that will allow Inkstitch to produce good stitches.

This tutorial assumes that you have Inkstitch installed.

## Stitching a Rectangle

### Draw a Rectangle
First we will just draw a simple rectangle.

![Rectangle Image](/assets/images/tutorials/rectangle/rectangle01.png)

### Turning the Rectangle into *two* subpaths.

For a satin stitch we need two subpaths that Inkstitch will then stitch between.
1. We set the fill to none.
![Fill image](/assets/images/tutorials/rectangle/rectangle02.png)
2. We set the stroke to a solid color.
![Stroke Color](/assets/images/tutorials/rectangle/rectangle03.png)
3. Now we set the stroke width. In this case we want a 5mm stitch.
![Stroke width image](/assets/images/tutorials/rectangle/rectangle04.png)
4. Now we click Stroke to Path
![Stroke to Path menu icon](/assets/images/tutorials/rectangle/rectangle05.png)
5. We need to tell Inkstitch where it should have the machine start and end the stitch. Here we simply select a node
![Node Selection](/assets/images/tutorials/rectangle/rectangle06.png)
and click 'Break path at selected nodes.'
![Break Node](/assets/images/tutorials/rectangle/rectangle07.png)
Break the path on each subpath.
6. It's very helpful to always show the path outline, as well as path _direction_. Inkstitch treats path direction very importantly. As you can see with the screenshot we have small arrows pointing in the direction of the path.
![Path screenshot](/assets/images/tutorials/rectangle/rectangle08.png)
However, this won't work with inkstitch, we need the two subpaths going same direction. So we reverse the path as show below
![Reverse path](/assets/images/tutorials/rectangle/rectangle09.png)
Now, as you can see with our arrow, they are pointing the same way
![Arrows pointing the same way](/assets/images/tutorials/rectangle/rectangle10.png)
7. Now we set our parameters to Satin Column. And odds are, we will get an error, like so
![Error](/assets/images/tutorials/rectangle/rectangle11.png)
This is because by default Inkstitch uses the path to guide its stitching and requires each subpath to have the same amount of nodes to do it automatically. But we can help guide Inkstitch by adding additional subpaths. To do this we:
  1. Press 'n'
  2. Select our path.
  3. Press 'p'
  4. While holding 'shift' draw a line across our two paths, essentially in the direction that we want out stitches to follow. 

We'll get something like this:
![Subpath draw](/assets/images/tutorials/rectangle/rectangle12.png)
I'm not very good at straight lines, but it's good enough to help out Inkstitch. Now we can see what out stitch will look like
![Show Embroidery menu](/assets/images/tutorials/rectangle/rectangle13.png)
It works! But produces some ugly stitches.
8. But by using additional subpaths, we can guide Inkstitch to making better stitches, like so:
![Lots of lines](/assets/images/tutorials/rectangle/rectangle14.png)
![After lines](/assets/images/tutorials/rectangle/rectangle15.png)

Better. Mine is a little wonky looking because my lines are fat and my squares are small, but that's enough of the general idea to start turing drawings into stitches.
