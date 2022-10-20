# Open Samples

[![Generic badge](https://img.shields.io/badge/Patch%20Number-v1.05-blueviolet)](https://shields.io/)
[![Open Source Love svg3](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)


The Pumodi Sample Library started as a collection of samples from various hardware synthesizers of the 90's and late 80’s. Many of these sounds come from romplers or various wavetable rack mount synthesizers. These samples were created and provided free of charge to PCC students as a start to their own sample banks. As of 2022, we are reconfiguring it and releasing it as Open Samples, an open source sampling initiative.

As the years go by this sample pack will increase in size all the while remaining free or donation based. Open Samples, as an organization, will be sampling and releasing packs on our own as time permits. But the project itself is open for contribution if you have something you'd like to sample!

Also! If you download this and feel like making a demo song for one of the sound packs I would love to include some here so people unfamiliar with the instruments can get a sense for how they sound. Hit me up if you are interested.

- [Contents of the Pack](#contents-of-the-pack)
- [Downloading the Pack](#downloading-the-pack)
- [Contributing](#contributing)
  * [Ways to Contribute](#ways-to-contribute)
  * [Some quick sample requirements](#some-quick-sample-requirements)
- [Upcoming Sample Projects](#upcoming-sample-projects)
- [Latest Update](#latest-update)
- [Contributors & Special Thanks](#contributors-and-special-thanks)
- [LEGAL](#legal)

# Contents of the Pack
Each sample is provided as single note samples, multiple note multisamples in a single file, or chromatic samples where appropriate (such as drum sets). This should make it easy to implement into the sampler of your choice. Not all patches have been multisampled as the process was mostly automated.

### Definitions

The Library - This refers to the entire repository as a whole.

Sound Packs/Sample Packs - Refers to indiviual instruments or groups of instruments that have been sampled.

# Downloading the Pack

To download the entire library in it's current release form, please visit this link on Dropbox - https://www.dropbox.com/sh/ap4na48qx1w5mbg/AADaLCRcWaJ40I1VsePlqzd9a?dl=0

We experimented with doing releases on Github but the cost for the development cost is too much for an open source and free distribution model. You can, however, clone the repository to get bleeding edge versions of the files. If you do decide to clone, please consider doing a shallow clone as a full clone takes quite some time. I would recommend this command:

```git clone --depth 1 https://github.com/pumodi/open-samples.git```

If you do end up cloning from here, please consider contributing in some way, such as creating a patch file.

The dropbox release will be updated on a schedule that has yet to be defined, to ensure that it is up to date with the repository. This will require a QA and approval process so that we don't release something that is broken. Eventually, we will be adding a status ticker to the top of this readme to indicate if the Dropbox is up to date or not.

# Contributing

Anyone is welcome to contribute samples to this pack. Simnply fork the repo, add your samples, and submit a pull request. Pull requests will be reviewed as they are received.
Alternatively, email Pumodi with what you'd like to include and he can sort out uploading for you.

## Ways to Contribute

* Sample Instruments or Sounds
* Author Patch Files for various samplers
* Convert files into Wavetable format
* Create synth presets for us to sample on hardware or soft synths
* Research & write history documents on instruments that we've sampled
* Composer & Produce Demo Songs to exemplify the contents of a pack
* Create artwork for us to use in Marketing or on instrument pages
* Edit copy
* QA/QC instrument samples, patches, and prests

## Some quick sample requirements
* Samples must be .wav (minimum of 16-bit, 44.1khz but ideally 24-bit/48khz).
* If submitting a Kontakt instrument, ncw or monolith nki's would be fine. Please no nicnt libs.
* Other formats are allowed but must be reviewed by repo admin before merging.
* Demos should be limited to mp3 or ogg file format. Please no flac or wav as we need to manage repo size.
* If you can, please include a README.MD with details about your submission. See the AntiqueZither for an example.
* For more details, please see the [Contributor Guide](docs/CONTRIBUTING.md)

# Upcoming Sample Projects

| Instrument                      	| Status             	| GH Issue Link 	| Samplist in Charge 	|
|---------------------------------	|--------------------	|---------------	|--------------------	|
| Concert Percussion              	| Recorded           	|               	| Jeffrey Brice      	|
| Expand Solo Marching Percussion 	| Recorded           	|               	| Jeffrey Brice      	|
| Roland SC-88                    	| Pre-Pro            	|               	|                    	|
| Roland MKS-50 (Alpha Juno)      	| Sampling           	|               	| Jeffrey Brice      	|
| Roland Super JX MKS-70          	| Pre-Pro            	|               	|                    	|
| Korg M1R                        	| Pre-Pro            	|               	|                    	|
| Korg Wavestation A/D            	| Pre-Pro            	|               	|                    	|
| Korg U-220 + Sample Cards       	| Pre-Pro            	|               	|                    	|
| Kurzweill 1000PX                	| Pre-Pro            	|               	|                    	|
| Yamaha DX7S                     	| Pre-Pro            	|               	|                    	|
| Yamaha TX816 (4 ch)             	| Repairing Hardware 	|               	|                    	|
| Ensoniq Mirage                  	| Pre-Pro            	|               	|                    	|
| Commodore 64                    	| Pre-Pro            	|               	|                    	|
| Gameboy (DMG)                   	| Pre-Pro            	|               	|                    	|
| Yamaha MU1000                   	| Partial Sampling    |               	| Jackson Harris      |
| Toy Glockenspiel                 | Sampled             |                | Jackson Harris      |
| Torn Bongo                       | Sampled             |                | Jackson Harris      |
| Wood Flute                       | Sampled             |                | Jackson Harris      |
| Harmonica                        | Sampled             |                | Jackson Harris      |
| BambooXylophone                  | Sampled             |                | Jackson Harris      |

# Latest Update

### v1.06
* Reorganized folder structures for a number of packs.
* Added demo song for the X5DR ("Gemination") created by Tony Dickinson
* Added demo song for the Hard Drive Music Box ("Memory Box") created by krzyis

For the full changelog, [please go here](/docs/Changelog.md)


## Contributors and Special Thanks
* Social Media Preview Artwork - Jamphibious
* Jason Zaffary
* Jackson 'Xykrotik' Harris
* Jeffrey Brice

### PCC Recording Engineers
I would like to thank the following recording engineers:

* Jordan Laurent
* Jay “Dalton” Battin
* Joel Bocek, Lisa Bennett
* Alessandra Genovese
* and Michael Romay

For their help with the sampling process. Without their help playing single notes at a time on these instruments, this pack would not have been possible. They were the original samplists and recorded the source wavs of the X5DR, M1, K1R, and the JV2080.

For a full list of credits, [please vist the credits doc here.](/docs/Attribution.md)

# LEGAL
```
OPEN SAMPLES PERMISSIVE USE PUBLIC LICENSE
                    Version 1, October 2022

 Copyright (C) 2022 Jeffrey Brice <jeff@jeffbricemusic.com>

License Brief: Open Samples is provided free of charge and royalty free for you to use in your music production or other audio production purposes. You agree to not resell the content of the library as is or repackaged into another retail product. This license is meant to be as permissive as possible while preventing individuals from profiting off the library in an unmodified state.

            OPEN SAMPLES PERMISSIVE USE PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  1. SAMPLES, PATCHES, AND OTHER FILES WITH THE EXCEPTION OF MUSIC DEMOS (SEE CLAUSE 3) ARE DISTRIBUTED ROYALTY FREE AND FREE OF CHARGE. YOU MAY UTILIZE THE SAMPLES IN ANY COMMERCIAL OR NON-COMMERCIAL APPLICATION THAT INVOLVES MUSIC PRODUCTION, COMPOSITION, PERFORMANCE, OR OTHER PURPOSES THAT INVOLVE SOUND PLAYBACK.

  2. CONTENT OF THE LIBRARY ARE NOT TO BE REPACKAGED FOR SALE ON THEIR OWN OR AS PART OF SAMPLER INSTRUMENTS, SAMPLE PACKS, OR FOR ANY OTHER SAMPLE BASED RETAIL PURPOSE.

  2a. THE LIBRARY MAY BE REDSITRIBUTED AS IS IN A NON-COMMERCIAL FASHION.

  3. MUSIC DEMOS PROVIDED IN THE LIBRARY ARE 'ALL RIGHTS RESERVED' BY THEIR RESPECTIVE COMPOSERS.

  4. BY PROVIDING SAMPLES, PATCHES, OR OTHER FILES TO THE LIBRARY, COLLABORATORS ARE ASSIGNIGN OPEN SAMPLES A LICENSE TO DISTRIBUTE, COPY, AND MODIFY THE SUPPLIED CONTENT IN PERPETUITY, CONFORMING TO THE CLAUSES OUTLINED IN THIS LICENSE

  5. OPEN SAMPLES AND ASSOCIATED FILES ARE PROVIDED 'AS IS'. WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE LIBRARY OR THE USE OR OTHER DEALINGS WITH THE LIBRARY.
```

Notices:
If you end up using this pack, let me know! I'd love to hear what you make with it :)

## Contact
Jeffrey “Pumodi” Brice - Project Admin

jeff@jeffbricemusic.com
