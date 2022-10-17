#FlipperZero Custom Animations by DoobTheGoober -Discord (CharlesTheGreat)

# Quick Peeks (pictures)
 - note: When taking screenshots/recording I was on unleashed firmware.
         As to why my top display bar is showing. If you wish to remove the bar on top of the flipper display,
         I would advise going to RogueMaster firmware.
         
• Scream

![Scream_Kill](https://user-images.githubusercontent.com/27988707/196075454-2f1a51d8-8f40-4edd-9d5c-1d291ba3d3f8.jpeg)

• Pipboy
![Pipboy](https://user-images.githubusercontent.com/27988707/196081391-6b97c65e-2f10-4025-959c-5c98339c1e92.png)

• Koko the Clown
![Koko](https://user-images.githubusercontent.com/27988707/196081516-6107540a-eb13-485b-ae50-877bfeaad82f.png)

• Steroids Chicken
![ChickenSteroids](https://user-images.githubusercontent.com/27988707/196082930-64c5b906-22e1-48a9-9011-0930c1afa721.png)

• King of the Hill
![KofH](https://user-images.githubusercontent.com/27988707/196082986-a4793329-291f-45b5-9d8a-5903e0f49f02.png)

# Prerequisite
```
git clone https://github.com/flipperdevices/flipperzero-firmware
```

# How to Install (png files)
• Some folders only contain the png files for each frame, we need these to be
  a "bm" extension. So to do this, follow along.
  
  1. download the "ChickenOnSteroids" file for instance.
  1.5. Clone the official firmware repo above (in prerequisites)
  2. Ill then drag and drop the "chicken_128x64" (in this instance) file into the "\flipperzero-firmware\assets\dolphin\external"
   - The file location is in the repo we cloned above
   - After dropping the file in the folder, we will then run the "fbt" script in the repo to compile the animation.
  3. Now that the file is in the external folder, open powershell and cd into the flipperzero-firmware directory. ie
     ```
     cd Downloads/flipperzero-firmware
     ```
  4. run this command to compile your animation:
  ```
  ./fbt icons proto dolphin_internal dolphin_ext resources
  ```
  5. After successfully compiling, plug your flippers SD card into the computer.
   - your now compiled animations can now be found under
     "flipperzero-firmware\assets\resources\dolphin" folder
  6. Drag and drop your newly compiled animations folder onto your flippers SD\Dolphin folder.
  7. Edit the manifest to this text:
```
name: chicken_128x64
Min butthurt: 0
Max butthurt: 10
Min level: 1
Max level: 3
Weight: 3
```
  - "name" is the name of the animations folder. (change according of course)
  - "Max level" adjust to max level if on custom firmware. (ie. 30, 15 etc)
  - "Weight" the higher the weight the higher the chance the animation will show up before other animations.
  
  8. Save the file and eject. Plug your SD back into the flipper and reboot! All done!
 
• Otherwise, were the animation files (frames) contains the "bm" file extension. The install is easy
  1. Plug in your flippers SD card.
  2. Download the animations folders (that contains the "bm" file extensions!)
  3. Drag and drop the animation folder into the Flipper SD\Dolphin folder.
  4. Edit the manifest.txt in the dolphin folder of the SD and add this to the top.
```
name: <FOLDER_NAME>_128x64
Min butthurt: 0
Max butthurt: 10
Min level: 1
Max level: 3
Weight: 3
```
  - see step 7 above for help
 
 5. Save file, eject SD, put SD in flipper, and reboot! All done!

# Learn how to make animations for the flipperzero
https://github.com/skizzophrenic/Talking-Sasquach
  - Give thanks to Talking Sasquach for making the animation learning process easy!

# zip2animations
https://github.com/CharlesTheGreat77/zip2Animation
  - utility to assist in automating some of the tedious animation creation process
    for the flipper zero

# Honorable mentions
https://github.com/Kuronons/FZ_graphics

# special thanks
Special thanks to Majik -qqmajikpp#8995
  for pioneering the way for me.

### 💬 Contact Me 

![Gmail Badge](https://img.shields.io/badge/-doobthegoober@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white)

### 🚦 Stats

<a href="https://github.com/CharlesTheGreat77">
  <img src="https://github-readme-stats.vercel.app/api?username=CharlesTheGreat77&show_icons=true&hide=commits" />
</a>
<a href="https://github.com/CharlesTheGreat77">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CharlesTheGreat77&layout=compact" />
</a>

<p align="center"> 
  <img src="https://profile-counter.glitch.me/CharlesTheGreat77/count.svg" />
</p>
⭐️ From [Charles](https://github.com/CharlesTheGreat77)
