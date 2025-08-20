# ASL-Detection-using-Deep-Learning

<p align="center">
<img src = "https://menlocoa.org/wp-content/uploads/2023/04/Screen-Shot-2023-04-05-at-10.09.30-AM-900x606.png" width = 500>
</p>

### Overview 
Sign language is a mode of communication that enables individuals with hearing or speech impairment, or both, to express themselves. Sign Language Recognition from videos has become a new challenge in this research field. This paper focuses on Isolated Sign Language Recognition, which involves recognizing and interpreting phrases or words expressed through gestures and hand movements through a short video. 
 
With the advancement of convolutional and recurrent neural network architectures in Computer Vision, this paper proposes efficient deep learning models to recognize American Sign Language (ASL). The models implemented in this paper are ResNet50, ResNet50 + BiLSTM, Xception, and Xception + BiLSTM. Overall, ResNet50 + BiLSTM peformed the best. The models were trained and evaluated on a 10-gloss subset of the WLASL dataset. Furthermore, a compartive analysis was performed with the models proposed in other research papers implemented for the same purpose.

 ### Keywords
 Sign Language Recognition   
 Isolated Sign Language Recognition   
 Deep Learning   
 American Sign Language   
 Transfer Learning  
 Computer Vision  

 ### Publishing 
 You can view my complete research paper here! [Click Here](https://link.springer.com/chapter/10.1007/978-981-96-1758-6_31)


 ### Some information about the research project

 1. The dataset used for this project is the World Level American Sign Language (WLASL) video dataset. It is publically available on Kaggle. You can find the link to it here: https://www.kaggle.com/datasets/risangbaskoro/wlasl-processed

 2. For the project, we have used a subset of 10 classes. The following classes were selected– ’before’, ’computer’, ’cool’, ’cousin’, ’drink’, ’go’, ’help’, ’take’, ’thin’, and ’who’. On average, there are around 11 videos per class.   

 3. The following models were developed and used in this project:
    - ResNet50
    - ResNet50 + BiLSTM
    - Xception
    - Xception + BiLSTM

4. The following were the evaluation metrics used to evaluate the model perfomances:
    - Accuracy (Also considering the Average accuracies of Train, Validation and Test sets)
    - Precision 
    - Recall
    - F1 Score
    - Accuracy and loss graphs (included in Final_Dissertation_Report pdf document)
    - Confusion matrix (included in Final_Dissertation_Report pdf document)
