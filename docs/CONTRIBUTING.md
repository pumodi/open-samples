# Open Samples - Sample Pack Contributor Guide

This is a brief guide to submitting sample packs and music demos to the Open Samples Repo. Please read through it before committing to the repo so as to not have your commits rejected. Many things listed here can be omitted or worked around but please reach out to Jeffrey Brice to discuss your plans before you do so.

## File Specifications

The only file type we can accept for Raw Samples is *Wav*. Simply put, we need uncompressed and easy to modify files. Other formats create issues in a number of ways. The big goal here is compatibility and Wav is mostly universal usable. In situations where it is not, it's the easiest to convert to another format.

Required Specs:

* Sample rate of 44.1khz - 48khz. We do not accept sample rates higher than that.
* Bit-Depth of 16 or 24 bits. 32 bit files are not useful for our purposes
* Mono or Stereo files are accepted. No multichannel or polywavs please.
* We are currently creating guidelines for embedded metadata. For the time being, please do not include BWF metadata tags.

## Samplers and Playback Engines Supported

We aim to support as many sampler formats as possible. We will not necessarily create a patch for every format, though you are welcome to submit a patch for a specific patch!

* Kontakt
* Decent Sampler
* Ableton Sampler/Simpler
* Logic Sampler (Previously known as EXS24)
* Battery
* Reasamplomatic
* Soundfont (Utilizing Sforzando)

We would love to support the following but need someone on the team who both owns it and is familiar with it. If this is you and you're interested in volunteering some time, please reach out!

* UVI Falcon

In addition we are also supporting wav files in the following formats.

* Wave Tables (for synths like Phase Plant, Serum, etc): If you plan to submit WaveTable, please be sure to do your research so that it is done correctly. Incorrectly done WaveTables don't sound as expected.
* Hardware Synth Patch Files: Ideally for synths that we also have samples for.
* Impulse Responses: We will be taking Impulse Response files in certain circumstances. They will need to be vetted and approved by the maintainer team before being published to the repo.


## Directory/File Structure

When submitting a pack of sounds, please follow this standard directory structure.

Sound Name

|-> Samples: For samples that have been edited and cleaned. Ready to implement.

|--> Sample Sub-Directories: If it makes sense to store your sample in multi sub directories (i.e. different instruments for an orchestral section) do so here.

|-> Samples_RAW: Raw samples that have been cut down to sample format but are otherwise not ready for implementation. Please try to avoid supplying RAW samples.

|-> Instruments: Patch files to load into specific VST's. Can also be called Patches or whatever file format you are supplying. Do note that other file formats may be added eventually. If you only supply one patch, such as one .nki file, you can forgo this folder.

|--> Sub-Instrument Patches: If your pack requires sub-directories for instruments please place them here.

|-> img: For storing images of the thing you have sampled or wallpapers/other images to be displayed in the VST. You may also supply marketing images if you wish.

|-> Demos: For storing demos of the pack, in mp3 format. You do not have to supply a demo when submitting a pack. At some point in the future, demos will be created for each pack in the repo.

|-> README.md: You should include a readme to display info about your pack on the repo. Treat this as an ad page that lists included files, specs, etc.

|-> Docs: If you want to include pdfs or other docs relevant to your pack, please include them here.

## Sampling Depth

In general, we do not want to restrict what you sample or how you sample it. That being said, a few guidelines should be followed for the sake of not taxing the resources of the Open Samples team or the repo itself. The Open Samples team will endevaour to make patches for as many formats as is feasible. Multi-Sampled or Deep Sampled instruments will be much harder for the team to achieve that goal. While they are appreciated we just don't have the resources to build and test something on that scale. If you go through the effort to Multi or Deep Sample an instrument, please take the time to make a patch or playable version yourself. Working with multi-samples is incredibly time consuming and one of the goals of Open Samples is to provide people with a playable version on top of the samples themselves.

### What does Open Samples Consider as Multi or Deep Sampled

In general, it's a combination of things. Following the following guidelines will help avoid this issue.

Depth Comes from Round Robins and Velocity Layers -

Round Robins (RR): Keep round robin samples to a maximum of 6.

Velocity Layers: We all appreciate detail but please keep them to a maximum of 12.

Multi Sampling comes from -

Semi-tone Distance: By this we mean how big is the gap between notes you've sampled as you go up in register. In a perfect world we would sample every note chromatically but this poses time issues. Make a judgement call when deciding how far apart the notes you sample should be. For our purposes, aim to sample anywhere from 1 note per octave to 3 notes per octave.

### Multi-Sampling and Percussion
Percussion, specifically non-pitched/non-chromatic percussion, is a bit of a unique case. Often different sounds are created by playing the instrument differently or just by the number of instruments included (i.e. a drumset). In these cases, we forgoe the multi-sampling recommendations and focus primarily on the Depth concerns. This also goes from percussion created from synthesizers or romplers.

## Sampling Questions

If, after reading this guide, you still have questions or concerns please don't hesitate to reach out to a maintainer of the repo or other member of the team for advice or guidance. We're here to help!

# Music Demo Contributor Guide

A big component of any sample library is demos showing what it can sound like. Open Samples is looking for composers and producers to craft tracks utilizing the packs provided throughtout the repo. We would love to hear what you do with the samples and don't want to restrict you creatively. If you are considering creating a track to submit please adhere to the following requirements.

* File format: MP3 320kbps CBR
* Length: At least 30 seconds, no longer than 3 minutes
* Instrument Requirements: You are allowed to use any instruments, tools, plugins, etc to make your track. However, you must feature or focus on the instruments from the pack you are creating a demo for. Ideally, you can also supply a 'Dry' version of your track that only has the instruments from the pack without processing.
* Style/Genre/Etc: There are otherwise no other restrictions. Go wild and make something cool! Just remember to follow our code of conduct.

Lastly, we will likely be creating a playlist somewhere to show off the music that's been created utilizing Open Samples. We're not exactly sure where just yet as we don't want it to be a revenue earning platform. We may use the Scritch Editor to create a page on github.io where people can come listen.

If you have been contracted by the Open Samples team to create a track for the repo, the above guidelines will still apply to you. Any differences in your brief will supercede anything you see listed here.

# Licensing

We are working on a full, legally vetted license for the pack. In the mean time, this paragraph is meant to demonstrate our goals with the license but should not be considered legally binding for the time being.

By providing Open Samples with a Sample Pack or a Demo song, you are giving the owners and operators of the repository (Open Samples) a non-exclusive, perpetual license to use the samples or demos within the context of or in advertisement of the repo. You allow Open Samples to distribute the samples or demos provided as long as the repo maintains its open source status. You also provide a license for anyone using the samples provided in the repo to use them unhindered, except in the case of redistribution.

You otherwise transfer no rights and maintain full ownership of your samples and music.

A more specific license will be crafted shortly.

# FAQ

As of now there are no Frequently Asked Questions!
