<img src="https://github.com/RobbiDev/imagine-dragons.js/blob/main/lib/img/imaginejs.png" alt="logo">

<p align="center">
   <a href="https://github.com/git/git-scm.com/blob/main/MIT-LICENSE.txt"><img alt="GitHub" src="https://img.shields.io/github/license/echogronkowski/imagine-dragons.js"></a>
   <a href="https://www.npmjs.com/package/imagine-dragons.js"><img src="https://img.shields.io/npm/v/imagine-dragons.js" alt="NPM package"></a>
   <a href="https://github.com/EchoGronkowski/imagine-dragons.js"><img src="https://img.shields.io/badge/state-pre--release-yellow" alt="state"></a>
</p>

<p align="center">
  <a href="#about">About</a> •
  <a href="#prerequisites">Prerequisites</a> •
  <a href="#usage">Usage</a> •
  <a href="#links">Links</a> •
  <a href="#compatible-with">Compatible With</a> •
  <a href="#credits">Credits</a> •
  <a href="#license">License</a>
</p>

# About

Imagine-dragons.js is a [NodeJS](https://nodejs.org/en/download/current/) library that utilizes the Unnecessary Libraries [ImDragonsAPI](https://github.com/unnecessarylibs/ImDragonsAPI). Making it easier for Developers to instantly find any information regarding the band of "Imagine Dragons". Making a simple way to index though the mass amounts of Data the API has to offer.

# Prerequisites

- [NodeJS](https://nodejs.org/en/download/current/)
- Basic Javascipt Knowledge

# Usage

Installing the Library within a NodeJS enviorment

```bash
# Run this to install imagine-dragons.js locally to your repository. 
$ npm install imagine-dragons.js --save

# Run this instead to install imagine-dragons.js globally so you can use it anywhere.
$ npm install imagine-dragons.js -g
```

This example is Creating a new Indexer class, thats sends a **GET/request** to the ImDragonsAPI looking for the **"band"** Collection. Once we Recieve the collection we can index throught it and we can find the Band Details.


```javascript
// Import Imgaine-Dragons.js
import { Indexer } from "imdragons.js"

// Create a New Indexer
const indexer = new Indexer('band')

// Show JSON Data 
console.log(indexer)
```

Expected Output should be as follow

```json
  "details": {
        "origin": "Las Vegas, Nevada, United States",
        "years active": "2008-present",
        "genres": [
            "Alternative rock",
            "Indie rock",
            "Electronic rock"
        ],
        "labels": [
            "Interscope Records",
            "KIDinaKORNER"
        ],
        "members": [
            "Daniel Samardžić",
            "Dan Reynolds",
            "Ben McKee",
            "Wayne Sermon",
            "Daniel Platzman"
        ]
    }
```

# Links

- [Github](https://github.com/RobbiDev/imagine-dragons.js)
- [npm](https://www.npmjs.com/package/imagine-dragons.js)
- [ImDragonsAPI](https://github.com/unnecessarylibs/ImDragonsAPI)
- [Unnecessary Libraries Discord](https://discord.gg/y8TYje4PXH)

# Compatible With

- [Discord.js](https://github.com/discordjs/discord.js)
- [Spotify Web API](https://github.com/jmperez/spotify-web-api-js)

# Credits

- [RobbiDev](https://github.com/pengyofficial) - Lead Programmer
- [Unnecessary Libraries](https://github.com/unnecessarylibs) - Organizer

# License

MIT
