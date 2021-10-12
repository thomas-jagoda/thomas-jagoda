---
title: "Chico Fuzz"
date: 2021-10-12
categories:
  - circuits
tags:
  - circuits
  - schematic
  - fuzz
  - wah-wah
---

I recently was given a dead handmade fuzz (no schematics or any info whatsoever) for repairs. I drew its schematic and found it quite interesting and unusual, so I'll share it here. The input stage is a shunt-feedback common emitter with a little bit of emitter degeneration and the _fuzzy_ section at the end is based on the CD4049UB CMOS inverter. The weird part is it's middle "tone" section, which is a full Crybaby style wah-wah down to the component values. The classic circuit can be seen [here](https://www.experimentalistsanonymous.com/diy/Schematics/Filters%20Wahs%20and%20VCFs/60s%20and%2070s%20Wah%20Variations.pdf), and I found the specific 82k//4.7u combination in [this one](https://www.experimentalistsanonymous.com/diy/Schematics/Filters%20Wahs%20and%20VCFs/New%20Way%20Wah.gif). The pedal resides in a stompbox (interestingly covered by mirrors), so there is no wah pedal, just a potentiometer. Another unusual choice is the inductor used; in this circuit it is actually half of a small step-up transformer (maybe from an electric flyswatter?). I haven't measured it's inductance, as I didn't want to take it out of the PCB, but I guess it should be around the usual 500mH seen in the Crybaby. The end result is a very unique sounding fuzz.



{% include figure image_path="/assets/images/chico-fuzz-schem.jpg" alt="chico-fuzz" caption="The drawn schematic" %}



{% include figure image_path="/assets/images/chico-fuzz-box-trans.jpg" alt="stombpox" caption="Left: the cool mirror enclosure. Right: the small transformer used as an inductor." %}








