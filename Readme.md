# Slack Bot For Github Configuration Guide 
<!-- Place this tag where you want the button to render. -->
<html>
<head><script async defer src="https://buttons.github.io/buttons.js">
<body>	
<a class="github-button" href="https://github.com/Dhiraj240/Slack-Test" data-size="large" data-show-count="true" aria-label="Star Dhiraj240/Slack-Test on GitHub">Star</a>
</script>
</body>
</head>
</html>

It is highly recommended to setup a virtual environment.
You can follow [This link to install virtualenv!](https://virtualenv.pypa.io/en/latest/installation/) 
After that typein :

```
virtualenv <-any environment-name-you-want>

For me i wrote :
virtualenv env
```

## Activate your environment

```
env\scripts\activate
```
As my environment name was ```env``` so i used this prefix with above command.
For you it can be anything :+1:

## Install requirements

```
pip install -r requirements.txt
```

## Set Slack Bot Token

```
set SLACK_BOT_TOKEN=xxxxxxxxx
```
Here ```xxxxxxxxxx``` is your slack bot token

## Run Below Script 

```
python bot_id.py
```
You will get a ```BOT_ID``` which will be generated automatically by the above script.

## Set BOT ID

```
set BOT_ID=xxxxx
```
Here ```xxxxx``` is your generated BOT_ID from the above script

## Run Below Script

```
python army_brat.py
```

## Note

###### The commands you are executing must be done in a virtual environment because this project has different dependencies and if you do not follow it, then there may be the case that it can hamper your someother project.