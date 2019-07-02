# chips 2.0

A Chiptune style synthesizer and more for your KORG Minilogue XD / Prologue Synthesizers!

# As always, especially with the KORG user oscillators, these are to be used at your own risk!

### installation

Ensure you have the KORG minilogue/prologue sound librarian installed. Now, before you do anything else, **perform a full and complete backup of your synthesizer and save this to disk before continuing**. See the sound librarian manual for instructions on how to do this if required.

Next, select the USER OSCILLATORS tab on the librarian, and press Receive ALL to upload your existing user oscillators. Now, drag and drop the requisite file to an available slot in the librarian :
 - for Minilogue xd users, please use chips2.mnlgxdunit
 - for Prologue users, please use chips2.prlgunit

You should now see chips2 V2.00-1 listed in your user oscillators. Press "Send All" under USER OSC / FX to send all of your user oscillator / effects to your synthesizer

*please note if you do not do this correctly you may run the risk of losing data. As always, backup, backup, backup!*

#
### usage

Chips2 can be used as simply as a simple saw/pulse/triangle wave, and can have variable PWM applied, thus freeing your single LFO for vibrato or filter duty.

In addition, you can have a brief noise 'chiff' applied to the start of your sound, an octave chiff, and / or have chip-tune style arpeggios applied. This is especially interesting on the Minilogue XD as the arpeggiator currently isn't as fast as the built in arpeggiator on the Prologue.

With the Pulse wave selected, you can apply PWM, however with the Triangle wave selected, you can apply a Sync+(digital)RingMod effect, a sound usually unique to a C64 SID chip. With the Sawtooth wave selected, you can position a phase shifted copy of the sawtooth to get some interesting detuning and chorus effects.

But on top of this there are MANY options, all of which shall be listed here:

## Shape
**Pulse Wave** : Sets the amount of PWM to apply to the waveform. 

**Triangle Wave** : Shape set to 0 = pure triangle wave, anything else applies sync+ringmod, and increases the carrier frequency for the sync+ringmod sound.

**Sawtooth Wave** : Shape adjust the phase offset of a second sawtooth oscillator. 

*New for 2.0* - Shape can now be modulated with the external LFO when selecting "shape" as the target.


## Shift+Shape
**Pulse Wave** : Adjusts the PWM frequency. 

**Triangle Wave** : Adjusts the carrier frequency LFO amount.

**Sawtooth Wave** : Shape adjust the phase offset of a second sawtooth oscillator. Shift+Shape allows you to modulate this with the oscillators' built in LFO. 

* Hint : Try a slow 1-2hz modulation with the internal LFO and add the external LFO (via shape) at around 6 hz. You can approximate a string machine sound!


## Under the Edit menu:

**Fixed PW** : For pulse waves, this is a static Pulse width. Values are from 1-51 , which represent squarew to off. *This has no effect on the triangle wave.*

**Sync/Wave** : This is a *VERY* multi-functioned item, but it becomes clear fairly quickly :

*(**Value** : Function)*

**1** : Pulse wave selected, PWM and arpeggios can free-run (*arpeggios re-start once their cycle has completed in this mode only)

**2** : Pulse wave selected, PWM and arpeggios re-sync on new note ons

**3** : Pulse wave selected, PWM and arpeggios re-sync on new note ons, noise chiff added (this occurs for 1 cycle of the arpeggio rate regardless if arpeggios are enabled or not - you can adjust this with the Arp Rate value)

**4** : Pulse wave selected, PWM and arpeggios re-sync on new note ons, noise chiff added, very quick 'kick down' (pitch falls from 1 octave up down to the desired pitch very quickly)

**5** : Pulse wave selected, PWM and arpeggios re-sync on new note ons, noise chiff added, mostly quick 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**6** : Pulse wave selected, PWM and arpeggios re-sync on new note ons, noise chiff added, reasonably quick 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**7** : Pulse wave selected, PWM and arpeggios re-sync on new note ons, noise chiff added, medium 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**8** : Pulse wave selected, PWM and arpeggios re-sync on new note ons, noise chiff added, less medium 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**9** : Pulse wave selected, PWM and arpeggios re-sync on new note ons, noise chiff added, somewhat slow 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**10** : Pulse wave selected, PWM and arpeggios re-sync on new note ons, noise chiff added, slow 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**Values from 11 to 20 echo the parameters of 1-10, however are for triangle wave:**


**11** : Triangle wave selected, Sync+Ringmod and arpeggios can free-run  (*arpeggios re-start once their cycle has completed in this mode only)

**12** : Triangle wave selected, Sync+Ringmod and arpeggios re-sync on new note ons

**13** : Triangle wave selected, Sync+Ringmod and arpeggios re-sync on new note ons, noise chiff added (this occurs for 1 cycle of the arpeggio rate regardless if arpeggios are enabled or not - you can adjust this with the Arp Rate value)

**14** : Triangle wave selected, Sync+Ringmod and arpeggios re-sync on new note ons, noise chiff added, very quick 'kick down' (pitch falls from 1 octave up down to the desired pitch very quickly)

**15** : Triangle wave selected, Sync+Ringmod and arpeggios re-sync on new note ons, noise chiff added, mostly quick 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**16** : Triangle wave selected, Sync+Ringmod and arpeggios re-sync on new note ons, noise chiff added, reasonably quick 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**17** : Triangle wave selected, Sync+Ringmod and arpeggios re-sync on new note ons, noise chiff added, medium 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**18** : Triangle wave selected, Sync+Ringmod and arpeggios re-sync on new note ons, noise chiff added, less medium 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**19** : Triangle wave selected, Sync+Ringmod and arpeggios re-sync on new note ons, noise chiff added, somewhat slow 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**20** : Triangle wave selected, Sync+Ringmod and arpeggios re-sync on new note ons, noise chiff added, slow 'kick down' (pitch falls from 1 octave up down to the desired pitch )


**21** : Sawtooth wave selected, phase-shift and arpeggios can free-run  (*arpeggios re-start once their cycle has completed in this mode only)

**22** : Sawtooth wave selected, phase-shift and arpeggios re-sync on new note ons

**23** : Sawtooth wave selected, phase-shift and arpeggios re-sync on new note ons, noise chiff added (this occurs for 1 cycle of the arpeggio rate regardless if arpeggios are enabled or not - you can adjust this with the Arp Rate value)

**24** : Sawtooth wave selected, phase-shift and arpeggios re-sync on new note ons, noise chiff added, very quick 'kick down' (pitch falls from 1 octave up down to the desired pitch very quickly)

**25** : Sawtooth wave selected, phase-shift and arpeggios re-sync on new note ons, noise chiff added, mostly quick 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**26** : Sawtooth wave selected, phase-shift and arpeggios re-sync on new note ons, noise chiff added, reasonably quick 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**27** : Sawtooth wave selected, phase-shift and arpeggios re-sync on new note ons, noise chiff added, medium 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**28** : Sawtooth wave selected, phase-shift and arpeggios re-sync on new note ons, noise chiff added, less medium 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**29** : Sawtooth wave selected, phase-shift and arpeggios re-sync on new note ons, noise chiff added, somewhat slow 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**30** : Sawtooth wave selected, phase-shift and arpeggios re-sync on new note ons, noise chiff added, slow 'kick down' (pitch falls from 1 octave up down to the desired pitch )

**31-60** : These mirror 01 to 30, but instead of noise chiff you get a +1 octave chiff.


**61** : 4 bit Triangle waveform
**62** : 4 bit Triangle waveform with noise chiff
**63** : 4 bit Triangle waveform with octave chiff

4 bit triangle modes can be used individually with the Shape parameter set to 0, or with it turned beyond zero, you may now have the 4 bit triangle in the Left side, and a Pulse / PWM oscillator on the right!

**64** : With shape set to 0, pitched LFSR noise generator.

This one is also double functioned. Set the shape to > 0, and chiptune-style drums are now mapped in the left hand mostly using the General MIDI standard for kick drums, snare drums, 3x toms and hi-hats. In addition a 'cymbal' type sound is assigned between the kick and snare (so as to avoid wasting some space by placing it where it "should" be). These drums are tuneable via shift+shape. Note here as well the notes above the drums - the right hand, now have the PWM oscillator (2 octaves shifted down). This allows you to have drums mixed with bass / leads. Note that since shift+shape is tuning the drums, the PWM rate is now fixed in this mode.


*This isn't optimal (a couple more options would have been better) but it does work, and is pretty quick to use / figure out*

**ResyncOffset** : This sets the absolute starting position of the LFO for PWM / Sync+Ringmod / phase shift LFO. This only applies when the Sync value is not 1 or 11 (LFO sync must be on). This allows you to specify what pulse width / Sync/Ringmod frequency / phase shift to start with.

**Arp Type** : Allows you to pick from **11** different arpeggio types:

1 : No arpeggio

2 : 2 notes : Root and 5'th

3 : 2 notes, Root and Octave

4 : 3 notes, Sus4 (C F G)

5 : 3 notes, Major (C E G)

6 : 3 notes, Minor (C D# G)

7 : 3 notes, sus 2 (C D G)

*new for version 2.0:*

8 : 4 notes, maj7 (C E G B)

9 : 4 notes, maj7dominant (C E G A#)

10 : 4 notes, minor 7 (c D# g A#)

11 : 4 notes, maj9 (C D E G)

12 : 4 notes, min9 (C D D# G)


**Arp Rate** : Allows you to chose the rate at which the arpeggios *and the chiffs* are updated at.

1 : 60hz

2 : 55hz

3 : 50hz

4 : 30 hz

5 : 25 hz

6 : 15 hz

7 : 10 hz

** Arp Inv ** : Allows you to chose different chord inversions for the arpeggios

#### Play around with the settings, there are many but become pretty clear fairly quickly.



#

 *All product names, trademarks and registered trademarks are property of their respective owners.*
