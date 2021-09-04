---
title: "Adding Libraries to OrCad Capture"
date: 2021-09-04
categories:
  - articles
tags:
  - circuits
  - spice
---


Do you have some `.lib` and model files and can't make them work in an OrCad simulation? I sure had this problem before, and before going crazy on stack exchange, there are a couple of simple steps that usually work. 

1. Download the models. I'm guessing that if you're creating your own models, you don't need to read this. So, find the models (`.lib`, `.sch`, etc. files ) and download them!

2. Put them in `.../Cadence/SPB_16.6[in my case, this may change]/tools/pspice/library` then double click the `.lib` file (or open it via File/Open/library in the dropdown menu). Then click `File > Export To Capture Part Library...` and choose `.../tools/capture/library` (**not the same folder**) or any subfolder like `.../tools/capture/library/pspice`  as destination; this will create the .olb file.

3. Load the library into the schematic: On the parts menu find the "add library" button and point it to the `.olb` file. 

4. If you try to simulate it and it doesn't work, go to the simulation profile, `Configuration Files` tab, chose "library" under "Category", browse and point to the `.lib` file and finally click "Add as Global".

I don't know if these steps are something obvious, but I remember having to scavenge some forum posts when I first encountered this problem.