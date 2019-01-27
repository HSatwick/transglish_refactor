# transglish_refactor
Transglish is developed using Python (Django Rest Framework) and Angular v7. 
The Angular front-end is build using ng build --prod and the dist folder is then integrated with Django Framework. 

SQLite is used to store the data. 

## How to Install and Run

Create a virtual environment in a dedicated folder where you want to clone the project

<code>λ virtualenv env</code>

Once the environment is set, we need to download the repo from the remote repo.

<code> λ git clone https://github.com/HSatwick/transglish_refactor.git  </code>

Once the project is downloaded, activate the virtual environment. Once you activate the virtual environment, run the requirements file, which you'll find in the project folder.

<code> λ pip install -r transglish_refactor\requirements.txt </code>

On installing the requirements, you'll have to make a small change in the googletrans folder, that exists in 
env/lib/site-packages.<br>
Replace the googletrans folder that exists in site-packeges with the one from the repo.

cd into the transglish_refactor folder and run the following command

<code> λ py manage.py runserver </code>

The application should start on localhost:8000. 
