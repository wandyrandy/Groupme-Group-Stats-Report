# Groupme-Group-Stats-Report 🧮 📊
![Math is fun!](https://media.giphy.com/media/9cpXRPjZuo6pq/giphy.gif)


# Requirements
* [Groupme Developer account](https://dev.groupme.com) 💻
* A Groupme with friends 🏃
* [Python3](https://www.python.org/downloads/) 🐍


# Installation
* Setup a developer account at https://dev.groupme.com and get your OAuth token💥
* Install the [pipenv virtual environment](https://docs.pipenv.org/en/latest/)! This keeps track of our python packages and helps with secret keys 😌
    - It _should_ be as easy as running `pip3 install pipenv`
* Run pipenv & Install Packages:
    - `pipenv shell`
    - `pipenv install --dev`
* Put your OAuth token in a `.env` file. As per this [stackoverflow](https://stackoverflow.com/questions/51227159/how-do-i-set-environment-variables-in-pipenv). Your script will source it.
    - `echo MY_SECRET_TOKEN=WhateverYourTokenIS >.env`


# Development (RANDY)
* Make sure you're in the virtual environment when you're working on stuff!
    - `pipenv shell`
* If you wanna install packages just do:
    - `pipenv install PACKAGE`
    - And when you're done:
        - `pipenv lock`

* Obviously run `git pull` before you push. I'm gonna make my own branch so I don't mess up your stuff too much.
