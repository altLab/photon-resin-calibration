# photon-resin-calibration
Anycubic Photon - Files and method to quickly finde the best exposure settings for any resin or UV film

First release is ready for public testing here: 

Context video
https://www.youtube.com/watch?v=0fksIkSthl8

![photo_20180521_004205 1](https://user-images.githubusercontent.com/11083514/40287288-2fe8adcc-5ca4-11e8-8a80-86d8516df68a.jpg)

---

Reading the results
![image](https://user-images.githubusercontent.com/11083514/40270445-874d4e94-5b85-11e8-99b4-94fece56fad1.png)

This resin test by Tycho Pandelaar was run with the base exposure at 10s and the normal exposure at 3s

The photo shows the probable best setting for his resin would be 10s+3sx(3.5-1) = 17.5 seconds per layer
The minimum viable exposure is probably around 10+3x(1.5-1) = 11.5 

This means this resin exposure latitude is safe to assume to be around 15s to 41s, Use faster times only for thinner layers  

Another thing we can learn from the test is The minimum XY positive and negative details
Negative Space: 0.09mm
Positive Space: 0.08mm

----
![image](https://user-images.githubusercontent.com/11083514/40264048-e9b664de-5b13-11e8-9322-67906841a8fd.png)

This poor job of a test was my own, made with anycubic gree resin, was run with the base exposure and normal exposure at 2s

You can see that the minimum viable exposure for this resin (The first resin column to cure) is 2sx4 = 8s this is the setting i use for 2.5µ layers

The poor job in cleaning the resin excess makes it more less impossible to detect what are the other important settings :P


---
Kudos to @Reonarudo for finding what makes .photon files tick. Check his project to convert images into .photon files (here)[https://github.com/Reonarudo/pcb2photon]

Kudos to Toby1kanobi in the anycubic owners forum for translating and cleaning up the gcode file used to switch modes in the printer
