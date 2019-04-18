
![alt text](https://github.com/fernandeslouro/classic-cars-classifier/blob/master/cars-outline.png?raw=true)

The purpose of this project is to develop a deep learning classifier capable of distinguishing between pictures of three models of classic car:
* Volkswagen Beetle
* Citroen 2CV
* Renault 4 GTL

### Technologies
* Python
* Pandas, Jupyter
* fastai
* Heroku
 
## Project Description
The pictures were scraped from Google Images and labeled by hand. The data consists of around 700 images for each model of car, and I've labeled around 50 pictures for each model of car.

A Heroku web application was also developed, capable of classifying pictures uploaded by the user between one of the three classes (it can tell the model of the car, provided it's one of the three mentioned above).

## To-Do List
- fixing the web app (it's currently broken)
- add a fourth class, "other", which includes random cars not corresponding any of these models.
