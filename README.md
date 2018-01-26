# Interactive Chat Bot

## Description
Implemented chat bot to simulate human like conversation with user as an online help desk for LexisNexis. Built front end using ReactJs which communicates with Microsoft Bot framework using NodeJS back end component. Used NLP & LUIS to identify the intent of the user using key phrase detection. Processed data using Python.

Creating an intelligent bot that will simplify getting relevant information and solving problems.

## Contributors

[Harshal Gurjar](hkgurjar@ncsu.edu), [Abhinav Medhekar](amedhek@ncsu.edu), [Atit Shetty](atit.shetty@gmail.com)

## Microsoft Bot Framework

[Microsoft Resource for Node](https://docs.microsoft.com/en-us/bot-framework/nodejs/bot-builder-nodejs-quickstart)

[Link to bot emulator](https://github.com/Microsoft/BotFramework-Emulator/releases/tag/v3.5.31)

## How to run the application

If .env file present run (sample .env file has been provided)

```node -r dotenv/config app.js```

If .env file not present, set the environment variables present in the file and then run

```node app.js```

## Configurations

LUIS_config.xml is the configuration to set up intents and utterances in Microsoft LUIS website.

output.tsv has been created by parsing Lexis Advance xml. This will be used for NLP processing by Microsoft QNA cognitive service.



