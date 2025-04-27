# BioVid
BioVid Dataset on MultiModal user authentication
BioVid Dataset

Welcome to the official repository for the BioVid dataset, a comprehensive video dataset designed for speaker identification and multimodal deep learning research.
For any question about the dataset send an email to: biometric.dataset.25@gmail.com

# Dataset Overview

The BioVid dataset contains 650 video recordings of 43 different users, focusing exclusively on the mouth region for visual consistency and precise lip-reading analysis. The dataset is structured as follows:

Each user has a dedicated folder named after their corresponding user ID.

Each folder contains 13 video files (.mp4), where each video is labeled with the spoken word as its filename.

This labeling scheme ensures straightforward identification of both the video content and the corresponding speaker, making it ideal for training multimodal deep learning models.

# Dataset Structure

Resolution: All videos were recorded at a resolution of 1080 x 1920 pixels using front-facing cameras.

Number of users: 43

Number of videos: 650

Number of words: 90

Number of videos with wrong password: 400

Number of videos with right password: 250

Number of different distances for recording: 5

Number of locations for recording: 21

Number of different smartphones for recording: 14

Video Cropping: Each video is pre-cropped to show only the mouth region.

# Data Annotation

Each video has been recorded into a subdirectory named with a specific username. This labeling scheme enables the precise identification of each video and its corresponding speaker. 

# Data Collection Methodology

Recording Environment: Videos were recorded in a controlled environment measuring 4m x 4m x 3m, with low background noise.

Noise Levels: Noise levels were measured during three separate recording sessions:

Session 1: 18 dB

Session 2: 19 dB

Session 3: 17.5 dB

Noise levels were measured using the Fonometro (Sound Meter) app.

Camera Distances: Participants held the camera at varying distances from their face, chosen from 30 cm, 35 cm, 40 cm, 45 cm, and 50 cm.

This variability in distance helps simulate real-world recording conditions, ensuring robustness in future models trained on the dataset.

# Word Statistics

The average length of the words in the dataset is 5.51 characters. The shortest word is composed of 3 characters, while the longest word is composed of 13 characters.

# Applications

The BioVid dataset is ideal for applications in:

Speaker Identification

Lip Reading

Multimodal Deep Learning

Robustness Testing under Varying Conditions

# Citation

If you use the BioVid dataset in your research, please provide proper citation.

# Acknowledgments

Thank you to all participants for their contributions and to the team for their efforts in data collection and processing.

We look forward to seeing how this dataset advances the field of multimodal learning and speaker identification!


