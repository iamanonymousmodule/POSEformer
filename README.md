# CRACformer
A Cross-attention Convolution Transformer for Human Pose Recognition

# Usage
model = cracformer((width,height),number_classes).to(DEVICE) #(width,height) is the dimesnions of the input images

Different versions of the model can be created by changing the 'num_blocks' and 'channels'
