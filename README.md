<img width="150" height="150" align="right" style="float: right; margin: 0 10px 0 0;" alt="music_disc" src="https://i.imgur.com/JWSIlSt.png">

# Music Disc 

<a href="https://github.com/hmes98318/Music-Disc/releases"><img alt="GitHub package.json version" src="https://img.shields.io/github/package-json/v/hmes98318/Music-Disc?style=for-the-badge"></a> 
<a href="https://discord.js.org/"><img src="https://img.shields.io/badge/Discord.JS-v14-blue?style=for-the-badge&logo=DISCORD" /></a> 
<a href="https://nodejs.org/"><img src="https://img.shields.io/badge/Node%20Version->=16.13.0-brightgreen?style=for-the-badge&logo=Node.js"></a> 
<a href="https://github.com/hmes98318/Music-Disc/blob/main/LICENSE"><img alt="GitHub" src="https://img.shields.io/github/license/hmes98318/Music-Disc?style=for-the-badge&color=brightgreen"></a>  

### Discord.js v14 Music Bot  
Supports **YouTube**, **Spotify**, **SoundCloud** streams.


### Reference version  
[**node.js  `v18.12.1`**](https://nodejs.org/en/)  
[**discord.js  `v14.6.0`**](https://www.npmjs.com/package/discord.js)  


## Deploying with node.js

### Clone the repository
```
git clone -b v1.2.3 https://github.com/hmes98318/Music-Disc.git
```
or [**click here**](https://github.com/hmes98318/Music-Disc/releases) to download  


### Install the dependencies
auto install all dependencies on [`package.json`](./package.json)  
```
npm install
```

### Configure Files
[`.env`](./.env) 
```env
TOKEN = "your_token"
```

[`config.json`](./config.json)  
```json
{
    "name": "Tuness",
    "prefix": "+",
    "playing": "+help | music",
    "color": "#FFFFFF",
    "defaultVolume": 50,
    "autoLeave": true,
    "displayVoiceState": true,
    "port": 33333
}
```
**`autoLeave`** : After the music finished, can choose whether let the bot leave voice channel automatically or not.  
**`displayVoiceState`** : Show voice channel status updates.   

## Running the script 
```
node index.js
```
