# Comparing the Saliency of Semantic Parts of Deep Convolutional Neural Network with Human Vision Through Representation Similarity Analysis

## Abstract
Humans' ability to recognize objects from only a few semantic parts of them demonstrate the importance of semantic parts in forming intermediate representations. Deep Convolutional Neural Networks (DCNNs) though achieve unforseen success in object image classification tasks, has been criticized for their inability to make inferences based on a global intermediate representation. In this paper, we examine the saliency of semantic parts as an intermediate representation of DCNNs by comparing how DCNNs' responses vary when each of the semantic parts are omitted from the original image. We then uses representation similarity analysis (RSA) to compare this intermediate representation with that of human obtained through a ranking experiment. Our results show that DCNNs' representations have a substantial similarity with that of human. Additionally, we propose using RSA and comparing with human representations as a potential method for studying intermediate representation of DCNNs. 

## Description
This the public repository for the project: "Comparing the Saliency of Semantic Parts of Deep Convolutional Neural Network with Human Vision Through Representation Similarity Analysis". Only stimulus we use are avaliable at this point because of copyrights. The unpeer reviewed version of the paper will be avaliable as soon as it is submitted the first/second week on December and the published version would be avaliable after it is accepted by CVPR/CVPR workshops. We will also update the analysis and plots soon after the paper is accepted. 

## Rdms Visualization
Our Representation Dissimilarity Matrices (Rdms) and raw data will also be avaliable in this repository. Sample Rdms:
<img src= plots/Rdms.png width="400" height="400" /><br>
Top Left: Last Convolutional Layer<br>
Top Right: First Convolutional Layer<br>
Bottom Left: Prediction Layer<br>
Bottom Right: Human’s Prediction<br>


## Stimuli Visualization
Full image<br>
<img src= plots/full.png width="200" height="200" /><br>
External part deletion<br>
<img src= plots/2008_003519_white_Deleted_Head.png width="200" height="200" /><br>
Internal part deletion<br>
<img src= plots/2008_003519_white_Deleted_LeftEye.png width="200" height="200" /><br>
