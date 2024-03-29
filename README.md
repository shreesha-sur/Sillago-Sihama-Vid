# Sillago-Sihama-Vid:
 Fish behaviour analysis plays an important role in managing fish farms in aquaculture. The lack of fish datasets for their behaviour analysis has limited the growth of computer-vision based technologies in aquaculture. Here, we provide an extensive Sillago sihama fish dataset for behaviour analysis via tracking. The dataset contains  a total of 16 videos, split into training (8) and testing (8).  The fish trajectory annotations are provided in Pascal VOC format. The dataset contains 8 to 10 fishes in an aquarium. We have strictly followed MOT16 annotation rules to create the dataset. We have emulated the natural environment of the fish in the aquarium to capture the normal behaviour of the fishes (Sillago sihama). Studying the behaviour patterns can provide greater insights regarding the fish, thereby enabling better management of the fish farms.

# Update (June 2022): We will be presenting our work in CV4Animals workshop organized at CVPR 2022. [View Poster](https://drive.google.com/file/d/1ILXqFQLoxvMsu7KnPWU6J-M5JwjOp-Qk/view). Do visit the [workshop website](https://www.cv4animals.com/) for more details

# Dataset details:
![Table_dataset_details](https://user-images.githubusercontent.com/91935551/138856329-d9bb2cfd-c3bd-4907-9c52-b514b648a994.PNG)

Few sample frames of the dataset has been shown below. 

![Sample-frame](https://user-images.githubusercontent.com/91935551/138845151-fd0ae478-b48e-48b3-9b0f-b22968e4a110.png)

![Sample_frame2](https://user-images.githubusercontent.com/91935551/138845180-0beb1b4e-449a-4375-8afd-6d676024fcb2.png)

Few sample frames with the annotation has been shown below.

![Sample_annotation_frame1](https://user-images.githubusercontent.com/91935551/138845218-646663ed-7325-438d-9e56-62f969e391cd.PNG)

![Sample_annotation_frame2](https://user-images.githubusercontent.com/91935551/138845232-e8494f0c-ad12-488d-b3ed-33816b49d1e8.PNG)

A sample result of the proposed tracking algorithm on the dataset is shown below. It is clearly seen that, the dark blue, yellow and orange coloured bounding box tracks the fishes even if there are rapid motion, sudden change in direction and occlusion. This shows the efficiency of the proposed tracking method. The proposed method considers appearance, motion, spatial and swim direction for making association between the tracklets and detections. Furthermore, the challenges of the dataset are clearly seen in the video. There are occlusions, reflections on the panel, rapid motions and sudden changes in the swim direction.


https://user-images.githubusercontent.com/91935551/167343628-106ef44c-2a31-431c-aa96-98dd4d92099c.mp4




# Download:
Please fill the [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSfHf5dBdDdPlKJ6eNuCGXqt_wSLJpL7Im5X31-DZtRdfK255g/viewform) if you are interested in using this dataset. The link to download the dataset will be shared to your email address. 
