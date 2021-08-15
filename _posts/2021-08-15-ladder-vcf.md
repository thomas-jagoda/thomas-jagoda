---
title: "Ladder VCF"
date: 2021-08-15
categories:
  - circuits
tags:
  - circuits
  - schematic
---

This is my go at the classic transistor ladder VCF. The twist here is using a single 9V supply and trying to keep it as simple as possible. The response is linear with CV, and the resistor Rc must be chosen according to the expected control voltage range. The input stage is ommited, but voltage at the input should be adequatly small. The exact gain makeup value is left to viewers discretion, depending on the desired levels at the output. Simulations indicate that everything's working fine.


{% include figure image_path="/assets/images/ladder_filter.jpg" alt="ladder vcf" caption="The classic transistor ladder filter" %}

