---
title: "Balancers"
date: 2021-08-15
categories:
  - circuits
tags:
  - circuits
  - schematic
---

## V1

A friend of mine asked me to make it possible to connect his guitar, bass and unbalanced whatnot to his new preamp/compressor that only has balanced inputs. So, here it is. Very simple stuff, no phase compensation. Ground can be connected or not to the XLR plug (leave unconnected for "ground lift").

{% include figure image_path="/assets/images/xlr.jpg" alt="xlr" caption="A very simple unbalanced to balanced converter" %}



## V2
So, it arised from my experimentations the need for my own unbalanced to balanced circuit, so here is its second incarnation. After checking, turns out the zener is actually 4v3 and not 4v7, but it shouldn't make a difference. 

{% include figure image_path="/assets/images/balancer.jpg" alt="balancer" caption="A more robust version of the balancer" %}


