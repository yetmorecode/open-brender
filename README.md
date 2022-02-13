# OpenBRender

BRender clone for DOS

## Motivation

It's 2022 and I've been poking around BRender for about 5 years. It's too young to die. Let's bring it back!

I found those great minds at https://github.com/dethrace-labs/dethrace/tree/main/src/BRSRC13 providing a IDA based decompilation as well. 

## Links & Inspiration

* https://github.com/dethrace-labs/dethrace
* https://floppy.foone.org/w/BRender
* https://rr2000.cwaboard.co.uk/R4/BRENDER/TEBK_1.HTM

```
What is BRender?

BRender is a rendering engine, the `bit of magic in the middle' that turns a scene into an image. It is the TV camera of virtual reality, translating an abstract description of a set, with its actors, cameras and lights, into a picture on a screen.

BRender is a combination of the most recent research in 3D graphics techniques and algorithms, and painstaking efforts to translate those algorithms into streamlined, lean, mean and highly optimised C code. Efficiency notwithstanding, BRender has always been designed with cross-platform portability, a wide range of useful features, and general purpose application, firmly in mind.

BRender takes the form of a C library, a set of C headers and library files that you build into your application. This lets you concentrate solely upon the task of describing scenes, modelling them and presenting them to the user. BRender takes care of all the hard work involved in positioning items in a scene, lighting them, applying special effects, and from a given camera specification, working out what's in the image, and rendering it (clipping, hidden surface removal, transparency, reflection, etc.).

The BRender C Library not only provides access to the rendering engine, but also facilities at each end of the process: describing a scene and processing the resulting image.
```

