# Financial Services Rasa Voice Bot

This is an example voicebot demonstrating how to build AI assistants for financial services and banking. This starter pack can be used as a base for your own development or as a reference guide for implementing common banking-industry features with Rasa. It includes pre-built intents, actions, and stories for handling conversation flows like checking spending history and transferring money to another account.


## Install dependencies

Run:
```bash
pip install -r requirements.txt
```

## Run the bot

Use `rasa run -m models --endpoints endpoints.yml --port 5002 --credentials credentials.yml` to train a model.


In a seperate shell, run:
```
python Voicebot.py
```

## Overview of the files

`data/nlu/nlu.yml` - contains NLU training data

`data/nlu/rules.yml` - contains rules training data

`data/stories/stories*.yml` - contains stories training data

`actions.py` - contains custom action/api code

`domain.yml` - the domain file, including bot response templates

`config.yml` - training configurations for the NLU pipeline and policy ensemble

`tests/` - end-to-end tests


## Things you can ask the bot

P0: The voice bot conversing with a customer to sell a credit card.<br/>

P1 : The voice bot conversing with a customer to gather user feedback on a specific topic (ex. New feature in the app, new industry news, focused customer survey, etc.)<br/>

P2 : The voice bot conversing with a customer to address a specific issue related to an ecommerce order<br/>

P3 : The voice bot conversing with a customer to check why the customer has not paid his credit card dues, and suggest suitable follow-up options<br/>



