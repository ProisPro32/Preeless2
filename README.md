# Peerless Scholar Slave

This is a discord bot designed to assist players in their peerless scholar sessions. The bot uses image processing and text recognition to extract information from peerless questions screenshots and then presents the answer in a formatted embed within a Discord channel. In addition there is the possibility to add new pair of questions and answers to the database.

## Required 

1. Python3
2. `.env` file containing:
	```
	APPLICATION_ID=XXX
	GUILD_ID=XXX
	DISCORD_TOKEN=XXX
	...
	```
3. Packages included in `requirements.txt`
5. Download and install Tesseract OCR on your machine and add it to Environment variables

## Installing

1. Create an application and the bot following the official Discord documentation [here](https://discord.com/developers/docs/intro);
2. Add the bot to your server (suggested to test it in a Test Server before using it in the real server);
3. Change the `.env` file values according to the Discord documentation;
5. Edit the `PATH_TO_JSON` variable in `extractor.py`;
6. Edit path to tesseract.exe in `extractor.py`;
7. Start using it.

## Important notes

Attach a screenshot of the question you don't know the answer to in order to get the following response: 

![Screenshot 2023-09-03 111331](https://github.com/TheMaxi7/RoK-discord-bots/assets/102146744/9b5dc0e1-d19d-4d36-b473-dcf07694b9b3)


In case the question is new and the answer is not in the database yet, you can write `add new <question>;<answer>` to add it to the database. Make sure there are no typos in it.

## Disclaimer

The bot can extract questions from different image sizes but for best performances you better attach a screenshot of the question only, like this one:

![imagrfghrthre](https://github.com/TheMaxi7/RoK-discord-bots/assets/102146744/a0aa5e4e-b849-4e70-9d38-0c803f85af34)


## Contact and Support

If you want to reach out to me for any kind of problem/request feel free to add me on discord (@themaxi7).

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Altaro97/Discord-Bots/blob/main/LICENSE) file for details
