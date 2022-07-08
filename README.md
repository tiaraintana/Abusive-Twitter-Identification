# Abusive-Twitter-Identification

## Citation
This topic with RNN-LSTM method has been publication on intenational Q3 journal in IAES International Journal of Artificial Intelligence (IJ-AI) (https://ijai.iaescore.com/index.php/IJAI/article/view/21071)
T. I. Sari, Z. N. Ardilla, N. Hayatin, and R. Maskat, “Abusive comment identification on Indonesian social media data using hybrid deep learning,” IAES Int. J. Artif. Intell., vol. 11, no. 3, pp. 895–904, 2022, doi: 10.11591/ijai.v11.i3.pp895-904.

## Dataset Description

The dataset from Kaggle (https://www.kaggle.com/) that create by Ilham Firdausi Putra with title is [Indonesian Abusive and Hate Speech Twitter Text](https://www.kaggle.com/ilhamfp31/indonesian-abusive-and-hate-speech-twitter-text)

The dataset is multi-label hate speech and abusive language detection in the Indonesian Twitter. The main dataset can be seen at re_dataset with labels information as follows:

* HS : hate speech label;
* Abusive : abusive language label;
* HS_Individual : hate speech targeted to an individual;
* HS_Group : hate speech targeted to a group;
* HS_Religion : hate speech related to religion/creed;
* HS_Race : hate speech related to race/ethnicity;
* HS_Physical : hate speech related to physical/disability;
* HS_Gender : hate speech related to gender/sexual orientation;
* HS_Gender : hate related to other invective/slander;
* HS_Weak : weak hate speech;
* HS_Moderate : moderate hate speech;
* HS_Strong : strong hate speech.

But, for the research data that used just Abusive Column, and we also used the oversampling and preprocessing of data that the result can bee seen on github which tithe "Text Preprocessing"

## Authors

Kontributor dalam projek ini yaitu :
* Tiara Intana Sari tiaraintana@gmail.com
* Zalfa Natania Ardila zalfaardila@gmail.com

## Acknowledgments

Inspiration, code snippets, etc.
* [Indonesian Abusive and Hate Speech Twitter Text](https://www.kaggle.com/ilhamfp31/indonesian-abusive-and-hate-speech-twitter-text)
* [Tensorflow](https://github.com/aymericdamien/TensorFlow-Examples/blob/master/tensorflow_v1/examples/3_NeuralNetworks/convolutional_network.py)
* [DenseNet Documentation](https://keras.io/api/applications/densenet/)
* [Resnet Documentation](https://keras.io/api/applications/resnet/)
* [SimpleRNN Documentation](https://www.tensorflow.org/api_docs/python/tf/keras/layers/SimpleRNN)
