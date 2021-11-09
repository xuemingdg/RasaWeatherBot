# Rasa WeatherBot

## Introduction

A simple Chinese weather robot (chatbot) built using Rasa (Rasa2.0, Rasa X) based on @luojie1024 's WeatherBot.

## Setup


**1. Clone project and install requirements**

```bash
git clone https://github.com/xuemingdg/RasaWeatherBot.git
cd RasaWeatherBot
pip install -r requirements.txt
```


**2. Train model by running**

```
rasa train
```

**3. Run the raas action server**

```
rasa run actions
```


**4. Open a new terminal and now you can curl results from the server, for example:**

```
rasa x
```
