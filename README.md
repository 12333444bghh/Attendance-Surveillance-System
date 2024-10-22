The "Attendance Surveillance System Using CNN" is an innovative approach designed to automate and enhance the accuracy of attendance monitoring in various environments,
such as educational institutions and workplaces. By leveraging the power of Convolutional Neural Networks (CNNs), this system aims to replace traditional methods of
attendance tracking, which are often manual, time-consuming, and prone to errors.The system of intelligent attendance is generally implemented with biometrics help.
Recognition of face is one of the Biometric ways of improving this system Face recognition proved to be a productive method for taking attendance.
Traditional attendance systems typically rely on manual entry or RFID card swiping, which can be inefficient and easily manipulated. The need for a more secure,
efficient, and accurate system has led to the exploration of computer vision techniques,particularly CNNs, which have shown remarkable success in image
recognition and classification tasks.
The accurate monitoring of attendance in educational settings is crucial for maintaining academic discipline and enhancing learning outcomes.
Traditional methods of attendance recording, such as manual roll calls, are time-consuming, suspected for proxy attendence and prone to errors.
To address these challenges, this project proposes an Attendance Surveillance System using Convolutional Neural Networks (CNNs).
Approach begins with the collection of a classroom dataset, captured manually through photographs. Individual faces within these
images are detected and extracted using the Multi-task Cascaded Convolutional Networks (MTCNN) framework. These extracted faces are
then divided into separate training and testing datasets, ensuring no overlap between the images used for training and testing to maintain the 
integrity of the evaluation process. Specifically, the training set comprises 367 images, which have been augmented to enhance model robustness,
while the test set includes 24 distinct images.
To improve face recognition, we employ FaceNet for transfer learning, generating embeddings that represent the facial features. 
These embeddings are then used to train a CNN model, which forms the core of our attendance detection system. Our CNN-based model achieves an accuracy of 87.5%
