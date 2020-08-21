<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Can I get through?
*[Pau Navarro]*

*[Data Analytics | Barcelona | June, 2020]*

## Content
- [Project Description](#project-description)
- [Questions](#hypotheses-questions)
- [Dataset](#dataset)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Organization](#organization)
- [Links](#links)

## Project Description
For this project I entended to generate a deep learning algorithm that was capable of identifying whether there was a ramp or not on a certain sidewalk image, to automatically assess the accessibility of a certain city or even a certain route. Also, to avoid mistakes, I generated an algorithm capable of identyfying whether the image contained a sidewalk or not, but due to time constrains I was not able to deploy it fully.

## Questions
* Can we automatically assess sidewalk accessibility by feeding the computer with Google StreetView images?

## Dataset
I created a database with around 430 images of sidewalks with ramp and with no ramp. After gathering those images, I used data augmentation techniques to generate a pool of aroung 2.100 images.

## Model Training and Evaluation
I used the ResNet50 model, with a training sample of 1.500 images. After the training, I evaluated my accuracy by comparing it to related projects.

## Conclusion
* I obtained an accuracy of around 50%. I should use bigger databases.

## Future Work
For future tasks, I should try to increase my accuracy by getting bigger samples and testing different algorithms, contemplate more barriers a sidewalk can have than just having no ramp and adress other questions handicapped people face when planning a trip to an unknown city.

## Organization
First, I researched about the topic and looked for a database. After realizing that I did not have one, I created it myself with Google StreetView. Then, I studied what kind of algotirthms could work best and started training the ResNet50 model and tested its accuracy.
Due to storage issues, the trained models cannot be uploaded to Github. Should you want to retrain the model or are curious about it, do not hesitate to contact me through navarrog.pau@gmail.com.

## Links
Here are some useful links:

[Repository](https://github.com/paunavarrogaspar/Project-Week-8-Travelling-With-Wheelchair/) 
[Slides](https://slides.com/paunavarro/project/fullscreen/)  
[Trello](https://trello.com/b/3i6JNUNE/projectweek8)  
