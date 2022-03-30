<p align="center">
<img src="https://telegra.ph/file/9048a91804aa430340848.jpg" alt="Arsene" width="300"/>


</p>
<p align="center">
<a href="#"><img title="Arsene" src="https://img.shields.io/badge/Arsene-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>
<p align="center">
<a href="https://github.com/DikaArdnt"><img title="Author" src="https://img.shields.io/badge/Author-Dika-red.svg?style=for-the-badge&logo=github"></a>
<a href="https://github.com/zeeone-ofc/Alphabot-Md"><img title="Recode" src="https://img.shields.io/badge/Recode-Zian-red.svg?style=for-the-badge&logo=github"></a>
</p>
<p align="center">
<a href="https://github.com/Xtrailz/followers"><img title="Followers" src="https://img.shields.io/github/followers/Xtrailz?color=red&style=flat-square"></a>
<a href="https://github.com/Xtrailz/Xtrailz-Bot-MD-V3/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/Xtrailz/Xtrailz-Bot-MD-V3?color=blue&style=flat-square"></a>
<a href="https://github.com/Xtrailz/Xtrailz-Bot-MD-V3/network/members"><img title="Forks" src="https://img.shields.io/github/forks/Xtrailz/Xtrailz-Bot-MD-V3?color=red&style=flat-square"></a>
<a href="https://github.com/Xtrailz/Xtrailz-Bot-MD-V3/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/Xtrailz/Xtrailz-Bot-MD-V3?label=Watchers&color=blue&style=flat-square"></a>
<a href="https://github.com/Xtrailz/Xtrailz-Bot-MD-V3"><img title="Open Source" src="https://badges.frapsoft.com/os/v2/open-source.svg?v=103"></a>
<a href="https://github.com/Xtrailz/Xtrailz-Bot-MD-V3/"><img title="Size" src="https://img.shields.io/github/repo-size/Xtrailz/Xtrailz-Bot-MD-V3?style=flat-square&color=green"></a>
<a href="https://github.com/Xtrailz/Xtrailz-Bot-MD-V3/graphs/commit-activity"><img height="20" src="https://img.shields.io/badge/Maintained%3F-yes-green.svg"></a>&nbsp;&nbsp;
</p>

<p align="center">
  <a href="https://bit.ly/ourgroupinvites"> Official Group Bot</a> •
  <a href="https://linktr.ee/hillalzian">Contact Me</a>
</p>
</div>


---

## Information
> Arsene adalah bot yang awalnya memakai base dari [Chikabot](https://github.com/rashidsiregar28/chikabot/blob/main/README.md), sekarang pindah base [Hisoka-Morou](https://github.com/DikaArdnt/Hisoka-Morou). Arsene is a bot whatsapp using a Baileys library.
> Jika kamu menemukan semacam bug, harap untuk dimaklumi sementara

## Bugs and Tester
* Jika kamu menemukan bug jangan lupa buka Issues
* Info Lebih Lanjut, Contact saya di [sini](https://linktr.ee/hillalzian)

# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://github.com/BtbN/FFmpeg-Builds/releases/download/autobuild-2020-12-08-13-03/ffmpeg-n4.3.1-26-gca55240b8c-win64-gpl-4.3.zip) (for sticker command)

# Instalasi
# Tekan Tombol Dibawah
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Xtrailz/Arsene-Bot)
```bash
heroku/nodejs
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```
## For Termux
```ts
termux-setup-storage
apt update && apt upgrade
pkg install nodejs git ffmpeg libwebp imagemagick
git clone https://github.com/Xtrailz/Arsene-Bot.git
cd (Nama folder file bot)
pkg install yarn
yarn install
npm i -g typescript
tsc -p ./node_modules/@adiwajshing/baileys-md/
rm -rf session.json
rm -rf store.json
npm start
```

## Edit file
`./settings.js`
```ts
// setting 
global.autoread = false // auto read pesan / message
global.autorecording = true //status auto merekam ( auto record )
global.autoketik = false //status auto mengetik (auto typing)
global.available = true //status online (online)

// Other
global.botname = "Arsene" //namabot kalian
global.ownername= "Zian" //nama kalian
global.myweb ="https://linktr.ee/hillalzian" //bebas asal jan hapus
global.youtube = "https://youtube.com/channel/UCZjPStjZEJV_2H4moucLP_w" //bebas asal jan hapus
global.github = "https://Xtrailz.github.io/" //bebas
global.email = "hillalzian@gmail.com" //bebas
global.region = "Indonesia" //bebas
global.ownernomer = "6289678423699" // nomor wa kalian
global.ownernomerr = "+6289678423699" //nmr wa kalian
global.thumbnail = "./image/lol.jpg" // ini lol.jpg adalah nama foto di folder image. untuk foto bot
global.donasi = "./image/donasi.jpg" // foto donasi di folder image
global.background_welcome="https://telegra.ph/file/90a931648de597820bc08.jpg" // maks size 30kb, agar welcome image nya tdk delay
global.owner = ["6289678423699","6289678423699","6289678423699"] //ganti agar fitur owner bisa di gunakan
global.packname = '© XtrailzBot' //sticker wm ubah
global.author = 'Di Buat Oleh Zian' //sticker wm ganti nama kalian
global.sessionName = 'session'
```

## Installing the FFmpeg for Windows
* Unduh salah satu versi FFmpeg yang tersedia dengan mengklik [di sini](https://www.gyan.dev/ffmpeg/builds/).
* Extract file ke `C:\` path.
* Ganti nama folder yang telah di-extract menjadi `ffmpeg`.
* Run Command Prompt as Administrator.
* Jalankan perintah berikut::
```cmd
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
Jika berhasil, akan memberikanmu pesan seperti: `SUCCESS: specified value was saved`.
* Sekarang setelah Anda menginstal FFmpeg, verifikasi bahwa itu berhasil dengan menjalankan perintah ini untuk melihat versi:
```cmd
> ffmpeg -version
```

# Thanks to
<a href="https://github.com/DikaArdnt"><img src="https://github.com/DikaArdnt.png?size=100" width="100" height="100"></a> | [![NURUTOMO](https://github.com/Xtrailz.png?size=100)](https://github.com/Xtrailz) 
---|---
[Dika](https://github.com/DikaArdnt)  | [Zian](https://github.com/Xtrailz)
Owner Hisoka-Morou | Owner Arsene Bot |


