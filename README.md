# StitchIt
Image stitching using SIFT, SURF, ORB, and BRISK for key point extraction, with Brute Force/KNN matching and RANSAC for homography, ensuring scale and rotation invariance resulting in a high quality panorama

Used various key points extraction algorithms like SIFT, SURF, ORB and BRISK for extracting the key points in the images
 • Used Brute Force Matcher and KNN Matcher for matching the key points and used RANSAC algorithm to find the
 homography between the two images
 • Finally wrapped both the images to create a stitched image and the algorithm is both Scale and Rotation invariant
