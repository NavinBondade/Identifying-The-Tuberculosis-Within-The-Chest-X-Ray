# Tuberculosis Detection With Deep Learning (90% Accuracy)
<img src="https://cdn.the-scientist.com/assets/articleNo/66278/aImg/33044/tb.jpg" alt="tomato" width="900" height="580">
Tuberculosis is one of the deadliest diseases and ranks 10th in the leading cause of death worldwide; alone in 2019, there was an estimated total of 1,418,000 tuberculosis related deaths. The major symptoms of tuberculosis are the cough that lasts more than three weeks, loss of appetite and unintentional weight loss, fever, chills, and night sweats. Most people die because of tuberculous mainly die because of the negligence of symptoms or not getting proper health treatment at the proper time. For fight against this problem and to save countless life I have created this convolutional neural network-based deep learning model that is capable of identifying Tuberculosis with an accuracy of 90%. 
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Keras</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Numpy</li>
  <li>Open CV</li>
  <li>Glob</li>
</ul> 
<h2>Data Visualization</h2>
<img src="https://github.com/NavinBondade/Tuberculosis_Detection_with_90_percent_accuracy/blob/main/Tuberculosis%20Detection%20with%2090%25%20accuracy/Graps%20and%20Images/Tuberculosis%20Data%20Visualization.jpg" width="730" height="430">
<h2>Model Details</h2>
<p>The model consists of four convolutional layers for feature extraction from the images, each followed by a max-pooling layer and having the same padding. After the convolutional and max-pooling layers, the model uses three dense layers for the classification task. All the convolutional and dense layers use the Relu activation function except the last dense layer, which uses the softmax activation function. The model was trained for 20 epochs with batch size equals to 19. During the training process parse binary cross-entropy loss function was used along with Adam optimizer. The dataset on which the model has trained has downloaded from Kaggle.com (https://bit.ly/3vw3FJQ) </p>

