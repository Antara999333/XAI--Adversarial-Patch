# For this Assignment, I have created an adversarial patch which was the result of merging patches for the goldfish class and the lipstick class. This patch, when applied to an image will cause the image to be missclassified. 
The result largely depends on which of the tw patches, the goldfish or the lipstick have a greater influence on the patch during inference. 

## Here are the individual patches used for goldfish and Lipstick classes.

1. Goldfish - ![](goldfish.png)



2. Lipstick - ![](lipstick.png)

## Merged Patch 
![](combined_patch.png)


## The model predicted the patch to be 'Goldfish' - "Predicted class for adversarial patch: goldfish"
