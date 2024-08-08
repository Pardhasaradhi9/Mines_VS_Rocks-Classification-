# Mines_VS_Rocks-Classification
## This is an ML-Classification Problem where the model is able to detect even the suttle difference between a rock and mine. 

# Inspiration:
### I recently re-watched one of my favourite telugu movie "Ghazi" which is a movie related to India's first underwater war. Cut short the main turning point of this movie is when the submarine is damaged by mine due to the fail to distinguish between a mine and a rock. I know this is 2024 all those problems are sorted and even better measures are in practice but at that moment i thought let's create a classification model which can solve this issue and searched the internet for related data sets--found one and this the project.
--------
# About the Dataset:
### - The data set is collected from [mines_vs_rocks](https://archive.ics.uci.edu/dataset/151/connectionist+bench+sonar+mines+vs+rocks)
### - The file "sonar.mines" contains 111 patterns obtained by bouncing sonar signals off a metal cylinder at various angles and under various conditions.  The file "sonar.rocks" contains 97 patterns obtained from rocks under similar conditions.  The transmitted sonar signal is a frequency-modulated chirp, rising in frequency.  The data set contains signals obtained from a variety of different aspect angles, spanning 90 degrees for the cylinder and 180 degrees for the rock.

### - Each pattern is a set of 60 numbers in the range 0.0 to 1.0.  Each number represents the energy within a particular frequency band, integrated over a certain period of time.  The integration aperture for higher frequencies occur later in time, since these frequencies are transmitted later during the chirp.

### - The label associated with each record contains the letter "R" if the object is a rock and "M" if it is a mine (metal cylinder).  The numbers in the labels are in increasing order of aspect angle, but they do not encode the angle directly.
----------
# Problem Statement
  The task is to train a network to discriminate between sonar signals bounced off a metal cylinder(mines) and those bounced off a roughly cylindrical rock.

## Breakdown:
### Classification:
  This is a machine learning task where the goal is to assign data points to a specific category. In this case, the categories are "mine" and "rock".
### Sonar signals:
  These are sound waves used underwater for navigation and object detection.
### Metal cylinder(mines) vs. rock:
  The network needs to learn the subtle differences in the way sonar signals bounce off these two different materials, based on the 60 frequency band readings.
