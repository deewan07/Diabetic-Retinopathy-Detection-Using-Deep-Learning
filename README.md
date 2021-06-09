# Diabetic-Retinopathy-Detection-Using-Deep-Learning

Diabetic Retinopathy is a leading disease-causing vision-loss globally. Retinopathy has
several stages if not rehabilitated in time it could be severe. It originates from the
diabetic disease, an increase of sugar level in the blood vessels of the retina. This paper
is all about the smart proposed model which is trained to detect the stage of Diabetic
Retinopathy in patients. simply by putting the fundus images into our model, it will not
only detect Retinopathy disease but also tell which stage it is. Generally, DR can be
separated into two major stages: non-proliferative DR (NPDR) and proliferative DR
(PDR). Our model is capable to detect 5 stages of DR namely No DR, Mild DR, Moderate
DR, Severe DR, and Proliferative DR. It will be very beneficial for doctors as well as for
researchers to detect Diabetic Retinopathy patients at an instant. Generally, it is
time-consuming for doctors to analyze each and every tiny nerve cell from fundus
images.

The proposed model uses Densenet Convolutional Neural Network to train the model.
First, the dataset is n preprocessed. The images of the dataset are converted from
BGR(blue, green, red) to RGB(red, green, blue) format. Now The dataset is split into
train and test dataset 85 percent and 15 percent respectively. The images are resized to
224*224 size for the Densenet model. Next, we create MULTI LABELS for the images .To
create multi labels, we use logical OR between adjacent images. The image which is
diagnosed with Severe Diabetic Retinopathy (id = 3) will have its multi labels as [1 1 1 1
0]. In order to further improve the dataset quantity , we augment the dataset by
Flipping the images horizontally . Flipping the images vertically . Fill mode = Constant.
Random zooming of the images by 0.15.

#Conclusion
The paper presented a deep learning approach to detect diabetic
retinopathy. The system utilizes a DenseNet powered training model, which
can be utilized for quick identification of Diabetic Retinopathy. The system
at first identifies the prominent features of the input retina image. On the
basis of the features , the system predicts the type of retinopathy based
upon its training. The results indicate that the proposed system can
successfully detect the type of retinopathy with accuracy between 96-98(in
percentage) based on different stages of the disease. Further, the initial
results of disease prediction also shows a good agreement with actual
results given by clinicians. The future work includes to get or create a better
dataset for class 3 and 4 of the model. Overall the system will help in
detecting the type of retinopathy and based on the results, the patients can
be given proper medication based on the seriousness of the disease.
