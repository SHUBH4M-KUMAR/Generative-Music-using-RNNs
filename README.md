# Generative-Music-using-RNNs

**Overview**
This GitHub repository contains the code and resources for generating music using Recurrent Neural Networks (RNNs) with Long Short-Term Memory (LSTM) architecture. The model is trained on an Irish folk song dataset with ABC notations. The primary purpose of this project is to showcase the capabilities of RNNs in generating new and unique musical sequences based on the patterns learned from the training data.
**
Dataset**
The dataset used in this project consists of Irish folk songs represented in ABC notations. ABC notation is a simple text-based format for representing music that is widely used in the folk music community. The dataset is included in the data directory.

**Model Training**
The model is implemented using TensorFlow and Keras, and the training process is documented in the Jupyter notebook provided (music_generation_rnn.ipynb). The notebook is designed to be run on Google Colab, providing a convenient environment for training and experimenting with the music generation model.

**To run the notebook:**

Open the notebook in Google Colab.
Connect to a GPU runtime for faster training.
Execute each cell sequentially to train the model.

**Predicting Music**
Once the model is trained, you can use it to generate new music sequences. The notebook includes a section for generating music based on the learned patterns. Feel free to experiment with different seed sequences and parameters to create variations in the generated music.

**Dependencies**
The project has the following dependencies:

Python 3.x
TensorFlow
Keras
abcMIDI 
Mitdeeplearning utils
Install the required packages using the following command:

bash
Copy code
pip install -r requirements.txt

**Usage**
To generate music using the trained model, follow the steps outlined in the music_generation_rnn.ipynb notebook. Customize the input parameters, and experiment with different settings to observe the diversity in generated musical sequences.

**License**

This project is licensed under the MIT License - see the LICENSE file for details.

**Acknowledgments**

The Irish folk song dataset used in this project is sourced from [source link].
Inspiration and guidance from various music generation projects and research in the field.
Feel free to contribute, report issues, or reach out with any suggestions or improvements. Happy music generation! 
