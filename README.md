# Zly.js
Zly.js is a light-weight Discord Bot framework that takes heavily customization, command handler(s) and much more, and makes it easy for the developer to apply.

#### Getting Started
1) Open your conole.\
This, of course, can be `bash`, `cmd`, `powershell`, `zsh`, anything. As long as you can reach `node` and `npm` you're set.
2) Install `Zly.js`.\
In your currently open console, type the following command.
```bash
# If you're the stable type of person: 
npm install zly.js@latest
# But if you live life on bleeding edge and want newer features faster at the price of stability:
npm install github:3STEB4N28/Zly.js
```
3) Open your IDE and create a new Project/file.\
This is the oart where you question if you really should've went into Development and Programming.\
Create a new JavaScript file, name it `index.js`, or `bot.js` or anything of the sorts,
and paste this content below as if you're pasting a answer from Stack Overflow.
```javascript
const { Intents} = require('discord.js');
const { Client } = require('zly.js');

let bot = new Client({
    prefix: '-'
}, {
    ws: { intents: [Intents.NON_PRIVILEGED]}
});

bot.build('Discord Bot Token');
```
4) Then run `node filename.js`, replace `filename.js` with the name of the file you just pasted the above code to, and after that if there is no errors, you're set! You may want to take a look at the [documentation](https://zly.3steb4n28.xyz)!

#### Extras
- [More Examples](https://github.com/3STEB4N28/Zly.js/tree/Examples)
- [Support Server](https://discord.gg/)
- [Github](https://github.com/3STEB4N28/Zly.js)
