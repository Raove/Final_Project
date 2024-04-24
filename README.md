# CS445_2024_Final_Project

## Installation

Follow these steps to get your development environment running:

1. **Clone the repository**
   ```bash
   git clone https://github.com/Raove/Final_Project.git
   cd Final_Project
   ```
2. **Set up a Conda environment**

   ```bash
    conda create --name myenv python=3.9.13
    conda activate myenv

   ```

3. **Install library**
   ```bash
    pip install -r requirements.txt
   ```

## Motivation:

Human Emotion Recognition: We decided on emotion recognition, as sentiment analysis is an important subject and human emotion is a large part of that. It could have a significant positive impact on society, from improving mental health care to enhancing user experiences in various applications. There is also a great deal to be learned here, with this project crossing through multiple disciplines such as psychology, HCI, and of course computer vision. There is also a lot of work to be done in this field further than human emotion recognition, such as tying emotions to colors. This project is a great opportunity to dip our toes into this subject.

## Milestones:

- Gather a dataset
- Face recognition Training
- Emotion recognition Training
- Create classification for emotions
- Emotion classification accuracy
- Object detection for multiple subjects

## Evaluation:

We will connect to a camera or upload pictures of people’s faces and check what emotion they are showing. A success would be a recognition of the face regardless of the emotion shown or given. Later on as the milestones progress, the success would be giving the correct emotion.

## Resources:

- Webcam
- OpenCV, TensorFlow, Pytorch
- Dataset of individuals presenting different emotions
- FER dataset: https://www.kaggle.com/datasets/deadskull7/fer2013
- https://docs.opencv.org/3.4/da/d60/tutorial_face_main.html

## Group Contributions:

| Name  | Contribution                               |
| ----- | ------------------------------------------ |
| Raoul | Data exploration, Research, Testing        |
| Rohan | Data exploration, Data Gathering, Testing  |
| Fufei | Data exploration, Research, Model Research |
| Tyler | Data exploration, Research, Model Research |
