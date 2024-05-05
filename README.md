# CS445_2024_Final_Project

## Installation

Follow these steps to get your development environment running:

1. **Clone the repository**
   ```bash
   git clone -b Emotion_Change https://github.com/Raove/Final_Project.git
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

4. **Run Code**
   Load existing models in objectdetect.ipynb as well as all data processing functions, then use call of the three WebcamViewer functions. The first focuses on single subjects, the second handles multiple subjects, and the third uses a VGG16 model for comparison.


## Motivation:

Human Emotion Recognition: We decided on emotion recognition, as sentiment analysis is an important subject and human emotion is a large part of that. It could have a significant positive impact on society, from improving mental health care to enhancing user experiences in various applications. There is also a great deal to be learned here, with this project crossing through multiple disciplines such as psychology, HCI, and of course computer vision. There is also a lot of work to be done in this field further than human emotion recognition, such as tying emotions to colors. This project is a great opportunity to dip our toes into this subject. In addition to our main project, we wanted to show that we could change the emotions given a picture and a masked picture of a given emotion.

## Milestones:

- Gather images
- Perform poisson blending to blend images together
- Final image with the face having an entirely different emotion

## Evaluation:

We will use an image of a person's face and an image of a their emotion. A success would be a natural change given an emotion and a face.

## Resources:

- OpenCV, matplot, scipy, skiamge, numpy
- Dataset of individuals faces and emotions
- https://www.pinterest.com/pin/40884309088244854/
- https://www.slate.com/articles/health_and_science/cover_story/2016/08/can_smiling_make_you_happier_maybe_maybe_not_we_have_no_idea.html

## Group Contributions:

| Name  | Contribution                               |
| ----- | ------------------------------------------ |
| Raoul | Data exploration, Research, Testing        |
| Rohan | Data exploration, Data Gathering, Testing  |
| Fufei | Data exploration, Research, Model Research |
| Tyler | Data exploration, Research, Model Research |
