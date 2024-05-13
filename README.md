> **What is it exactly?**

It is an image sorting script that efficiently employs advanced analysis to sort images and returns images it deems are the highest quality among all of them.

> **How is it built?**

Used OpenCV and Dlib to craft our facial recognition and image quality assessment feature. 
Set up an AWS EC2 server creating an instance, allowing remote access and setting up SSH, and optimized the server for better efficiency.

> **How does it work?**

We successfully integrated it into an AWS EC2 web server, incorporating facial recognition to identify faces, smiles, and assess image quality, including blurry pictures. -Used Grayscale filter on each RGB to which filtered out irrelevant information to our analysis of intensity of each RGB thus making it uniform for us to apply the Laplacian Filter -Used the Laplacian filter for edge detection and provides a measure of the rate of change of intensity/brightness in an image. This determined if an image was blurry or not.
