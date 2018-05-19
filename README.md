# photon-resin-calibration
Anycubic Photon - Files and method to quickly finde the best exposure settings for any resin or UV film

First walktrough video
https://www.youtube.com/watch?v=0fksIkSthl8

Reading the results
![image](https://user-images.githubusercontent.com/11083514/40264048-e9b664de-5b13-11e8-9322-67906841a8fd.png)

![image](https://user-images.githubusercontent.com/11083514/40270445-874d4e94-5b85-11e8-99b4-94fece56fad1.png)

This resin test by Tycho Pandelaar was run with the base exposure at 10s and the normal exposure at 3s

The photo shows the porbable best setting for his resin would be 10s+(3sx3.5) = 40.5 seconds per layer
The minimum viable exposure is probably around 10+(3x1.5) = 14.5 

This means this resin exposure latitude is safe to assume to be around 15s to 41s, Use faster times only for thinner layers  

Another thing we can learn from the test is The minimum XY positive and negative details
Negative Space: 0.09mm
Positive Space: 0.08mm


---
Kudos to @Reonarudo for finding what makes .photon files tick. Check his project to convert images into .photon files (here)[https://github.com/Reonarudo/pcb2photon]

Kudos to Toby1kanobi in the anycubic owners forum for translating and cleaning up the gcode file used to switch modes in the printer
