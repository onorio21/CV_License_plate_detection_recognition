# CV_License_plate_detection_recognition
License Plate Detection and Recognition project for Computer Vision course Sapienza

# Abstract
Automatic car plate recognition is a crucial task in the field of computer vision with wide-ranging
applications in intelligent transportation systems, tra!c monitoring, law enforcement, and access control.
The goal is to accurately recognize and reconstruct vehicle license plates from images or video streams, often
captured under challenging real-world conditions such as varying lighting, occlusions, motion blur, and diverse
plate formats. Deep learning models, particularly convolutional neural networks, have significantly advanced
the performance and reliability of car plate recognition. This project aims to explore and implement deep
learning-based approaches for license plate recognition, emphasizing practical challenges and the impact of
robust solutions in modern urban infrastructure and mobility management.

# Dataset
The used dataset is available at [CCPD dataset](https://github.com/detectRecog/CCPD)

# Task
The objective of this project is to design and implement a deep learning-based system for license plate
recognition, following the methodology outlined in [1]. The proposed solution is structured as a two-stage pipeline,
leveraging the strengths of di”erent neural network architectures to address the distinct subtasks involved in the
recognition process. In the first stage, a YOLOv5 model is employed for license plate detection, allowing for
fast and accurate localization of the plate region within vehicle images, even under challenging environmental
conditions. In the second stage, the cropped plate region is passed to a specialized recognition model based on the
PDLPR architecture. This model is responsible for decoding the sequence of alphanumeric characters on the plate,
e”ectively treating the task as a sequence prediction problem. The integration of these two components aims to
deliver a robust and e!cient system for plates recognition and reconstruction suitable for deployment in real-world
scenarios.

# Authors
- [Onorio Iacobelli](https://github.com/onorio21)
- [Alessandro Rocchi](https://github.com/TheXbomber)

# References
1. Tao, L., Hong, S., Lin, Y., Chen, Y., He, P. and Tie, Z. (2024). A Real-Time License Plate Detection and
Recognition Model in Unconstrained Scenarios. Sensors, 24(9), 2791
2. Xu, Z.; Yang, W.; Meng, A.; Lu, N.; Huang, H.; Ying, C.; Huang, L. Towards end-to-end license plate
detection and recognition: A large dataset and baseline. In Proceedings of the European Conference on
Computer Vision (ECCV), Munich, Germany, 8–14 September 2018.
3. R. K. Prajapati, Y. Bhardwaj, R. K. Jain and D. Kamal Kant Hiran, ”A Review Paper on Automatic Num-
ber Plate Recognition using Machine Learning : An In-Depth Analysis of Machine Learning Techniques in
Automatic Number Plate Recognition: Opportunities and Limitations,” 2023 International Conference on
Computational Intelligence, Communication Technology and Networking (CICTN), Ghaziabad, India, 2023,
pp. 527-532
4. https://huggingface.co/keremberke/yolov5m-license-plate
5. https://github.com/PaddlePaddle/PaddleOCR


