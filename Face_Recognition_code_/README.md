Face Recognition using CNN, SVM, and Fuzzy Logic

This project presents a hybrid face recognition system that combines Convolutional Neural Networks (CNNs), Support Vector Machines (SVMs), and Fuzzy Logic to improve recognition accuracy in real-world conditions. The system is designed to handle challenges such as lighting variations, pose changes, and facial expressions.

Methodology
The system follows a structured pipeline that starts with image preprocessing and normalization. Facial features are extracted using a pre-trained ResNet50 model. These features are then classified using an SVM classifier. Fuzzy logic is applied as a final decision layer to refine predictions, especially in uncertain or low-confidence cases. The model performance is evaluated using standard classification metrics.

Dataset
The project uses the Labeled Faces in the Wild (LFW) dataset, which is a well-known and widely used benchmark in face recognition research. The dataset contains images of real individuals captured under unconstrained, real-world conditions.

Results
The proposed system demonstrates strong performance, achieving high accuracy and balanced precision and recall. The integration of fuzzy logic helps improve robustness by handling ambiguous cases and reducing misclassification of unknown faces.

Tools and Technologies
The project was implemented using Python and Jupyter Notebook. Deep learning and machine learning components were built using TensorFlow, Keras, and Scikit-learn, with additional support from OpenCV and Scikit-Fuzzy.

Project Files
The repository includes a Jupyter Notebook containing the full implementation of the system and a PDF report that explains the methodology, experiments, and results in detail.

How to Run
To run the project, download the LFW dataset, open the Jupyter Notebook file, and execute the cells sequentially.

Purpose
This project explores hybrid approaches for face recognition.

Author
Albatul Altoum (team project)