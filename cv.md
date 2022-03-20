# Aksultan Zhumadil
## Contacts
- email: [aksultan.zhumadil@gmail.com](mailto:aksultan.zhumadil@gmail.com)
 ### Interactive
[![img](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://www.github.com/aksultan)
[![img](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discordapp.com/users/Decruse#2981)
[![img](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Penguinshaveknees)
## About
Currently, employed  24 years old front-end developer. I like reading/watching sci-fi, adventure related books/movies. Learning to play on the electric guitar :guitar: . Discovering/learning/experiencing something new is my passion in life.
## Skills
![img](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) 
![img](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![img](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![img](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![img](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![img](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![img](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=Webpack&logoColor=white)
## Code example
![img](https://www.codewars.com/users/Aksultan/badges/micro)

**Duplicate Encoder 6 kyu**

The goal of this exercise is to convert a string to a new string where each character in the new string is "(" if that character appears only once in the original string, or ")" if that character appears more than once in the original string. Ignore capitalization when determining if a character is a duplicate.
```
"din"      =>  "((("
"recede"   =>  "()()()"
"Success"  =>  ")())())"
"(( @"     =>  "))((" 
```
```js
function duplicateEncode(word){
    word = word.toLowerCase()
    let repeats = [...word].reduce((acc, letter) => { acc[letter] = acc[letter] ? acc[letter] + 1 : 1; return acc }, {})
    return [...word].map(char => repeats[char]>1?')':'(').join("")
}
```
## Experience
- 2019 - 2020 **Elefanto** (Web Developer php/css/html/js/angular-js)
- 2021.01 - 2021.06 **Rocket Firm** (Front-end developer css/html/js/react)
- 2021.08 - ~ **Rebel** (Front-end developer scss/html/js/vue)
