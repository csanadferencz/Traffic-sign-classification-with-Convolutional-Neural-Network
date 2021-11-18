# Traffic-sign-classification-with-Convolutional-Neural-Network

The task is to categorize  40×40  RGB pixelspace input images into 43 possible traffic sign categories: ℎ: ℝ4800 ↦ {0,1,…,42}. Due to the three color channels we have a 40 × 40 × 3 = 4800 dimensional input.
The used dataset consists of more than 50000 images total. A detailed description about the dataset can be found via this link: https://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset. An already pre-processed version of the images resized to 40x40 will be used.
In this task, convolutional neural networks (CNN-s) usually perform at around 90-95% accuracy. The goal is to try training a network that performs better than humans (98.9% on the original GTSRB).
