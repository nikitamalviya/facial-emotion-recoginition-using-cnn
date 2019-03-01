README file for the Indian Spontaneous Expression Database (ISED)
----------------------------------------------------------------

Thank you for downloading material from the database. The description of the files are given below.

videos.zip - It contains all the videos of facial expressions.
    videos/PS 1 - Data of participant 1
    videos/PS 1/4.avi - 4th video of participant 1

peakImages.zip - It contains all the peak images of the included facial expression videos
    peakImages/26_7_39.jpg - Peak images of participant 26, clip number 7 which is the frame number 39.
    peakImages/5_3_85.jpg - Peak image of 3rd video clip from 5th participant. The frame number of the image frame in the video is 85.

ISED_details.mat - It contains the details of the data included in the databas. For easy assess of the database, the paths to all the files are provided here. It also includes the position of face, nose and eyes in the peak frames of each clip. 
    column 1: participant number
    column 2: participant ID
    column 3: video number
    column 4: peak intensity frame number in that clip (frame numbering starts with 1)
    column 5: video clip path
    column 6: path to the peak image in that video clip
    column 7: Emotion label. The following convension is used:
                1) happiness
                2) surprise
                3) sadness
                4) disgust
    column 8: intensity of emotion as annotated by the decoders
    column 9: male/female
    column 10: spectacles: yes/no
    column 11: beard/mustache: yes/no
    column 12: other occlusions: yes/no (includes hand,hair etc.)
    column 13: face position of the participant in the peak image of the video clip
    column 14: eye position of the participant in the peak image of the video clip
    column 15: eye position of the participant in the peak image of the video clip
    column 16: nose position of the participant in the peak image of the video clip

ISED_peak_images.mat - This file contains all the peak intensity images of each video clip

HowToUse.m - Some example codes to make use of different files

If you have any questions regarding the database, please contact us at iseddatabase@gmail.com.

For full details see:
Happy, S. L., Patnaik, P. , Routray, A. , Guha, R., "The Indian Spontaneous Expression Database for Emotion Recognition", Affective Computing, IEEE Transactions on, 2015, DOI:10.1109/TAFFC.2015.2498174