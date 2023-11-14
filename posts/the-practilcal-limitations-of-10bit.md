---
title: The red sensor and my partial understanding of it
date: 2023-08-31T21:08:20.787Z
tags:
  - post
---
The RED Komodo Sensor and my conceptual understanding of it.

As it produces a Raw R3D output, ISO is just an interpretation of the sensor data. So my belief is that the sensor has an optimal in-sensor lux range. By this, I mean that the sensor performs best when it receives a certain amount of photons between x-y. (This is the raw sensors’ dynamic range)

Whilst I don’t believe the raw data has what we conserve as dynamic range, the interpretation from the ISO component adds a dynamic range into the equation. I might be very wrong here and my understanding isn’t very good but I believe the sensor converts from a floating point to a 16-bit output.

This is where dynamic range allocation comes into place. As well as signal boosting. because when you do as RED says to use a higher ISO like 1600 in bright situations, you are reducing the amount of photons hitting the sensor. This naturally reduces clipping at a cost to the shadow section. As we boost the raw input data, we will have a greater noise floor.

The inverse is also true when using lower ‘ISOs’ to interpret darker scenes that we over-exposed to reduce the amount of naturally occurring photon noise.

What you are doing is bringing the sensor back to its sweet spot.

To conclude, the relocation of the middle grey point is a smart but hacky way to get the most out of the raw sensor dynamic range, using sensor jujutsu to utilise its weakness as a benefit.