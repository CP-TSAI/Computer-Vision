## Using homography mapping to inpaint an image, and convert it into front view 
- Calculate homography mapping matrixes between two images, and inpainting the obstacle region of the image, then convert it into a front-view image.

<img src="https://github.com/CP-TSAI/Computer-Vision/raw/master/cv_pic/1.JPG" width="45%" height="45%"> <img src="https://github.com/CP-TSAI/Computer-Vision/raw/master/cv_pic/2.JPG" width="45%" height="45%"> 

- Please manually pickup at least 4 corresponding coordinates on both images by using any Image Viewer Tool.

- Store these correspondences, then compute their homography matrix. (Hint: all points on this projection-screen are co-planar.)

- Please manually define the pixel-region of the obstacle, as a mask. Then draw the regions by the pixels from other view according to homography transformation. 

- Finally convert it into front view image. 

## Results:
<img src="https://github.com/CP-TSAI/Computer-Vision/raw/master/cv_pic/隨班附讀-蔡金博.jpg" width="25%" height="25%"> 
