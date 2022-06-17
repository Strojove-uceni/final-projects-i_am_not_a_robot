# Instruction and Evaluation

You can get maximum 100 points. Team with the highest score receives the prize. Final projects will be evaluated accordingly:

* **Idea (0-40 points)**
anything from Machine learning, own idea guarantees you at least 20%
if you have no Idea for your project, we can give you some (deducting 20% from your "idea" score)

* **Implementation (0-30 points)**
    upload your code (preferably in Python) on GitHub by 2.1.2022 23:59
    include working demo in Colab (clearly demonstrate your results)
    
* **Presentation (0-30 points)**
     present your project during the last Lab session on 6.1.2022
     duration 20 min., (PowerPoint/Beamer/...)

# Project
Finding optimal optical character recognition for CAPTCHA codes(images).

Files description:

* create_dataset.ipynb - for creating datasets used in project 

* captcha_model.ipynb - main model for captcha recognition 

* captcha_model_2.ipynb - same model as in captcha_model.ipynb, but instead of loading training data it creates dataset locally and these data are replaced with new one every couple of iteration

* results.ipynb - trained networks are loaded from google drive (or can be found in github folder models) and demo files of captcha codes are evaluated on these newtorks (demo datasets also in google drive or in folder samples)
