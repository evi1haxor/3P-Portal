## Abstract
Going with the theme, the project has been visioned in a way that it serves with a solution for prediction and suggests appropriate remedies to the problems been put. Moreover, the solutions in our idea are  planned in a way that ultimately the city on which the system will get implemented, gets a touch of a smart city.

## 3P-Portal

It's going to be a website which shall serve with following services-


### Prevention
*Prevention is better than cure.*<br>
It's been planned to open a web portal as **Community Complaint Portal (CCP)** with a form accessible to be filled by common people who might be living in some sufferings. People can upvote or downvote the request as per required. (Although not all inputs are meant to be publicised, authority can moderate the public requests.) Sufferings may vary from, say flaw in drainage system in some areas to any other problem in general. Then these CCP Complaints shall get delivered to authorised body for it. It can help to prevention from many calamities like epidemics, flooding etc. And act beforehand in order to avoid the unwanted conditions. <br>
### Protection
Using services available on *Azure*, we are also trying to include services like SOS messages, urgent emergency messages to the autorities. Such features could be used by the people who have certain information about it, example suppose you see an old building falling down and realise that there is a possiblity that their could be poeple inside it, in such case you can use the feature and your one click would notify all necessary departments on an alert notice to work immediately. <br>
### Prediction
We are also trying to add some general services like weather forcasting and suggestions about the day, example like *"In Jodhpur today temperature can break the bars of colum so better carry a water bottle with you"* or maybe *"It is going to be a very heavy rain. Going out is not adviceable."*

# Installation and running

Run following script for setting the app up.
```
git clone https://github.com/evi1haxor/3P-Portal.git
cd 3P-portal
python manage.py makemigrations
python manage.py migrate
python manage.py runserver 8080
```
You're now good to go. Now open https://localhost:8080/ to see it working.
