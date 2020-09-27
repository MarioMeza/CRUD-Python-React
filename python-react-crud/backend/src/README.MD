# INSTALLATION OF LIBRARIES FOR Python Flask

## Virtual VENV

*Install Virtual ENV* 

**LINUX**

´´´
python3 -m venv tutorial-env

´´´
**WINDOWS**

´´´

python -m venv tutorial-env

´´´

**and finally activate env with command:**

´´´
tutorial-env\Scripts\activate

´´´

[Link](https://www.mongodb.com/try/download/enterprise?tck=docs_server)


## INSTALATIONS PACKAGES PIP

 ```
pip install -r requirements.txt

 ```
## INSTALATIONS PACKAGES PIP

Run application:

´´´ 

python app.py

´´´

## INSTALATIONS MongoDB for WINDOWS

[Link](https://www.mongodb.com/try/download/enterprise?tck=docs_server)


## Commands Mongo

**Run MongoDB**
´´´

mongod

´´´

**Console mongoDB for queries:**

´´´

mongo

´´´

**Open new console for show DataBases**

´´´

show dbs

´´´


**Use database**

´´´
use name_database

´´´

**Show all collections**

´´´
show collections

´´´

**Show dates collections**

´´´

db.users.find().pretty()

´´´
