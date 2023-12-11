# Single View Homography Estimation of an inclined texture planar surface: Overcoming the Inverse and Ill-Posed Challenge!

1. Contributions

We propose a solution for  single view homography estimation, where given only a single view of an inclined texture planar surface we estimate the homography and the corresponding orthogonal (rectified) view of the planar surface. [To the best of our knowledge, we are the first to estimate homography using single input image] This research also proposes a "homography dataset" that contains diverse and challenging texture images (mostly checkerboard and grid patterns with a few real-world scenes). Numerous experiments were conducted to verify the performance of our proposed algorithm and our work demonstrates cutting-edge performance on various texture datasets such as Stereocamera Chessboard dataset, Synthetic Chess Board Images, and Chess Pieces Object Detection.


3. Proposed methodology:

![Screenshot from 2023-12-11 12-02-28](https://github.com/pooja12295/HOMOGRAPHY-ESTIMATION-FROM-ONLY-A-SINGLE-VIEW-TEXTURED-PLANAR-SURFACE-USING-IMAGE-RECTIFICATION/assets/57430450/63ded384-e5e5-483e-93c0-19c48a47c9ad)

3. Dataset details:

We created our own dataset because there was no such dataset that could be used for our problem statement directly and their simulation gives us several inclined perspectives of the surfaces together with their orthogonal projections. Ground truth homography is also specified in this collection for several image perspectives. Our homography dataset contains more than 300 images from different perspectives with different combinations of transformations. We also collected some real-world images using a Nikon D7200 DSLR camera and mobile phones. The images in our homography dataset have different dimensions ranging from 512 x 512 to 2165 x 1506 (H x W, where H is height and W is the width of the image). 

![Screenshot from 2023-12-11 12-05-29](https://github.com/pooja12295/HOMOGRAPHY-ESTIMATION-FROM-ONLY-A-SINGLE-VIEW-TEXTURED-PLANAR-SURFACE-USING-IMAGE-RECTIFICATION/assets/57430450/6236e77d-4b7c-49de-8e86-aac882043c1c)

4. Qualitative Results:
   
![Screenshot from 2023-12-11 12-06-15](https://github.com/pooja12295/HOMOGRAPHY-ESTIMATION-FROM-ONLY-A-SINGLE-VIEW-TEXTURED-PLANAR-SURFACE-USING-IMAGE-RECTIFICATION/assets/57430450/ac273ebf-8459-44d8-b07c-2153ee04377b)
![Screenshot from 2023-12-11 12-07-04](https://github.com/pooja12295/HOMOGRAPHY-ESTIMATION-FROM-ONLY-A-SINGLE-VIEW-TEXTURED-PLANAR-SURFACE-USING-IMAGE-RECTIFICATION/assets/57430450/027515ab-57eb-4839-9793-3313120de3c2)
![Screenshot from 2023-12-11 12-07-45](https://github.com/pooja12295/HOMOGRAPHY-ESTIMATION-FROM-ONLY-A-SINGLE-VIEW-TEXTURED-PLANAR-SURFACE-USING-IMAGE-RECTIFICATION/assets/57430450/b3a9178f-3170-46a2-aa51-b411b9c709f5)
![Screenshot from 2023-12-11 12-08-36](https://github.com/pooja12295/HOMOGRAPHY-ESTIMATION-FROM-ONLY-A-SINGLE-VIEW-TEXTURED-PLANAR-SURFACE-USING-IMAGE-RECTIFICATION/assets/57430450/021e9acf-d6fa-4629-8604-9b975033a3e4)
![Screenshot from 2023-12-11 12-09-05](https://github.com/pooja12295/HOMOGRAPHY-ESTIMATION-FROM-ONLY-A-SINGLE-VIEW-TEXTURED-PLANAR-SURFACE-USING-IMAGE-RECTIFICATION/assets/57430450/5dd5b7c1-2e5f-44ca-9fa3-438aec2e99f3)
![Screenshot from 2023-12-11 12-09-42](https://github.com/pooja12295/HOMOGRAPHY-ESTIMATION-FROM-ONLY-A-SINGLE-VIEW-TEXTURED-PLANAR-SURFACE-USING-IMAGE-RECTIFICATION/assets/57430450/6e4e4b17-ec7e-4b67-823f-402a737e5a30)

5. Quantitative Results:

![Screenshot from 2023-12-11 12-10-56](https://github.com/pooja12295/HOMOGRAPHY-ESTIMATION-FROM-ONLY-A-SINGLE-VIEW-TEXTURED-PLANAR-SURFACE-USING-IMAGE-RECTIFICATION/assets/57430450/33b32aa7-3327-4122-b22e-51d6aacfc5ed)

Note: Our method is not trained on any dataset as it uses classical method while other SOTA use deep learning techniques and are trained on various datasets. 

6. Faiiure Cases:

![Screenshot from 2023-12-11 12-13-14](https://github.com/pooja12295/HOMOGRAPHY-ESTIMATION-FROM-ONLY-A-SINGLE-VIEW-TEXTURED-PLANAR-SURFACE-USING-IMAGE-RECTIFICATION/assets/57430450/26713f51-af60-4052-a58a-10ea85727723)
![Screenshot from 2023-12-11 12-13-42](https://github.com/pooja12295/HOMOGRAPHY-ESTIMATION-FROM-ONLY-A-SINGLE-VIEW-TEXTURED-PLANAR-SURFACE-USING-IMAGE-RECTIFICATION/assets/57430450/11b6e5ea-0707-4e18-ba74-80666295d41e)
![Screenshot from 2023-12-11 12-14-03](https://github.com/pooja12295/HOMOGRAPHY-ESTIMATION-FROM-ONLY-A-SINGLE-VIEW-TEXTURED-PLANAR-SURFACE-USING-IMAGE-RECTIFICATION/assets/57430450/8a05299a-d474-4b81-b22a-0b5f05d256c9)

![Screenshot from 2023-12-11 12-14-43](https://github.com/pooja12295/HOMOGRAPHY-ESTIMATION-FROM-ONLY-A-SINGLE-VIEW-TEXTURED-PLANAR-SURFACE-USING-IMAGE-RECTIFICATION/assets/57430450/4b2518e4-fba0-48f0-89ee-b61b1d6ae77c)




