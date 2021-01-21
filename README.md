# Image Classifier to Identify Dog Breeds
Application uses pretrained CNN models.

Application uses pretrained CNN models.
- AlexNet
- VGG
- ResNet

## Project Components
1. check_images	-main program function
2. get_input_args -function to retrive command line arguments
3. get_pet_labels -creates the results dictionary
4. classify_images -runs classfier and creates classifier labels
5. adjust_results4_isadog -adjusts the results dictionary to check if classifier correctly classified images as 'a dog' or 'not a dog
6. calculate_results_stats -calculates results of run and puts statistics in the Results Statistics Dictionary - called results_stats
7. print_results -prints summary results, incorrect classifications of dogs (if requested) and incorrectly classified breeds (if requested)

## Packages
Project uses python 3, time, ast, PIL, torch, torchvision,

## Model
Application uses the following pretrained CNN models.
- AlexNet
- VGG
- ResNet

## License
Files listed in the Project Components section above are a public domain work, dedicated using [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Feel free to do whatever you want with it. All other files in this repository are not for any commercial use.
