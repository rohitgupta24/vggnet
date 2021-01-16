# vggnet
VGG16, VGG19 

It gives better result than resnet in some cases.

VGGNET : 2convo_1maxpooling_2convo_1maxpooling_3convo_1maxpooling_3convo_1maxpooling_3convo_1maxpooling_3fc
         (2-1-2-1-3-1-3-1-3-1-3fc)and Softmax in end to give 1000 outputs

         1000 results(Imagenet Database)
         Image input: 224*224*3 
If stride is 2*2 than resultant image will be half of input image ([ (n+2p-f)/s]+1). If stride is 1,than resultant image will be same.

Alexnet and VGGnet both are deep NN but there is no problem of Vanishing gradient because they uses Relu.
Alexnet have different combos of padding and strides but in VGG these things are more consistent,for Convo stride is 1_1 and for MP stride is 2*2


Dataset : https://drive.google.com/drive/folders/1vdr9CC9ChYVW2iXp6PlfyMOGD-4Um1ue