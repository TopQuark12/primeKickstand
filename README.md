# HP Prime kickstand and protective cover

![Photo](Photos/Stand.JPG?raw=true "Glam shot")

This repository contains the design and mesh files for a kickstand integrated into a protective cover that slides onto the HP Prime calculator.  

The design is optimised so that it can be easily printable on a FDM 3D printer without supports. 

## Print Instructions

The design consists of the sliding cover, and the kickstand. The Mesh folder contains the STL files oriented in the way it should be printed. 

There are two versions of the kickstand mesh files, the "vertical" version optimised for better surface finish, and the "no support" version. 

The "vertical" version has support structures built into the design, so that no additional support structures need to be add on in the slicer software. This version prints the stand in a vertical position, so that the surface finish matches that of the cover.

The "no support" version prints the stand lying flat, so that supports are not needed. This also allows users who wish to print vertically and add support structure themselves to do so. 

## Assembly Instructions

The stand attaches to the slide cover via a hinge mechanism. The design intends for a 1.75mm plastic filament (the same filament used for most FDM 3D printers) to be inserted into the axis of rotation to form the hinge. 

Depending on the tollerance of the 3D printer used, the holes on the sliding cover and the stand may need to be enlarged with a drill bit with diameter of 1.8mm - 2.0mm.

To increase friction between the kickstand / cover assembly and the surface for which the calculator stand / lay on top of, 1mm thick, 10mm wide EVA foam tape is applied to 3 locations of the kickstand / cover assembly where it contacts the surface below:
- The bottom curved surface of the cover 
- The bottom of the stand (for added friction in the standing up position)
- The four protrusions of the stand at the hinge (for added friction in the lying flat position)  

You can refer to Photos/Cover.JPG for an illustration.

## Usage

The cover slides onto both sides of the HP Prime, like the original cover that came with the calculator. 

The kickstand can be folded flat for storage or when the calculator is used flat on a table. A protrusion on the cover retains the kickstand with a satisfying snap.  

In testing, the calculator is stable during normal operation in either the standing up position and the folded flat position. 

## Further modifications

I am pretty done with this little project. I spent two days of holidays to refine this thing to the point where I'm happy with it. 

Source files in the native fusion 360 format and standard STEP format is provided for further modifications. 

I have to admit while I'm happy with the end result, I am not proud of the absolute mess of operations used to construct the 3D model. This project turned from a quick hack into something I printed 10-20 versions of. Changing certain features of the CAD model might cause the model to self destruct and your computer to explode. You've been warned, here be dragons. 

## Rant 

A great deal of wasted plastic (~1 kg) and Lunar New Year holiday was wasted to design and iterate this bloddy thing, because the brilliant engineers / designers of the Prime calculator decided to install the screen upside down, so that the screen is barely legible when the calculator lays flat, WHY!? 

Even with the Prime standing up, the text on the screen is blury because they decided to dither the edges of the text. This obviously took processing power, memory, storage and actual effort to implement. WHY? 
