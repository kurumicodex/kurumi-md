# Kurumi-MD
# AUthor THIS SCRIPT READ.ME = Aiinne

# NOTE
*pihak team developer dan team aine tidak beroperasi kembali karena script ini di perjual belikan*


This script is free, if caught sold, this script will be deleted immediately.
Don't forget to follow my github

Script ini gratis, Jika ketahuan di jual, Script ini akan langsung di hapus.
Jangan lupa untuk mengikuti github ku
* My WhatsApp [`Click Here`](https://wa.me/6283167443391?text=Assalamualaikum)
* My Instagram [`Click Here`](https://www.instagram.com/kurumi_cwe)

## Viewer 👁️
<p align="center"><img src="https://profile-counter.glitch.me/{kurumicodexx}/count.svg" alt="neoxr :: Visitor's Count" /></p>

## Heroku Buildpack
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/kurumicodexx/kurumi-md)

| BuildPack | LINK |
|--------|--------|
| **FFMPEG** |[here](https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest) |
| **IMAGEMAGICK** | [here](https://github.com/DuckyTeam/heroku-buildpack-imagemagick) |

---------

## HOW TO CONNECT TO MONGODB WHEN RUN IN HEROKU

* Create account and database in mongodb atlas [`watch here`](https://youtu.be/rPqRyYJmx2g)
* when you already have a database, you just need to take mongourl
* Put mongourl in Procfile `web: node . --db 'mongourl'`
* Example `web: node . -- db 'Your Mongo URI'`

---------

## FOR TERMUX/UBUNTU/SSH USER

```bash
apt update && apt upgrade
apt install git -y
apt install nodejs -y
apt install ffmpeg -y
apt install imagemagick -y
git clone https://github.com/kurumicodexx/kurumi-md
cd kurumi-md
pkg install yarn
yarn

```
---------

## INSTALL ON TERMUX WITH UBUNTU

[ INSTALLING UBUNTU ]

```bash
apt update && apt full-upgrade
apt install wget curl git proot-distro
proot-distro install ubuntu
echo "proot-distro login ubuntu" > $PREFIX/bin/ubuntu
ubuntu
```
---------

[ INSTALLING REQUIRED PACKAGES ]

```bash
ubuntu
apt update && apt full-upgrade
apt install wget curl git ffmpeg imagemagick build-essential libcairo2-dev libpango1.0-dev libjpeg-dev libgif-dev librsvg2-dev dbus-x11 ffmpeg2theora ffmpegfs ffmpegthumbnailer ffmpegthumbnailer-dbg ffmpegthumbs libavcodec-dev libavcodec-extra libavcodec-extra58 libavdevice-dev libavdevice58 libavfilter-dev libavfilter-extra libavfilter-extra7 libavformat-dev libavformat58 libavifile-0.7-bin libavifile-0.7-common libavifile-0.7c2 libavresample-dev libavresample4 libavutil-dev libavutil56 libpostproc-dev libpostproc55 graphicsmagick graphicsmagick-dbg graphicsmagick-imagemagick-compat graphicsmagick-libmagick-dev-compat groff imagemagick-6.q16hdri imagemagick-common libchart-gnuplot-perl libgraphics-magick-perl libgraphicsmagick++-q16-12 libgraphicsmagick++1-dev
```

---------

[ INSTALLING NODEJS & AINE-MD ]

```bash
ubuntu
curl -fsSL https://deb.nodesource.com/setup_current.x | sudo -E bash -
apt install -y nodejs gcc g++ make
git clone https://github.com/kurumicodexx/kurumi-md
cd kurumi-md
npm install
npm update
```

---------

## FOR WINDOWS/VPS/RDP USER

* Download And Install Git [`Click Here`](https://git-scm.com/downloads)
* Download And Install NodeJS [`Click Here`](https://nodejs.org/en/download)
* Download And Install FFmpeg [`Click Here`](https://ffmpeg.org/download.html) (**Don't Forget Add FFmpeg to PATH enviroment variables**)
* Download And Install ImageMagick [`Click Here`](https://imagemagick.org/script/download.php)

```bash
git clone https://github.com/kurumicodexx/kurumi-md
cd kurumi-md
npm install
npm update
```

---------

## FOR OKTETO

* Okteto [`Click Here`](https://okteto.com)

```bash
Login with your github
Click Launch Dev Environment
Choose your repo
```


---------

## PANEL/RDP/VPS

* Amiruldev [`Click Here`](https://www.amiruldev.my.id)


---------

## Run

```bash
node .
```

---------

## Arguments `node . [--options] [<session name>]`

### `--session <file name>`

Use another session with another name, default is ```session.data.json```

### `--prefix <prefixes>`

* `prefixes` are seperated by each character
Set prefix

### `--server`

Used for [heroku](https://heroku.com/) or scan through website

### `--db <json-server-url>`

#### GET

```http
GET /
Accept: application/json
```

#### POST

```http
POST /
Content-Type: application/json

{
 data: {}
}
```

### `--big-qr`

If small qr unicode doesn't support

### `--img`

Enable image inspector through terminal

### `--test`

**Development** Testing Mode

### `--trace`

```js
conn.logger.level = 'trace'
```

### `--debug`

```js
conn.logger.level = 'debug'
```

## Settings

Now set using switch [enable.js](https://github.com/kurumicodexx/kurumi-md/blob/master/plugins/enable.js), among others are

```js
autoread: false, // If true all chats are automatically read
nyimak: false, // No bot, just print received messages and add users to database
restrict: false, // Enables restricted plugins (which can lead your number to be banned if used too often)
self: false, // Activate self mode (Ignores other)
pconly: false, // If that chat not from private bot, bot will ignore
gconly: false, // If that chat not from group, bot will ignore
```

---------

#### Thank's To

Allah SWT,

Orang Tua,

Semua yang selalu mendukung

#### Special Thank's To Script Readme This
[![Aiine](https://github.com/Aiinne.png?size=100)](https://github.com/Aiinne)


## Contributor Script

[![Kurumi](https://github.com/kurumicodexx.png?size=100)](https://github.com/kurumicodexx)

Best Regards. Kurumi-MD
