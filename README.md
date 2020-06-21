# Face-Recognization

# Introduction

Face recognition problems commonly fall into two categories:

- Face Verification - "is this the claimed person?". For example, at some airports, you can pass through customs by letting a system scan your passport and then verifying that you (the person carrying the passport) are the correct person. A mobile phone that unlocks using your face is also using face verification. This is a 1:1 matching problem.

- Face Recognition - "who is this person?". For example, the video lecture showed a face recognition video (https://www.youtube.com/watch?v=wr4rx0Spihs) of Baidu employees entering the office without needing to otherwise identify themselves. This is a 1:K matching problem.

# Output 

- Implement the triplet loss function.

- Use a pretrained model to map face images into 128-dimensional encodings.

- Use these encodings to perform face verification and face recognition.

# Requirements

- Jupyter-Notebook 
- Tensorflow
- Pandas
- Keras
- Numpy
- Python 3.8

# References

- Florian Schroff, Dmitry Kalenichenko, James Philbin (2015). FaceNet: A Unified Embedding for Face Recognition and Clustering

- Yaniv Taigman, Ming Yang, Marc'Aurelio Ranzato, Lior Wolf (2014). DeepFace: Closing the gap to human-level performance in face verification

- The pretrained model we use is inspired by Victor Sy Wang's implementation and was loaded using his code: https://github.com/iwantooxxoox/Keras-OpenFace.

- Our implementation also took a lot of inspiration from the official FaceNet github repository: https://github.com/davidsandberg/facenet


