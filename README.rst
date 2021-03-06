OSAMC LV2 Plug-in Workshop
==========================

Documentation and code for a workshop on creating LV2 plug-ins by OSAMC
(https://osamc.de)

Recommended Reading Order
-------------------------

"My first LV2 plugin": SimpleGain
   Step by step instructions to create the SimpleGian plugin, based on the DPF framework
   https://github.com/osamc-lv2-workshop/lv2-workshop/blob/master/my-first-lv2-plugin.rst
   
Changing SimpleGain into SimpleSaw
   https://github.com/osamc-lv2-workshop/lv2-workshop/blob/master/simplesaw-plugin.rst   
   
MIDI input for SimpleSaw to create SimpleSynth
    (Step by step instructions may follow)
    https://github.com/osamc-lv2-workshop/simplesynth


Plug-in Frameworks
------------------

The DISTRHO Plugin Framework (DPF):
   https://github.com/DISTRHO/DPF

   DPF allows to create plug-ins in different formats with custom UIs using a
   simple C++ API. We are using this framework in this workshop to create our
   plug-ins.

A presentation by DPF's author falkTX:
   https://media.ccc.de/v/minilac16-ltsmakesomeplugins

WDL / IPlug (Oli Larkin Edition):
   https://github.com/olilarkin/wdl-ol

   A framework very similar to DPF, but orientated more towards developing for
   Windows and OS X (i.e. supports AU plug-ins)

A very good multi-part tutorial on developing plug-ins with WDL-OL:
   http://www.martin-finke.de/blog/tags/making_audio_plugins.html


General Programming, DSP and Synthesis
--------------------------------------

A blog with many articles on the different aspects of software synthesizers:
   http://www.earlevel.com/main/

   The WaveTable oscillator and ADSR envelope classes we are using in this
   workshop originate there.

A good tutorial on the basics of programming in C++:
    http://www.cplusplus.com/doc/tutorial/


LV2
---

A short introduction to what the LV2 standard tries to accomplish:
   http://lv2plug.in/pages/why-lv2.html

A Developer tutorial on creating LV2 plug-ins by using its C interface directly:
   http://lv2plug.in/book/

LV2 environment and paths:
    http://lv2plug.in/pages/filesystem-hierarchy-standard.html


GUI & Graphics
--------------

JKnobMan:
    https://www.g200kg.com/jp/software/knobman.html

    A Java-based creation tool for making image strips for animated knobs,
    sliders and switches.

Knob Gallery:
    https://www.g200kg.com/en/webknobman/gallery.php

    Knob Gallery is a free sharing space for ".knob" files created with
    JKnobMan or WebKnobMan.
