# BotOA
What is BotOA?  
It's the acronym for Open Attestation Bot.   
The bot's role is to answer any questions that one may have pertaining to the your journey to onboard Open Attestation.

### Create Telegram Bot  
You can find details on creating a new bot [here](https://core.telegram.org/bots#6-botfather)   
Take note of the __token__ string that is generated,as it will used in the next steps.

### Deployment in DiaglogFlow  
Clone a copy of the source code onto your local machine.
Create a ZIP file that comprises of:  
1. __entities__ folder  
2. __intents__  folder  
3. __agent.json__ file  
4. __package.json__ file  

Go to [DialogFlow](https://dialogflow.cloud.google.com)  
Select 'Create new agent'

Go to __Settings__  
Select *Export and Import* > *RESTORE FROM ZIP*  

Go to __Integrations__  
Select the *Telegram* toggle button  
Paste the Telegram token that was issued during the Bot setup.  

### Ready for testing
You are now ready to chat with your bot on telegram