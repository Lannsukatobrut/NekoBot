**😼 NekoBot | 1.4.0** | ***create by AxellNetwork***

```> Simple WhatsApp bot Using Library Baileys```

 ![Logo](https://files.catbox.moe/8mek19.jpg)
=

```javascript
{
  message: Message { conversation: '>_ Welcome to 𝓂𝒶𝒹𝑒 𝒷𝑜𝓉 - 𝒞𝒽𝒾𝑜' },
  type: 'conversation',
  msg: '>_ Welcome to 𝓂𝒶𝒹𝑒 𝒷𝑜𝓉 - 𝒞𝒽𝒾𝑜',
  isMedia: false,
  key: {
    remoteJid: '6283111036395@s.whatsapp.net',
    participant: '6283111036395@s.whatsapp.net',
    fromMe: false,
    id: '5780C33F89C0BE600B6D71DF79C4FC02'
  },
  cht: '6283111036395@s.whatsapp.net',
  fromMe: false,
  id: '5780C33F89C0BE600B6D71DF79C4FC02',
  device: 'android',
  isBot: false,
  isGroup: false,
  participant: '6283111036395@s.whatsapp.net',
  sender: '6283111036395@s.whatsapp.net',
  mentions: [],
  body: '>_ Welcome to 𝓂𝒶𝒹𝑒 𝒷𝑜𝓉 - 𝒞𝒽𝒾𝑜',
  prefix: '',
  command: '>_',
  args: [ 'Welcome', 'to', '𝓂𝒶𝒹𝑒 𝒷𝑜𝓉 - 𝒞𝒽𝒾𝑜' ],
  text: 'Welcome to 𝓂𝒶𝒹𝑒 𝒷𝑜𝓉 - 𝒞𝒽𝒾𝑜',
  isOwner: true,
  download: [AsyncFunction (anonymous)]
}
```
## ⚙️ Settings Bot ***( settings.js )***

```javascript
const fs = require('node:fs');

const config = {
    owner: ["6283111036395"],
    name: "𝓂𝒶𝒹𝑒 𝒷𝑜𝓉 - 𝒞𝒽𝒾𝑜",
    sessions: "sessions",
    sticker: {
      packname: "𝓂𝒶𝒹𝑒 𝒷𝑜𝓉 - 𝒞𝒽𝒾𝑜",
      author: "𝓂𝒶𝒹𝑒 𝒷𝑜𝓉 - 𝒞𝒽𝒾𝑜"
    },
   messages: {
      wait: "*( Loading )* Tunggu Sebentar...",
      owner: "*( Denied )* Kamu bukan owner ku !",
      premium: "*( Denied )* Fitur ini khusus user premium",
      group: "*( Denied )* Fitur ini khusus group",
   },
   database: "neko-db",
   tz: "Asia/Jakarta"
}

module.exports = config
```


## 👨‍💻 How to install/run


```bash
 git clone https://github.com/AxellNetwork/NekoBot
 cd nekoBot
 npm install
 npm start
```

## ☘️ Example Features
Berikut cara menambahkan fitur pada bot ini

## 1. Plugins

```javascript

module.exports = {
    command: "tes", //- Nama fitur nya
    alias: ["tesbot", "testing"], //- Short cut command
    category: ["main"], //- Kategori Fitur 
    settings: {
        owner: false, //-  Apakah Fitur ini khusus owner ?
        group: false, // - Apakah Fitur ini khusus group ?
     },
    description: "Tes bot saja", //- Penjelasan tentang fitur nya
    loading: true, //- Ingin menambahkan loading messages ?
 async run(m, { sock, Func, Scraper, text, config }) {
    m.reply("> Bot Online ✓")
  }
}
```
## 2. Case

```javascript
case "tes" : {
     m.reply("> Bot Online ✓")
   }
break
```
## 📢 Discussion 
Jika ingin mengenal seputar Script ini lebih dalam lagi
silahkan mampir ke komunitas kami[![WhatsApp Group](https://img.𝓂𝒶𝒹𝑒 𝒷𝑜𝓉 - 𝒞𝒽𝒾𝑜)](https://ch𝓂𝒶𝒹𝑒 𝒷𝑜𝓉 - 𝒞𝒽𝒾𝑜)
[![WhatsApp channel](https://img.𝓂𝒶𝒹𝑒 𝒷𝑜𝓉 - 𝒞𝒽𝒾𝑜)](https://𝓂𝒶𝒹𝑒 𝒷𝑜𝓉 - 𝒞𝒽𝒾𝑜)

