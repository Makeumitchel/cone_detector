# cone_detector

This models detect and counts the number of cones on a larch tree. It requires to download the images to be treated in a folder in cone_detector/data/. You can then run the detector through the whole folder using the method run_through_folder with the folder_name as an argument. The predictions will be saved in a csv file in cone_detector/predictions/prediction_folder_name.csv.  To consider a single image and see the detected cones use the method detect with the image name as an argument.
