# ringmod_sidechain
DAW Presets for doing Ring Modulation Sidechain

See the following videos for details:

https://youtu.be/PeUD20tGxKY

https://youtu.be/-jJ7Nl25NnY

https://youtu.be/NiS-1DKuoto

https://youtu.be/R6iOPs8Ol2o

https://youtu.be/OzLEwdcDXWo

Reaper threads:

https://forum.cockos.com/showthread.php?t=263999

https://forum.cockos.com/showthread.php?t=276028

Reason threads:

https://forum.reasontalk.com/viewtopic.php?p=601496

## Files

### Bitwig

#### [RM_sidechain.bwpreset](RM_sidechain.bwpreset)

Bitwig Grid FX implementation.

#### [RM_sidechain_v2.bwpreset](RM_sidechain_v2.bwpreset)

Bitwig Grid FX implementation. This version uses lower level modules that seems to work better. The Rectifier device in the other version appears to introduce some random latency causing it to not sum right and go over 0db in tests.

#### [Ring Mod Sidechain Grid FX.bwtemplate.zip](Ring%20Mod%20Sidechain%20Grid%20FX.bwtemplate.zip)

Bitwig example project/template that uses Grid FX.

#### [Ringmod Sidechain MXXX.bwtemplate.zip](Ringmod%20Sidechain%20MXXX.bwtemplate.zip)

Bitwig example project/template that uses MXXX instead of Grid FX. This is what I use, as it does not add any latency and bugs seen with Grid FX.

### Reaper

To install, in Reaper go to `Options -> Show Reaper resource path ...` and add the file in the subdirectory below.

#### [Ring Mod Sidechain](Ring%20Mod%20Sidechain)

Reaper JSFX implementation requiring an extra bus track. To install, add this file in the `Effects` subdirectory.

#### [Ring Mod Sidechain Without Extra Track](Ring%20Mod%20Sidechain%20Without%20Extra%20Track)

Reaper JSFX implementation without needing an extra bus track. To install, add this file in the `Effects` subdirectory.

#### [Ring Mod Sidechain JSFX.RTrackTemplate](Ring%20Mod%20Sidechain%20JSFX.RTrackTemplate)

Reaper track template using JSFX. This is the extra bus track. To install, add this file in the `TrackTemplates` subdirectory.

#### [Ring Mod Sidechain Melda.RTrackTemplate](Ring%20Mod%20Sidechain%20Melda.RTrackTemplate)

Reaper track template using Melda plugins. This is the extra bus track. To install, add this file in the `TrackTemplates` subdirectory.

#### [example projects.zip](example%20projects.zip)

Example Reaper projects using the above setups to understand the routing needed.
