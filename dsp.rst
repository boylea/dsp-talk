
Data Transformation Super Powers with Digital Signal Processing
===============================================================

Amy Boyle @amylouboyle

---------------------------------------

Digital Signal Processing = DSP

---------------------------------------

TOC
====
What is DSP?
When and why DSP?

---------------------------------------

What is DSP?
==================

bad definition: 
	Digital signal processing (DSP) is the mathematical manipulation of an information signal to modify or improve it in some way. It is characterized by the representation of discrete time, discrete frequency, or other discrete domain signals by a sequence of numbers or symbols and the processing of these signals.

But DSP is so broad, it is quite difficult to come up with a 1-2 sentence explanation that covers it and is comprehensible.

My definition:

    Take real-world continuous measurement, turn it into a discrete series of data points. Use an algorithm to manipulate the data samples to do cool things.

Still not super clear, so let's break it down.

---------------------------------------

What is a signal?
==================

A type of physical data that conveys information. A description of how one parameter depends on another parameter.

examples:
Sound - mention transducers : speakers, microphones
Light
Temperature
vibration
heart beats
<something weird>

continuous signals have an infinite range of values. Most signals in nature are continuous.

---------------------------------------

Digital

We work with computers so we need to represent them somehow. In order to be able to hold the data in digital memory we need to discretize the signals.

For recorded signals, this is done by a process called sampling. We record a measurement in some number of finite steps at finite points in time or space.

e.g.
Sound -> voltage/time
Light -> intensity/space
Temp -> degrees/time - or space
Text -> characters/location???

Talk about sampling and quantization here?
Nyquist, correct precision range for quantization?

---------------------------------------

DSP
====

Anytime you do anything to that digital signal to analyze or manipulate it. 

---------------------------------------

Trivial Example
===============

signal + 1? meaning?

signal averaging?

---------------------------------------

Mastering all of DSP is an unreasonable goal. So learn the general concepts that apply to the field as a whole, figure out what area to focus on, and learn the specialized techniques for that area.

---------------------------------------

All signals are composed of sine waves

---------------------------------------
	
Sound Example
=============
<show times series of plot and play audio with cursor>

---------------------------------------

Talk about domains?

---------------------------------------

Let's talk about the DFT/FFT
============================

Transform audio from time to frequency domain (use tones first?)

think of a metaphor as to why you don't need to understand the FFT?

---------------------------------------

Image Example
==============

<show picture, its 2D representation, you can flatten this too, and it's just like the last example>

* spatial domain, instead of time.

---------------------------------------

Compression
===========

* JPEG

---------------------------------------

Caveats
=======

Although closely related, the distinction between the acquired signal and the underlying process is key to many DSP techniques. 

* Coin flip example

Something about probability describing the underlying process... can I give a more complex example?

Talk about normality?
