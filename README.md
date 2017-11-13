

# An Open, Labeled Dataset for Analysis and Assessment of Human Motion

This repository contains a dataset with acceleration and rotation data of 8 different body weight exercises from 26 different users. It contains raw sensor data as well as adaptively segmented and labeled instances of individual repetitions. All in all more than 11,000 individual repetitions. In the following, we give an overview onto the contained data.
The complete documentation is provided within our publication "An Open, Labeled Dataset for Analysis and Assessment of Human Motion", which can be found in the repositories root directory (documentation_rc_1.0.pdf). It gives insigths into the study design, the used sensor system, and the directory and file structure. The paper will be published by Springer within the proceedings of the MobiHealth conference 2017, taking place in Vienna, 14-16 November (http://mobihealth.name/).
Analysis results concerning exercises recognition and qualitative classification as well as information concerning the segmentation process can be found within "Qualitative assessment of recurrent human motion" (http://ieeexplore.ieee.org/document/8081218/).

The dataset is free to use for anyone, so if you use it please cite it :)


RELEASE 1.0
-----------------------------------------------------------------------
## Complete Documentation
- See documentation_rc_1.0.pdf, "An Open, Labeled Dataset for Analysis and Assessment of Human Motion"

## Deteiled segmentation approach
- See publication "Qualitative assessment of recurrent human motion": http://ieeexplore.ieee.org/document/8081218/

# Raw exercise data
Raw data is available for all of the 8 recorded exercises. 

## All in raw data contained exercises and their abbreviations
- Bicycle Crunch (bi)
- Crunches (cr)
- Jumping Jack (ha)
- Squats (kn)
- Lunges (lu)
- Mountain Climbers (mo)
- Push-Up (li)
- Russian Twist (ru)

## Already segmented and labeld exercises
All in all, we segmented 7,352 exercises repetitions out of the raw data files.
- Bicycle Crunch (bi)
- Crunches (cr)
- Jumping Jack (ha)
- Squats (kn)
- Lunges (lu)
- Mountain Climbers (mo)

## Labeling
- All exercises are labeled with a numeric value within the range of 1 (very good) till 5 (very bad). The labeling was conducted by an professional sports engineer and an ambitioned athlete on basis of video recordings, wich were taken for all exercises during the workout's conduction.

## Pending segmentation and labeling
- For the whole dataset, no Push-Ups were segmented (li) and labeled, only raw data is available.
- For the whole dataset, no Russian Twists were segmented (ru) and labeled, only raw data is available.
- The study participants 5 and 9 were not segmented and labeled because of preliminary recordings with different sensor setup, only raw data is available.
- Participant 19 was not segmented and labeled du to physical issues during the exercises - the workout was not finished.

-----------------------------------------------------------------------
