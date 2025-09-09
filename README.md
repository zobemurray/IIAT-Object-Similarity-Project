## Object Similarity Project
### Project Summary
We wanted to developed a tool to support neuroscientific and psychological research at our school, helping researchers better understand 
how the human brain processes and categorizes images. To facilitate this tool, we created two Convolutional Neural Networks (CNNs) modified to 
conduct pairwise comparisons between inputted images.

### What does the program do?
1. The program prompts the user for a file path leading to the greyscale images the user wants to be analyzed
2. The program will then prompt the user to choose which model they want to be used for the analysis (VGG16 or ResNet50) and the names they want
for the csv and heatmap output files
3. The chosen model is then trained on ImageNet parameters and produces feature data from VGG16's first fully connected
   layer and ResNet50's final global pooled feature vector
4. This data is then used to make similarity comparison data through cosine similarity and is output to users via heatmap and csv file
