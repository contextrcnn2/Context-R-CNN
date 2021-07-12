# Context-R-CNN
The repo consists of 4 files. First one is the loaded pre-trained model. other two are the library functions for the meta-arch. Last one is the architecture construction.

library1: consists of the library fucntions used to construct the short term memory bank, like weights and values filters and the generic attention block.

library2: consists of the library functions used to construct the long term memory bank. it includes context projectors, another attention block and extractors.

ARCHITECTURE: imported the faster RCNN meta architecure and other utilities like box_predictor from tensorflow. then used the library functions defined earlier to construct the meta-arch of the Conext RCNN.

PRE_TRAINED: preprcoessed the dataset by defining the bounding boxes for the dataset images along with uploading the JSON config files for the test and train data. plotted the bounding boxes on the test images. Further the pre-processed dataset will be used to re-train.

contributions: 
1. Nakula: data preprocessing and dataset uploading. Converted the sparse available dataset into a trainable one. Also, worked on the pre-trained model i.e PRE_TRAINED file.   Helped in the meta-architecture construction.
2. Piyush: worked on the codes of library functions of the short term memory bank i.e library1 file. Also, worked on the codes of attention module .
3. Rishabh: worked on the codes of library functions of the long term memory bank i.e library2 file.
4. Vaishnavi: worked on the meta-arch construction i.e ARCHITECTURE file. Used the library fucntions and imported faster RCNN to construct the arch.

we got results from the pre-trained model on images of one camera from the SS dataset.

* Everyone worked on the literature review part.
** we directly imported the faster RCNN model from tensorflow.

Future work:
In the next 10 days, we aim to re-train or fine tune the pre-trained model on another dataset which comprises of the images from a different camera in the same national park.  also, aim to complete the meta arch. The meta arch. is not possible to train from scratch due to computational resources limitations. that's why we'll be doing the re-training part on pre-trained model as told by the mentors. 
