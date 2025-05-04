This project seeks to classify an individual handwritten
word so that handwritten text can be translated to a digital form. We used two main approaches to accomplish this
task: classifying words directly and character segmentation. For the former, we use Convolutional Neural Network
(CNN) with various architectures to train a model that can
accurately classify words. For the latter, we use Long Short
Term Memory networks (LSTM) with convolution to construct bounding boxes for each character. We then pass the
segmented characters to a CNN for classification, and then
reconstruct each word according to the results of classification and segmentation.
