# STVRadio

This github repo will give you the power and info on how to install it and use it for playing music!

## Information

* ⚙️ Slash Only!

* 💻 SSP6904

* 📡 FM/AM

* 🤖 Radio/Music

## Install

To install, use these commands down here:

```
https://git.ttnrtsite.me/SSP6904/STVRadio.git
```

or

```
https://github.com/SSP6904/STVRadio.git
```

Enter into the directory

```
cd STVRadio/
```

Install the dependencies

```
npm install
```

Also, it is importent to keep in mind to install FFMPEG in the manchine or whatever your running this on!

Read more on how to install FFMPEG for your computer or server in the docs in this repo!

## Configuration

After cloning the project and installing all dependencies, you need to add your Discord API token in the config.json file.

Starting the application

```
node index.js
```

Before you can use the bots slash command you first need to add them to your Discord server. 

You can use the ```!deploy``` command to do so.


## Features & Commands

Note: **The repository now uses the new Discord slash commands**

🎶 - Play music from YouTube via url `/play YOUTUBE_URL`

🎶 - Play music from using song name `/play SONG_NAME`

📃 - Pause music `/pause`

🎓 - Resume music `/resume`

💿 - Skip song `/skip`

🔇 - Stop music `/stop`

🔀 - Shuffle Queue `/shuffle`

↕ - Move song position `/move TRACK_POSITION TARGET_POSITION`

↔️ - Swap song positions `/swap POSITION_1 POSITION_2`

⏏️ - Remove song `/remove POSITION`


## Other Commands

▶️ - Now Playing `/nowplaying`

🙋‍♂️ - Get information about a user `/userinfo USER`

⛔ - Ban a player `/ban USER`

⌨️ - Delete the latest chat messages `/purge NUM_OF_MESSAGES`
