## Magnetic reconnection prediction using recurrent Neural Networks(RNN) and Data Augmentation<br>
<b>Dataset Details:</b><Br>
  you can download dataset from <a href = "https://omniweb.gsfc.nasa.gov/form/sc_merge_min1.html" target="_blank">DataSet of ACE satalite</a>.<br>

<b>Dataset Description:</b><br>
Dataset contain 24 lakh observations of Bx,By,Bz components of magnetic field of earth and sun from satelite ACE ,
we will train our model on 15 lakh observations , 5 lakh observations for validation and 4 lakh observations for testing.<br><br>
Training data   = 15 lakh rows of Bx ,By ,Bz components other features  and <br> 

<b> Libraries Used : </b>
<b> Numpy Version 1.26.0 <b>
<b> TensorFlow  Latest current version(2.14.0) </b>
<b> MatPlotlib Version 3.0<b>
<b> Keras Version 2.14.0 </b>
<b> Streamlit Version 1.27.2</b>



<b> Algorithms Used : </b><br>

<b>LSTM - Long Short Term Memory Algorithm </b><br>
<b>SVM - Support vector machine</b><br>

<b>Model Summary:</b><br>
<b>we used Recurrent neural networks with 10  layers.<Br>



<b>Results:</b><br>
Achieved 84% Accuracy on Training data with <b><i>epochs = 100</i></b><br>
83% accuracy on validation data<br>
79% accuracy on testing data<br>
