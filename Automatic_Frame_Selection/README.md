To execute the code correctly, after extracting the video information through OpenPose, 
and replacing the directories within the files with the directories of the machine on which the codes are executed, 
they must be executed in the following order:

1. Dlib_video_to_frame (to extract dlib information)
2. jsontocsv_label_with_dlib (to merge Dlib information with Openpose information and create CSV file for the training)
3. CNN (to create and fit the Convolutional Neurale Network)
4. testing (to calculate the accuracy of the network)
5. n_best_frame (to execute the model on a video and save the N best frame)
