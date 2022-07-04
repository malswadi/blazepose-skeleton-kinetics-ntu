#  Using BlazePose on Spatial Temporal Graph Convolutional Networks for Action Recognition

This is the project repository for the research study *Using BlazePose on Spatial Temporal Graph Convolutional Networks for Action Recognition* presented by Motasem S. Alsawadi, Ghulam Muhammad and Miguel Rio.

(In reviewing process for publication)

<p align="center">
<img src="https://user-images.githubusercontent.com/52717252/162593347-a8a62eb6-a96a-45fb-bc6c-cc51671dfebe.gif"
</p>
<p align="center">
BlazePose skeleton data from Kinetics dataset class 'playing violin'.
</p>

## Contents
* Download Kinetics BlazePose Skeleton Dataset
* Download NTU-RGB+D BlazePose Skeleton Dataset
* Storage info
* Citation
* Acknowledgements

## 1. Download Kinetics BlazePose Skeleton Dataset

The Deepmind [Kinetics](https://www.deepmind.com/open-source/kinetics) human action dataset is the largest set with unconstrained action recognition samples. 
The 306,245 videos provided by the Kinetics dataset are obtained from YouTube classified into 400 different action classes. Due to the variability of the duration of each clip, a fixed duration of 300 frames has been proposed. Therefore, if any video clip has less than 300 frames, we repeat the initial frames until reach the amount needed. Otherwise, if the video clip exceeds the frame number, we ramdomly deleted the exceeding frames. An independent JSON file has been exported for each video sample. The Kinetics BlazePose skeleton dataset can be downloaded [here](https://drive.google.com/file/d/1K953rOULG7cPEaw6MRL_0RKEG7cuIJjd/view?usp=sharing).

## 2. Download NTU-RGB+D BlazePose Skeleton Dataset
The [NTU-RGB+D](https://rose1.ntu.edu.sg/dataset/actionRecognition/) dataset provides a total of 56,880 action clips performing 60 different actions classified into three major groups: daily actions, health-related actions, and mutual actions. Forty participants performed the test action samples. Each sample has been captured with 3 different cameras simultaneously located at the same height but different angles. We set the duration of the video clips to 300 frames using the method explain in Section 1. The NTU-RGB+D BlazePose Skeleton dataset can be downloaded [here](https://drive.google.com/file/d/1K5nnPiF2-xmtZNwUF3yVvbSlnMf97AY-/view?usp=sharing).
## 3. Storage info
The Kinetics and NTU-RGB+D BlazePose skeleton dataset are provided as .zip format. 

#### Kinetics
The compressed file size of the Kinetics BlazePose Skeleton dataset is 6.7 GB. On the other hand, the uncompressed format has a size of 21.6 GB of storage.

#### NTU-RGB+D
The compressed file size of the NTU-RGB+D BlazePose Skeleton dataset is 1.62 GB. When uncompressed, this dataset has a size of 5.47 GB of storage.

## Citation
When our paper is published, we will include the citation information in this section.

## Acknowledgements
We utilized the Pose API to extract the skeleton information of the video datasets provided in [MediaPipe](https://google.github.io/mediapipe/solutions/pose.html)
