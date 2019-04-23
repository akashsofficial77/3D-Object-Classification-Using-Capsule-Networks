
# 3D-Object-Image-Generation-For-Capsule-Networks
## My contribution in short

### Week 1
- Installed Maya on Day 1
- Explored Maya and learnt its functionality using tutorials given by Prof Nik Brown and Youtube.
- Built basic objects like cubes, cones , etc
- Rotated them using python scripting
- Created camera and lights to get understanding of how shadows work
- Tried to manually capture images from camera view on single axis

### Week 2
- Started to work on the developing the scripts
- Worked on understanding the scripts developed by other teammates
- Fine tuned the parameters of "[Snapshot Script](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/Snapshot_Script.py)" to get good quality images
- The problems we faced was quality of images and the noise that came with taking snapshots
- We figured it out that by getting render image- we can maintain the quality of images.
- The image we obtained looked like following:
![Sword_Capture_1](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/image10_10_YX.jpg)
![Sword_Capture_2](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/image160_190_YX.jpg)

### Week 3
- We needed shadows - so , we had to create a new [environment](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/BestScene.mb).
- The above environment consists of a camera, lights, plane and final [script](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/Final_Script.py)
- This script rotates the camera by 45 degrees on each axis, it generates 540 images per object with shadows.
- While few of us were working on improving the environment and finalizing the best script , I was collecting the objects
- Collecting objects seems like downloading stuff from internet, but it isn't as easy as it looks; takes too much time to get relevant objects.
- I managed to collect 42 objects and developed major categories of electronics and food.

### Week 4
- The object which were collected came in all shapes,colors and sizes - which were exactly not suitable to our environment
- I developed a practice of importing the objects, merging all the meshes , rescaling , applying shaders and making them point towards the person on laptop before actually importing it to our environment.
![Importing Raw Object](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/Capture_1.png)
![](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/Capture_2.png)
- Optimizing it before actually getting to run script on it consumed much time
- Images after optimization looked like:
![](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/Capture_3.PNG)
![](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/Capture_4.PNG)
- Images generated after running the script looked like:
![Image Generation](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/Gorilla.PNG)

### Week 5
- Cumulatively, we collected almost 200 objects together and built different categories.
- While, few of us moved to working on database and website, i still continued dealing with objects and image generation.
- I took the task of checking all the images generated by others and making corrections wherever required.
- Handling so many images and naming all of them was becoming difficult time to time
- We had to run the script again to rename the images if there was any error.
- It took almost 5-6 minutes for full generation of images
- We discovered that we can rename all images in Mac but not in windows.
- I found out a [software](https://www.bulkrenameutility.co.uk/Main_Intro.php)- which helped us rename , add suffix/prefix and replace names of files in bulk, which increased our productivity by 10 times
- Now, as we were doing good with white background and black shaded objects, we decided to add a creative edge to our work by creating [environment](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/Black_Environment.mb) which helped us to generate white-shaded images in black background.
- We also created limited objects without shadows as well.
![Goalpost_Black](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/Sports_Soccer_Goaplost_X0_Y0_Z0_No_White_Black.png)
![Table_Black](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/Sports_Tennis_TennisTable_X0_Y135_Z315_No_White_Black.png)
- Also , I created image dataset with real colored or textured objects.
![Rose_Color](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/Rose_Color_X0_Y45_Z45.png)
![Rose_Color1](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/Rose_Color_X0_Y90_Z270.png)
- We came up with naming convention such that by looking at it, one can know catergory, sub-category, angles, shaders and backgrounds.
![Naming_Convention](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/NamingConvention.PNG)

#### This is the [link](https://drive.google.com/drive/u/1/folders/1c7wjh__WL8cVYCPE3ebdM8oSq1riKts6) to our final dataset
#### This is the [link](https://drive.google.com/drive/u/1/folders/1pY7DqCnL1EDFS9PC10NZXp6IfNobYaeZ) to the objects that i collected.

![Final Schema](https://github.com/nikunjlad/3D-Object-Classification-Using-Capsule-Networks/blob/smit/Maya3D-Images-Dataset/Smit/FInal%20Schema.PNG)

We would really appreaciate your feedback and support .
We are planning to continue our work in future as well.
