# Emotion Detection using CNN and Haar Cascade Classifier

## Idea
The basic idea is to allow detection of human emotions using a webcam. The emotions are detected using a Convolutional Neural Network (CNN) and the face is detected using a Haar Cascade Classifier.

## Brief
### Convolutional Neural Networks
A Convolutional Neural Network (CNN) is a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other. The pre-processing required in a CNN is much lower as compared to other classification algorithms. While in primitive methods filters are hand-engineered, with enough training, CNNs have the ability to learn these filters/characteristics.

### Haar Cascade Classifier
A Haar Cascade Classifier is an object detection algorithm which is used to identify faces in an image or a real time video. The algorithm uses edge or line detection features proposed by Viola and Jones in their research paper "Rapid Object Detection using a Boosted Cascade of Simple Features" published in 2001.

## Installation
1. Clone the repository
2. Install the dependencies using `pip install -r requirements.txt`
3. Run `python main.py`

## Screenshots
<table cellspacing="0" cellpadding="0">
    <tr>
        <td>
            <img src="screenshots/happy.png" alt="Happy Face">
        </td>
        <td>
            <img src="screenshots/surprise.png" alt="Surprised Face">
        </td>
    </tr>
</table> 

## Data Set
We used the [Face Expression Recognition Dataset](https://www.kaggle.com/jonathanoheix/face-expression-recognition-dataset) by [Jonathan Oheix](https://www.kaggle.com/jonathanoheix) from [Kaggle](https://www.kaggle.com/).


Made with ❤️ by [**Aniket Kumar**](https://www.linkedin.com/in/aniket-kumarr)
