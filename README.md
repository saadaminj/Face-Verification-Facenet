# Face-Verification-Facenet
I have built a face verification program with the help of keras built-in model called 'FaceNet' and MTCNN. 
Keras Facenet model is used for creating image embeddings of input 3 dimensional image.
MTCNN is used for extracting images from input images.
after extracting faces and their embeddings, the distance function is used to calculate distance between two face embeddings.
if the distance is above a threshold then the classifier states that two faces are of different person's.
