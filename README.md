# Submitted by - Ritij Raj
# Roll No- 24/SE/144

## APPROACH-
### FasterRCNN + CLIP

- I am using FasterRCNN for its robust object detection capabilities and CLIP (Contrastive Language-Image Pre-training) for its dual-encoder model that takes both images and natural language text as input.
- Instead of using a traditional, fixed-class classifier in the Faster R-CNN's detection head, I integrated the outputs of CLIP. The visual features extracted by CLIP's vision encoder are used by the RPN to propose regions. The text query, encoded by CLIP's text encoder, provides the semantic target for the detection head. This allows the model to search for and localize objects based on a free-form text query, not just a predefined list of classes.


## KAGGEL NOTEBOOK LINK

**https://www.kaggle.com/code/ritijraj/finaldraft**

## Things present in the repository
- weights and biases of the trained Frcnn
- Downloaded Notebook

  
