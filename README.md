#### ‼️ This was just some practice training that I did as a proof of concept to myself before I built the actual model for a project involving faces. That repo is much cooler, ~~but it is private so you'll have to enjoy this one instead.~~ I guess the other repo is public too, check that one out instead. 

This repo houses a fairly simple model that uses a Convolutional Neural Network to predict and plot keypoints on faces.

The idea is that we will use this to inform a homography between two "face pictures" so that we can merge the hair of one with the face of another. 

### Dataset 
We're using a subset of the FEI Faces Dataset which only includes frontal images that have been cropped such that the pixel-locations rougly correlate to the same locations on the faces and have been annotated with 46 points each denoting various keypoints on the face.  https://fei.edu.br/~cet/facedatabase.html
