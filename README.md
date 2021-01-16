# Identify-similar-images

Reference: TensorFlow: Advanced Techniques Specialization - Laurence Moroney

## Abstract: 
Finding matching images across large datasets plays a key role in many computer vision applications such as structure-from-motion (SfM), multi-view 3D reconstruction, im- age retrieval, and image-based localisation. In this module, we propose finding matching and non-matching pairs of images by representing them with neural network based feature vectors, whose similarity is measured by Euclidean distance. The feature vectors are obtained with convolutional neural networks which are learnt from labeled examples of matching and non-matching image pairs by using a contrastive loss function in a Siamese network architecture. 

Previously Siamese architecture has been utilised in facial image verification and in matching local image patches, but not yet in generic image retrieval or whole-image matching. Our experimental results show that the proposed features improve matching performance compared to baseline features obtained with networks which are trained for image classification task. The features generalize well and improve matching of images of new landmarks which are not seen at training time. This is despite the fact that the labeling of matching and non-matching pairs is imperfect in our training data. The results are promising considering image retrieval applications, and there is potential for further improvement by utilising more training image pairs with more accurate ground truth labels.


![Result](Clothes.png)
