 Beyond Cards and PINs: Enhancing ATM Security with Iris Recognition and CNN

 Project Overview

This project proposes a modern and highly secure ATM authentication system using Iris Recognition Technology integrated with a Convolutional Neural Network (CNN) algorithm. The goal is to replace traditional card and PIN-based authentication with biometric-based identification, enhancing user security and convenience.

 Key Features

- Biometric Authentication: Uses iris recognition to verify user identity.
- Deep Learning with CNN: Extracts features from facial images for accurate verification.
- Card-less & PIN-less Access: Eliminates the risk of card theft and skimming.
- Enhanced Security: Strong defense against unauthorized access and identity fraud.
- Performance Optimization: CNN trained with data augmentation and evaluated using accuracy, precision, recall, and F1-score.

 System Architecture

The proposed ATM system consists of:

- User Interface: Captures facial/iris data and allows transaction selection.
- Facial Recognition Module: Applies CNN for biometric authentication.
- Transaction Processing Module: Manages withdrawals, balance checks, etc.
- Security Module: Encrypts sensitive data and enforces access control.
- Database: Stores biometric templates and transaction logs.

 CNN Model Summary

- Layers: Convolution → ReLU → Pooling → Flatten → Dense → SoftMax
- Optimizer: Adam (Learning rate = 0.001)
- Loss Function: Categorical Cross-Entropy
- Epochs: 10
- Batch Size: 32
- Techniques: Data Augmentation (rotation, shifts, zoom)

 Technologies Used

- Python
- OpenCV
- TensorFlow/Keras
- SQLite / MySQL (for user data storage)
- High-Resolution Camera
- GUI Tools (Tkinter or web-based frontend)

 Literature References

The system is designed based on extensive research and incorporates findings from reputable sources like:

- Jain et al. – Handbook of Biometrics
- Wang et al. – CNN for Facial Recognition
- Krizhevsky et al. – Deep Learning with CNNs
- Multiple IEEE and Springer journals

 Future Scope

- Integration with mobile banking apps
- Multi-modal biometric authentication (Iris + Fingerprint)
- Real-time fraud detection using AI
- Deployment on real ATM hardware for live testing

 Authors

- M.D. Narmadha (Assistant Professor)
- M. Sabarieesh, V. Sivaashankar, N. Vijayaragavan, S. Pavithra, V. Sridhar (UG Scholars)
- Raja S (Assistant Professor, SNS College of Technology)

 Contact

For questions or collaboration:
- Email: narmadhamd17@gmail.com
- Email: raja.s.ece@snsct.org

 License

This project is for academic and research purposes. For commercial use, please contact the authors.
