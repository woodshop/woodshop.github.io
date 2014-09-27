---
layout: page
title: "Workshop Talks"
tags: [talks]
image:
  feature: pierce2.jpg
  credit: 
  creditlink: 
share: true
---

# Friday, October 10

## Scaleable Art: Open Source for Sound Art and Installation

### Spencer Topel

Over just the past five years, the Open-Source (OS) Hardware community has expanded into a multi-million dollar industry. The opportunities for integrating hardware/software OS have given rise to a new kind of inventor, but also provides opportunities for digital artists to explore previously costly or inaccessible projects, such as multi-computer installations, cluster computing for audio/video processing and sonification/visualization. This workshop will present the nuts and bolts of how to get started with OS Hardware/Software. 

## We Are Not Alone In the Universe: Spacebrew and Physical Computing to Connect Distant Spaces

### Joselyn McDonald

Do you love WebSockets? Do you hate WebSockets? Either way, we’re not going to be learning (directly) about WebSockets (so be calm). We’re going to be learning about Spacebrew!

Spacebrew is an open, dynamically re-routable software (WebSockets) toolkit for choreographing interactive spaces. In other words, Spacebrew is a simple way to connect interactive things to one another.  No matter what your ultimate programming desire is, you can utilize Spacebrew to quickly prototype physical and psychic* interaction through a user-friendly online node connection. Spacebrew uses WebSockets as the communication protocol for talk between clients and the server. Any client that can speak WebSockets can communicate with Spacebrew. We've run successful tests with node.js, C++ (using libwebsockets), Processing, Java, Python, and client-side javascript.

Once we get Spacebrew up and running, we’re going to look at CapSense libraries and conductive materials that allow for a myriad number of complicated and nuanced sensors embedded either in a physical space or in wearables.  By the end of the workshop, participants will understand how they could Spacebrew, an intuitive WebSockets toolkit, to trigger audio/ visual responses in distant spaces or vice versa, and additionally comprehend the fundamental usage of a CapSense library for allowing human touch or even mere human presence (do you know how conductive we are?!)  to trigger audio/ visual events in those spaces. It wouldn’t hurt to have an Arduino handy. [Link to Spacebrew github](https://github.com/Spacebrew/spacebrew).

## Digital raster scanning as audiovisual synthesis

### Alex Dupuis

The process of raster scanning, adapted from its analog television origins, offers a simple means of mapping between audio and video data. The flexibility afforded by this process allows for the creation of trans-modal feedback loops, as well as the application of effects from one domain to data originating in the other. Moreover, the distortions of the digital translation process can be exploited to create a wide array of new patterns, animations and sounds. Working in Max/MSP, I'll describe and implement an example of audiovisual raster scanning, discuss the considerations specific to a digital version, and demonstrate a number of the unique opportunities and by-products of the digital process.


## Light-Data Two Ways: Constructing Optical Sensors for Use in Analog and Digital Systems

### Carlos Dominguez

Carlos will give a tutorial on making a hybrid digital/analog system for reading visible light data and discuss how it can be used for installation and performance art. In collaboration with Alexander Dupuis, the system will be incorporated into a performance at the Workshop in the Woods.


# Saturday, October 11

## Principles of Auditory Scene Analysis for Audio Synthesis

### Kevin Woods

Understanding the perceptual organization of sound can aid creative synthesis. For example, why might two different sounds fuse together rather than being heard as distinct? What kinds of sounds grab your attention, and why? Issues like these are not fully understood, but what we do know might help us better predict the perceptual effect of sounds we want to make, or guess how sounds should be changed to get the effects we want. In addition to primary processes which are largely obligatory, our perception of auditory scenes is also heavily influenced by attention. So, an awareness of attentional dynamics may also inform creative audio synthesis. Prior work tended to approach auditory attention as allocated in a stationary way to sound sources with consistent features. However, recent work suggests that attention can also track a sound source as it changes over time, and that this moving locus of attention can influence the formation of auditory objects and aid in selection among similar sources.

## HKL•••XYZ: Moving from reciprocal space to real space in X-ray crystallography

### Daniel J Wilson

The workshop will be an introduction to the process of X-ray crystallography, widely used in structural biology (2014 is actually the UNESCO International Year of Crystallography), and an explanation of the process of molecular structure determination, which uses inverse Fourier transforms of information in reciprocal space to reveal real space information about the structure of a crystallized molecule.

The question of how to use the physical information about the crystals, both in reciprocal space as well as inverse Fourier transformed to real space, to create sonic representations of the molecule's structural information will be considered.

## Systems and Methods of Performative Synthesis: Considerations for Improvising with Code

### Scott Petersen

This workshop will provide the attendee with an introduction to several systems and methods for improvising with code, focussing specifically on the strengths and weaknesses of different approaches to live audio synthesis. The workshop will use the audio programming language SuperCollider for all examples, but the concepts are portable to other languages.

Key topics will include: data entry and interaction methods, communication protocols, language­specific goodies (UGens), one­liners, strengths and weaknesses of syntactic sugar, hardware considerations for real­time synthesis and more.

You may find it helpful to install SuperCollider before attending the workshop as example files, documentation and further reading will be provided beforehand.

## Archive BLASTing for Audio-Visual Synthesis

### Michael Casey

I will present Dartmouth's BLAST (Bregman Labs' Audio-viSual Transformation) plugins for real-time retrieval from big media archives. BLAST tools are compatible with widely-used platforms via standard plug-in frameworks such as Max/MSP/Jitter, PD, VST, AU, and LADSPA. I will give examples of non-repeating dynamic texture synthesis and sonic control of archive-generated film, and speculate on the critical inter-mediation that these new computational tools afford.

## Translating Visual Cues into the Auditory Domain

### DAAT

In this talk DAAT will discuss design choices and considerations for evoking visual imagery in the auditory domain within the context of 170 BPM dance music production. Topics discussed will include the historical, philosophical and practical usage of synthesis and sampling techniques in modern electronic dance music, and the parameterisation and manipulation of sampled sound.

## Electronic Images and Sound

### Le Révélateur

Sabrina anad Roger of Le Révélateur will discuss several aspects of their creative process, including the tools they use, inspirations, and relationships between images and music. Their talk will be accompanied by live performance and will conclude by kicking off Saturday night's AV Synth Jam.

# Sunday, October 12

## Autoencoding Musical Synthesizers

### Andy Sarroff

Autoencoders are neural networks that learn to reproduce their input at their output. They have an encoding stage where an input data space is transformed into a hidden representation, and a decoding stage where the output of the hidden representation is transformed to the original data space. The first part of the talk will cover basic principles of autoencoders, including designing the model's structure, using activation functions, connectedness, training, and regularization. The second part of the talk will discuss the application of autoencoders for musical sound synthesis, including design challenges, musical interfaces, and performability.

## Synthesis of realistic (and wildly unrealistic) sounding impulse responses from environmental statistics.

### James Traer

Every room is different and hence has a set of unique impulse responses associated with each possible source-listener orientation.  However, the percept of reverberation may be similar across a wide range of rooms and configurations therein.  This suggests that the perceptually important features of reverberation may be independent of the details of the fine-structure of the impulse response (determined by the exact configuration and properties of the room) and rather may depend more strongly on the bulk statistics of the impulse response time series (determined by features such as room size and average reflectance of all surfaces).  We have measured real-world impulse responses in over 200 real-world spaces, both indoor and outdoor, including rooms large and small.  We have measured the statistics of these impulse responses and by imposing these statistics on Gaussian random noise we can quickly and easily synthesize realistic sounding reverberation.  Moreover, if we set our synthesis algorithm to intentionally violate the statistics we have measured in the real-world, the resulting “reverberant” signal sounds noticeably synthetic and unnatural.  This implies that the human brain uses the statistics of real-world impulse responses to separate signal arriving at the ear into contributions from the sound source and echoes from environmental reverberation. 

## Animated GIFs, the Internet, and Art

### James Kerr

It’s hard to escape the animated GIF. Spend anytime surfing the internet, and you are bound to see more than a few. From their use in marketing to internet memes, the GIF has seen a renaissance within the last few years. But despite their ubiquity, many are exploring the medium as art. In this workshop, James will explain his process of making an animated GIF by creating a collaborative piece with those in attendance, which he will post online at its completion. Who knows, maybe it go viral! 

## Spirits in Objects: Problems, Philosophies, and Potential in Sound and Image

### Jodie Mack

JM will share historical gems from computerized experimental animation
history and lead discussions on the contemporary possibilities and
problems of A/V synthesis.
