# PERSONALITY TYPE ANALYSIS

Website to predict which telivision character matches your personality based on Machine Learning data from openpsychometrics.org.

I was searching through some cool projects on personality prediction one-day when I came across thiw website openpsychometrics.org that houses open-dataset about personality prediction.
This website will allow to you to slide through 20 different personality assets and then come up with a match for your favourite character from fiction works.
An interactive character-matching website based on machine-learning and personality prediction using Logistic Regression from sklearn.

<h1>Go and checkout which character matches your personality!</h1>
The dataset contains 800 characters and one will be mapped to one particular match based on the inputs of personality scores.

<h2>Website hosted</h2>
Website is hosted at <a href="https://your-character.herokuapp.com">Link to website</a>

![image](https://user-images.githubusercontent.com/72940291/139533289-c38e19a2-8d05-48cd-8ccc-3c07127c2606.png)

![image](https://user-images.githubusercontent.com/72940291/139533300-5bc6c84c-e649-4a3f-8149-df2d933bdf6b.png)

<h2>Functionality</h2>
The entire website has been made from Django framework and is hosted on Heroku. <br>
Images have been fetched from <a href="https://openpsychometrics.org/tests/characters/test-resources/pics/">Link</a>.<br>
Trained .ipynb file and added resources can be found in training directory.

<h2>Dependancies</h2>
<ul><li>Required modules can be found in requirements.txt</li><li>Run on your local machine using <pre>python manage.py runserver</pre></li>
<li>Script uses Gunicorn to work with .wsgi files</li><li>Python 3.7 is preferred</li></ul>
