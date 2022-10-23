
# Fire , Smoke : detecion

Exercise with neural network and classification.
The dataset includes approximately 32k images, divided into 3 classes: Fire, Smog, Normal
To find the best results are used 3 models with different parameters: Xception , Resnet , VGG , and compare them 

# Sections  in repository
- Libraries
- Defined all variables
- Section to Images generation - Simple function to generate photos based on other photos and parameters 
![6](https://user-images.githubusercontent.com/67312266/197408582-11f576c0-c479-41ed-8767-bcac211322c8.png)
- Main section to estimate - The section contains code to test the model with test_set and then display results as a heatmap.
![9](https://user-images.githubusercontent.com/67312266/197409835-06a4f257-0c01-4675-a679-5813d86f166b.JPG)


   In order to use that section the model have to be loaded before 
![7](https://user-images.githubusercontent.com/67312266/197409334-ed3b1800-c06d-4dc3-be4d-21596712d895.JPG)



- Comparison of models - section to compare all models and show learning by the model over epochs
![8](https://user-images.githubusercontent.com/67312266/197409779-f604f38f-a6df-4828-9967-904ad0ac0905.JPG)

- Creating and saving models: models created according to docu.
- Detecting fire on a random picture : to be confident that the model works properly one may past link to a random picture and check the results
![13](https://user-images.githubusercontent.com/67312266/197410248-46816d2e-f668-4608-9f71-b948e95bcd06.png)










## Documentation

[Documentation](https://www.tensorflow.org/)

## Authors

- [BartoszTajak](https://github.com/BartoszTajak)
