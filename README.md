<a name="readme-top"></a>
JOIN WITH MY COMUNNITY 

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?logo=whatsapp&logoColor=fff&style=flat)](https://chat.whatsapp.com/C1LbTu4n8lX30WOsdH32ff)

<br />
<div align="center">
  <a href="https://github.com/DitzOfc-Expertise/Komari_Botz">
    <img src="https://telegra.ph/file/702d5ba4993c5196930c7.jpg">
  <h3 align="center">Komari Botz</h3>
  <p align="center">
    Created By DitzOfc
 <p/>
</div>
    
### About
This bot was created by DitzOfc, a beginner programmer. This bot was created with the aim of making everyday activities easier, I am very grateful And can't forget the support you have given me all this time
 
## Types and Programming Languages 

This script is of the Plugins type, and the programming language used is:

* [![Javascript][Javascript.js]][Javascript-url]

<summary>Instalation</summary>

`you can choose Indonesian or English`
<details close="close">
<summary><i><b>Indonesian</b></i></summary>

***
### 1. Install Aplikasi [Termux](https://f-droid.org/repo/com.termux_118.apk)
> Setelah Install Aplikasi Termux, Silahkan Salin Teks Dibawah, Setelah Disalin Tempel Di Aplikasi Termux.
```
pkg update -y;pkg upgrade -y;pkg install nodejs -y;pkg install git -y;git clone https://github.com/DitzOfc-Expertise/Komari_Botz.git && cd Komari_Botz;rm -rf session.json;node index
```
### 2. Pairing Code & Scan
> Kamu juga bisa memilih opsi, antara pairing code atau scan
```sh
node index.js --pairing-code
```
> Ini adalah opsi perintah untuk scan
```sh
node index.js
```
***
</details><details close="close"><summary><i><b>English</b></i></summary>

***
### 1. Install The [Termux](https://f-droid.org/repo/com.termux_118.apk) App
> After Installing The Termux Application, Please Copy The Text Below, After Copying Paste In The Termux Application.
```
pkg update -y;pkg upgrade -y;pkg install nodejs -y;pkg install git -y;git clone https://github.com/DitzOfc-Expertise/Komari_Botz.git && cd Komari_Botz;rm -rf session.json;node index
```
### 2. Pairing Code & Scan
> You can choose the option between pairing code or scan
```sh
node index.js --pairing-code
```
> This is a command so that the script can connect to the scan option
```sh
node index.js
```
***
</details></details>

## Features

| Features | Avaible |
| -------- | --------- |
| Jadi Bot         | :white_check_mark: |
| RPG                 | :white_check_mark: |
| Function Send Button                  | :white_check_mark: |
| Downloader                 | :white_check_mark: | 
| AI                | :white_check_mark: |
| Anti Features           | :white_check_mark: |
| Game Features                  | :white_check_mark: |
| Anime Features                 | :white_check_mark: |
| Everyone Tags                 | :white_check_mark: | 
| Atlantic                 | :red_circle: | 

### Tutorial on How to Use the Send Button Function
<details close="close">
<summary><i><b>Send Button Message</b></i></summary>

***
```js
/**
  * ©DitzOfc
  **/
let buttons = [{ text: '', id: '' }]

conn.sendButtonMsg(jid, 'text', 'footer', buttons, quoted)
// Or
conn.sendButtonMsg(jid, 'text', 'footer', [{ text: '', id: '' }], quoted)
```
***
</details></details>
<details close="close"><summary><i><b>Send Button Message With Image</b></i></summary>

***
```js
/**
  * ©DitzOfc
  * The imageUrl part must be a string of url
  **/
let buttons = [{ text: '', id: '' }]
conn.sendButtonImg(jid, 'text', 'footer', buttons, imageUrl, quoted)
// or
conn.sendButtonImg(jid, 'text', 'footer', [{ text: '', id: '' }], imageUrl, quoted)
```
***
</details></details>
<details close="close">
<summary><i><b>Send List Message</b></i></summary>

  ***
```js
/**
  * ©DitzOfc
  **/
let sections = [{
  title: 'title',
  rows: [{
  header: 'header',
  title: 'title',
  description: 'description',
  id: 'id' 
}] 
}]

conn.sendListMsg(jid, 'text', 'footer', 'titleButton', sections, quoted)
```
***
</details></details>
<details close="close">
<summary><i><b>Send List Message With Image</b></i></summary>

***
```js
/**
  * ©DitzOfc
  * The imageUrl part must be a string of url
  **/
let sections = [{
  title: 'title',
  rows: [{
  header: 'header',
  title: 'title',
  description: 'description',
  id: 'id' 
}] 
}]

conn.sendListImg(jid, 'text', 'footer', 'titleButton', sections, imageUrl, quoted)
```
***
</details></details>
<details close="close">
<summary><i><b>Send Button Card</b></i></summary>

***
```js
/**
  * ©DitzOfc
  * The imageUrl part must be a string of url
  * [cards] Must follow the example below
  * type = ['buttons', 'url']
  **/
  let cards = [
    {
      header: 'header',
      body: 'body',
      footer: 'footer',
      imageUrl: 'string',
      buttons: [
        {
          type: 'url',
          text: "text of buttons url",
          url: "https://example.com"
        },
        {
          type: 'buttons',
          text: "text of buttons",
          id: "quick_reply_id_1"
        }
      ]
    }
  ];

  await conn.sendButtonCard(jid, 'text', 'footer', cards, quoted);
```
***
</details></details>

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact Me
If you find a bug/error in the script, you can contact me directly via:

[On WhatsApp](https://wa.me/6285717062467)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Javascript.js]: https://shields.io/badge/JavaScript-F7DF1E?logo=JavaScript&logoColor=000&style=flat-square
[Javascript-url]: https://nodejs.org
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
