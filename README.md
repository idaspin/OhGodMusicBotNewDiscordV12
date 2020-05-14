# OhGodMusicBot
A v12 Discord.JS music bot in 140 lines with Search
> Пример музыкального бота с поиском по YouTube для Discord.js версии 12
> Подробное описание работы в видео по ссылке: [Музыкальный бот Discord.js](https://youtu.be/MSOtiOMe4JE)

## Installation (Windows)

This section is for running the bot locally on Windows. If you're on Mac it should be similar. I'll assume Linux users can figure it out.
> Установка Windows: если запускаешь бота локально со своего компьютера. Инструкция более менее идентична как для Windows, так и для Мака и Linux.

### Download Node.js

Node.js is what will be used to run the bot.
Download [Node.js 14.X from the website](https://nodejs.org/en/).
> Необходима установленная Node.js версии 12+

### Install Node.js

Open the Node.js Setup.
In the options, make sure `Node.js runtime` `npm package manager` and `Add to PATH` are enabled. After that install Node.js.
> Установка ноды. Убедись, что установлен NPM, а сама нода добавлена в переменную среды ОС.

### Download Git

And install it. The website is http://git-scm.com and make sure you choose "for command prompt".
> Установи git и клонируй проект.

### Download FFMPEG

Download FFMPEG from [this website](https://ffmpeg.zeranoe.com/builds/). Make sure to find the current **Static Build** for your OS Architecture (32bit/64bit).
> Установи глобально FFMPEG (гугл в помощь).

### Install & Configure FFMPEG

Extract the files to the root of your harddrive, and rename the folder to `ffmpeg`. 

**Then add FFMPEG to your Path variable:**

1. `windows key + x`
2. go to system
3. on the left Advanced system settings
4. Environment Variables
5. under System variables find the variable **Path** hit edit
  * Depending on your version of windows you may have a list of entries or a semicolon sperated field of entries. 

**If Windows 10:**

1. Hit the new button on the right
2. add `c:\ffmpeg\bin`

**If older versions of Windows:**

1. add `;c:\ffmpeg\bin` to the end of the field.

### Download and Install OhGodMusicBot

Next you'll need to download the bot and configure it.
Download the master branch and put the unzipped files in a new folder on your computer.
Next rename .json.example to .json and enter the correct information. *Note: You will have to remove any and all comments from the .json.example file, as they are not supported in json. They are there to guide you as you decide how you want to configure your bot*

For obtaining a Discord Bot token, please see [this page.](https://discordapp.com/developers/docs/intro)

Before running the bot you need to install the dependencies.
In the folder you put the files in, Shift+Right click and select open command window here.
In the command prompt type `npm install`.

The bot should now be ready!
Open a command prompt like above and type `npm start` to start the bot and see if it works.

> Далее тебе следует пройти по инструкции из видео [Музыкальный бот Discord.js](https://youtu.be/MSOtiOMe4JE)
> Если не умеешь запускать бота посмотри это видео [Как отслеживать события Discord.JS](https://youtu.be/LsJ7zkVepMc)

### Install dependencies

> Установи модули вроде `discord.js`, `ytdl-core` итп.

**Windows**

Shift-RightClick in the folder that you downloaded and select Open command window here. Then type `npm install` and hit Enter.

**Linux**

cd to where you cloned the GitHub repo and type `npm install`. This will take a while.
