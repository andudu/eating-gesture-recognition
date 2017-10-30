# Eating Gesture Recognition

The project is based on ongoing research project [MT-Diet](http://impact.asu.edu/MTDiet.html) at [iMPACT Lab](http://impact.asu.edu) arizona state university. This project was done as part of CSE 572 Data Mining course under [Prof. Ayan Banerjee](http://impact.asu.edu/ayan/).

This project is carried out in 5 phases as explained below.

## Phase 1 - Creating Dataset

For creating dataset we have recorded video of eating person with wristband sensors. We have used [Myo armband](https://www.myo.com/), wearable gesture control and motion control device for capturing motion activity.

The food is equally divided into four sections of a plate. The unit of eating actions is considered as one bite. The dataset was created consisting of 40 bites each with fork and spoon.

While start eating eating we did a unique gesture that can be easily identified in the accelerometer sensor so that later we can synchronize the time stamps of the video and the accelerometer data from the wristband.


## Phase 2 - Data annotation
In this phase we have annotated the collected raw data as eating or non-eating with the help of video recording. We have annoted frame numbers as starting of eating activity and ending of eating activity. We captured all these frames numbers in Annotation.txt   

## Phase 3 - Feature Extraction

## Phase 4 - Designing Classifier

## Phase 5 - Performance & Accuracy
