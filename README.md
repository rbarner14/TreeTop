# TreeTop
Track your family story.  Share photos, videos and events safely with your loved ones.

## Table of Contents
* [Overview](#overview)</br>
* [Tech Stack](#techstack)</br>
* [Setup/Installation](#installation)</br>
* [Demo](#demo)</br>
* [Future Development](#future)</br>

<a name="overview"/></a>
## Overview
TreeTop was inspired by my struggle in documenting stories of my ancestors and sharing information between my family members and me privately.  With my app, users can:

* Create profiles of their name, age, photo, occupation, marital history and residence.
* Organize family reunions, gatherings and conferences.

<a name="techstack"/></a>
## Tech Stack
**Frontend:** JavaScript (AJAX, JSON, React), Jinja, jQuery, Bootstrap</br>
**Backend:** Python, Flask, SQLAlchemy, PostgreSQL<br/>
**Libraries:** D3, Chart.js, Pandas, Scikit-learn<br/>
**API: Google Maps, Spotify** <br/>

<a name="installation"/></a>
## Setup/Installation
On local machine, go to desired directory.  Clone protag repository:
```
$ git clone https://github.com/rbarner14/protag.git
```
Create a virtual environment in the directory:
```
$ virtualenv env
```
Activate virtual environment:
```
$ source env/bin/activate
```
Install dependencies:
```
$ pip install -r requirements.txt
```
Create database:
```
$ createdb music
```
Build database:
```
$ python3 -i model.py
>>> db.create_all()
```
Seed database:
```
$ python3 -i seed.py
```
Run app:
```
$ python3 server.py
```
Navigate to localhost:5000 in browser.

<a name="demo"/></a>
## Demo

**Create family as admin.**
<br/><br/>
![Homepage](/static/images/readme/homepage.gif)
<br/>


**Thanks for exploring!**

<a name="future"/></a>
## Future Development
* Experiment with security.
* Incorporate face recognition technology.