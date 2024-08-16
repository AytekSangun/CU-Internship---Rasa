This is an AI Assistant demo developed on Rasa Open Source for our intership porject.

# How to Use Rasa

## 1. Python Environment Setup

    First you should check your python and pip versions.



    If these packages are already installed you should see your version numbers.
    If not you have to install the supported version of the Python. We used Python 3.8.0 for our project but you should check which versions are supported at the time.
    
## 2. Virtual Environment Setup

    Create a new virtual environmet fort he project. If you don’t use virtual environment thing will get messy.


    To activate your virtual environment:


## 3. Installing Rasa

    To install Rasa Open Source:


    After the installation of the Rasa, you can create a new project with this command:


## 4. Preperation of Rasa Files

    You should prepare your data for at least these three files:

    NLU.yml
    In this file you will add all your examplary sentences for certain intents of the users. You will also add these custom intents to the domain.yml file.
        
    
    Stories.yml
    This file is where Rasa make decisions what will it do for certain sceneraios. If you want to make a complex AI Assistant, you can also use actions.py to add different features. If you want your AI should only respond with your given sentences, you should use predefined “utter” function in the domain file.
    
    Domain.yml
    This is where your Rasa actually works. Every intent you defined in the nlu.yml file should be in the domain. You will use predefined “utter” function for bot responses.
    

## 5. Training Rasa

    After you done with the files you will use:
    
       
    
    Your trained model will be inside of the Models folder.


## 6. Testing Your Model

    You will use this command to communicate with your bot:
    
