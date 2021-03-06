# Telegram Bot Template 👨‍💻 
![alt text](https://miro.medium.com/max/1400/1*rK34spWM1alCH4Si5vEKjw.png)
#### A Python Template with a small setup to start building faster your telegram bot and deploy it on Heroku.

#### Steps:

##### ✍️ Download the template and extend it with your code.
##### 👨‍💻 Set up your Heroku App.
##### 🚀👨🏻‍🚀 Get Ready to Deploy it.
##### 🔥 Have Fun!

## Description

Improve your Bot telegram release speed just having a clean set of files and basic functions to get your bot online in less step.

### Files included:

* **_bot.py_**:
The main Python script
* **_Procfile_**:
This file define the starter and what type of application you will deploy.It's used to help Heroku to set the right enviroment for your case.
* **_requirements.txt_**:
This file is used to say Heroku what dependencies you are going to use. At init is just python-telegram-bot

## Getting Started

### Download the repository
```
git clone https://github.com/renato-milano/telegram-bot-template
```
### Dependencies
If you want to test it locally you will need:

* Python
* PIP
* python-telegram-bot

### Installing (Linux)

* Installing Python
```
sudo apt install python3.8
```
* Installing PIP
```
sudo apt install python3-pip
```
**If you are using Windows or Mac check the tons of tutorials/docs on internet to install Python and PIP on your machine :D**

* Installing Python Telegram Bot (Linux/Windows/MacOS)
```
pip install python-telegram-bot
```
### Executing program

Just run the script locally or on Heroku and Telegram will detect the running code.   

## Heroku Deploy
### Setting up Heroku 

* Login on Heroku and Create a new App
![alt text](https://i.ibb.co/FB7rYJj/Schermata-da-2021-10-10-15-49-28.png)
* Go to Settings of your App and add the Python Buildpack
![alt text](https://i.ibb.co/hg5srd4/Schermata-da-2021-10-10-15-51-13.png)
* Click on python and Save Changes  
![alt text](https://i.ibb.co/yW1fGQ6/Schermata-da-2021-10-10-15-51-01.png)
### Deploy 
* You have different options to deploy the code, i usually connect the github repository to use automatic deploy when a commit is sent. 
* To use the same deploy method:
1. Connect your **GitHub Profile** to **Heroku**
2. Connect the app to your **__Github Repository__**
   - In the Deploy page of your app click Connect to GitHub
   - Search for your repository name
   - Click Connect
   
![alt text](https://i.ibb.co/JQ0F7Sv/Schermata-da-2021-10-10-15-50-27.png)

## Authors

Contributors names and contact info

Github [Renato Milano](https://github.com/renato-milano) 

Instagram: [@renatomilano96](https://www.instagram.com/renatomilano96/)

## Version History
* See [commit change](https://github.com/renato-milano/telegram-bot-template/commits/main)

* 0.4
    * ReadMe and Guide improve
* 0.3
    * Comments adde for better code reading
* 0.2
    * Snippet for Image retrieve added
* 0.1
    * Initial Template Release

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, generic infos.
* [python-telegram-bot](https://pypi.org/project/python-telegram-bot/)
* [PIP](https://pypi.org/)
* [Python](https://www.python.org/)
