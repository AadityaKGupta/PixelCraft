# PixelCraft  
A pixel art & animation creation tool built using HTML5 Canvas.  
It is a **Progressive Web App (PWA)** with offline compatibility, mobile-friendly design, and an intuitive interface.  

![PixelCraft](icons/logo.png)  

## Features  
- **Customizable Canvas**: Choose dimensions (default: 16x16). Dimensions below 128x128 are recommended for smooth performance.  
- **GIF Support**: Create animations by adding frames and exporting them as GIFs.  
- **Offline Support**: Works seamlessly as a PWA.  
- **Advanced Tools**: Import images, convert them to pixel art, and customize them easily.  
- **Flexible Output**: Save your creations as PNG or GIF.  
- **Color Transparency**: Create complex patterns using translucent colors.  

---

## Table of Contents  
1. [Overview](#overview)  
2. [Toolbar](#toolbar)  
3. [GIF Tools](#gif-tools)  
4. [Utility Tools](#utility-tools)  
5. [Advanced Tools](#advanced-tools)  
6. [Saving Pixel Art and GIF Animation](#saving-pixel-art-and-gif-animation)  
7. [Color Palette & Transparency](#color-palette--transparency)  
8. [PWA Support](#pwa-support)  
9. [Sample Pixel Art](#sample-pixel-art)  
10. [Contact Information](#contact-information)  

---

## Overview  

On opening PixelCraft, you’ll see a screen like this:  

![PixelCraft overview](images/overview.png)  

You can select canvas dimensions. The default is **16x16**, but dimensions below **128x128** are preferable for smooth operation and GIF creation.  

---

## Toolbar  

![Toolbar](images/toolbar.png)  

PixelCraft includes the following tools:  

### 1. Pencil  
Draw pixels freehand.  

![Pencil Tool](https://user-images.githubusercontent.com/17960677/96023223-b83b8800-0e6f-11eb-8af1-0cfab42c19d7.png)  

### 2. Eraser  
Erase pixels one at a time. The size is fixed at **1x1**.  

![Eraser Tool](https://user-images.githubusercontent.com/17960677/96023372-f5077f00-0e6f-11eb-965f-815b37f0d7b2.png)  

### 3. Paint Tool  
Flood-fill a region with a new color.  

![Paint Tool](https://user-images.githubusercontent.com/17960677/96023679-6b0be600-0e70-11eb-8451-0d5955f2c8b4.png)  

### 4. Line Tool  
Draw a line segment between two points using the **Bresenham line-drawing algorithm**.  

![Line Tool](https://user-images.githubusercontent.com/17960677/96023893-b625f900-0e70-11eb-9b16-ac0d68f9423c.png)  

### 5. Circle Tool  
Draw a circle using the **Midpoint Circle Algorithm**.  

![Circle Tool](https://user-images.githubusercontent.com/17960677/96024358-3d736c80-0e71-11eb-8c1a-acb528f027b6.png)  

### 6. Ellipse Tool  
Draw an ellipse by specifying the center and radii along the x-axis and y-axis.  

![Ellipse Tool](https://user-images.githubusercontent.com/17960677/96024638-a0fd9a00-0e71-11eb-9171-16944bf95b40.png)  

---

## GIF Tools  

### Add Frame  
Add the current canvas state to the frame stack.  

### View Frame  
Displays a popup with all frames in the stack. Click to load, right-click to delete a frame.  

![Frame Panel](https://user-images.githubusercontent.com/17960677/96025802-48c79780-0e73-11eb-8ca1-4948226804ad.png)  

---

## Utility Tools  

### Undo/Redo  
Undo or redo small pixel changes (one pixel at a time).  

### Clear Window  
Clear the entire canvas.  

---

## Advanced Tools  

### Import Image  
Convert an image into pixel art at customizable dimensions.  

![Pixelated Mona Lisa](https://user-images.githubusercontent.com/17960677/96027394-71509100-0e75-11eb-8260-c1ed426805bc.png)  

---

## Saving Pixel Art and GIF Animation  

### Save Image  
Download your artwork as a PNG with dimensions scaled to **10x width x 10x height**.  

### Save GIF  
Export your animations as GIFs.  

---

## Color Palette & Transparency  

Choose colors from a pre-defined palette. Set transparency values (between 0 and 1) for creating complex patterns.  

![Color Palette](https://user-images.githubusercontent.com/17960677/96028508-fdaf8380-0e76-11eb-8502-18d49d96d059.png)  

---

## PWA Support  

Install PixelCraft as a PWA via the dropdown menu or “Add to Home Screen” on mobile devices.  

![PWA Support](https://user-images.githubusercontent.com/17960677/96029402-3ef46300-0e78-11eb-8a54-d54b6dff458a.png)  

---

## Sample Pixel Art  

Here are some creations made using PixelCraft:  

<img src="https://user-images.githubusercontent.com/17960677/96029683-a14d6380-0e78-11eb-8901-bff832a4cb6e.gif" alt="canvas1" width="150" height="150">  
<img src="https://user-images.githubusercontent.com/17960677/96029686-a3afbd80-0e78-11eb-8c03-0f407a5110fd.gif" alt="canvas2" width="150" height="150">  

---

## Contact Information  

Feel free to reach out for support, contributions, or feedback:  

- **Email**: [k.aaditya.gupta@gmail.com](mailto:k.aaditya.gupta@gmail.com)  
- **GitHub**: [AadityaKGupta](https://github.com/AadityaKGupta)  
