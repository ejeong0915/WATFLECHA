# ๐ฝ WATFLECHA
> Front-end 4๋ช์ด 1์ฃผ๊ฐ ์งํํ Vanilla JavaScript ์ํ ์ ๋ณด ์ฌ์ดํธ WAFLECHA์๋๋ค. <br />

![main2](https://user-images.githubusercontent.com/69497936/101235861-73193100-370f-11eb-9358-2a9a36bfc85e.png)

<br>

## ๐ Overview 
- [Demo](#id-section1)
- [Installation and usage](#id-section2)
- [Functional Specification](#id-section3)
- [Project period](#id-section4)
- [Tech Stacks](#id-section5)
- [Team Members](#id-section6)

<br>

<div id='id-section1'/>

## ๐ Demo

https://user-images.githubusercontent.com/69497936/130321956-0e7ac407-352b-4c1a-b1ef-a58c238ef768.mp4

<br />

<div id='id-section2'/>

## ๐พ Installation and usage
```
$ git clone https://github.com/hanseul-lee/WATFLECHA.git
$ cd WATFLECHA
$ npm start
```
- ์ฐธ๊ณ ์ฉ ๊ณ์ 
```
์์ด๋: hihi
๋น๋ฐ๋ฒํธ: 1234 
```

<br />

<div id='id-section3'/>

## ๐ Functional Specification
### 1. ๋ก๊ทธ์ธ ํ์ด์ง
- ์์ด๋, ๋น๋ฐ๋ฒํธ ๊ฐ์ด ๊ณต๋ฐฑ์ด๊ฑฐ๋, ํ์๊ฐ์ ํ ์์ด๋๊ฐ ์์ผ๋ฉด ์๋ฌ ๋ฉ์ธ์ง๋ฅผ ์ถ๋ ฅํด์ค๋ค.
- ์์ด๋ ์ ๋ณด ์ ์ฅ ๋ฒํผ์ ์ฒดํฌํ์ ์, ํ ๋ฒ์ด๋ผ๋ ๋ก๊ทธ์ธํ์๋ค๋ฉด ๋ค์ ๋ก๊ทธ์ธ ํ๋ฉด์์ ์์ด๋๊ฐ ๋จ์์๋๋ก ํ๋ค.
- ์์ด๋, ๋น๋ฐ๋ฒํธ๋ฅผ ์ฌ๋ฐ๋ฅด๊ฒ ์๋ ฅํ ๊ฒฝ์ฐ, ์ํ๋ฆญ์ฐจ ๋ฉ์ธํ์ด์ง๋ก ๋ก๊ทธ์ธ๋์ด ์ด๋ํ๋ค. 
์ด๋ ์ด๋ฆ, ์์ด๋, ์ ํธ์ฅ๋ฅด, ๋ก๊ทธ์ธ ์ ๋ณด ์ ์ฅ ์ฌ๋ถ ๋ฐ ํ์ฌ ๋ก๊ทธ์ธ ์ํ๊ฐ local storage์ ๋ด๊ธด๋ค.

### 2. ํ์๊ฐ์ ํ์ด์ง
- ์ด๋ฆ, ์์ด๋, ๋น๋ฐ๋ฒํธ ์๋ ฅ ์ฐฝ์ ๊ณต๋ฐฑ ๋๋ ์ ํด์ง ์์ด๋, ๋น๋ฐ๋ฒํธ ์์ฑ ๊ท์น์ ๋ง์ง ์์ ๊ฒฝ์ฐ ์๋ฌ ๋ฉ์ธ์ง๋ฅผ ์ถ๋ ฅํด์ค๋ค.
- ์์ด๋์ ๋น๋ฐ๋ฒํธ๋ 4 ~ 15์๋ฆฌ ์๋ฌธ ํน์ ์ซ์, ์ด๋ฆ์ 1์ ์ด์ ์๋ฌธ, ํ๊ธ, ์ซ์๋ฅผ ์๋ ฅํ  ์ ์๊ฒ ํ๋ค.
- ๋น๋ฐ๋ฒํธ์ ์ฌํ์ธ ์๋ ฅ์ฐฝ์ด ๊ฐ์ง ์์ ๊ฒฝ์ฐ, ์๋ฌ ๋ฉ์ธ์ง๋ฅผ ์ถ๋ ฅํด์ค๋ค.
- ์ ํธ ์ฅ๋ฅด๋ฅผ ์ ํํ์ง ์์ ๊ฒฝ์ฐ, ์๋ฌ ๋ฉ์ธ์ง๋ฅผ ์ถ๋ ฅํด์ค๋ค.
- ๋ชจ๋  ์กฐ๊ฑด์ ๋ง์ถ ๊ฒฝ์ฐ, ์๋ ฅํ ์ด๋ฆ, ์์ด๋, ๋น๋ฐ๋ฒํธ, ์ ํธ ์ฅ๋ฅด๋ฅผ DB์ ์ ์กํ๊ณ  ํ์๊ฐ์์ด ์๋ฃ๋๋ค.

### 3. ํ์ ์ ๋ณด ์์  ํ์ด์ง
- ์ด๋ฆ, ๋น๋ฐ๋ฒํธ, ์ฅ๋ฅด๋ฅผ ์์ ํ  ์ ์๋ค. (์์ด๋๋ ์์  ๋ถ๊ฐ)
- ์ฐํ ์์ด์ฝ ํด๋ฆญ ์ ์๋ ฅ์ฐฝ์ ๊ฐ์ ์๋ ฅํ  ์ ์๋ค.
- DB์ ๋ด๊ธด ๊ธฐ์กด ์ ๋ณด์ ๋น๊ตํด ๊ฐ์ด ๋ณ๊ฒฝ๋ ๊ฒฝ์ฐ, ์๋ ฅ์ฐฝ ์์ด ์ด๋ก์์ผ๋ก ๋ฐ๋๋ค.
- ์๋ ฅํ ์์ด๋, ๋น๋ฐ๋ฒํธ, ์ด๋ฆ์ด ์ ๊ทํํ์ ์กฐ๊ฑด๊ณผ ๋ง์ง ์๋๋ค๋ฉด ์๋ฌ ๋ฉ์ธ์ง๋ฅผ ์ถ๋ ฅํด์ค๋ค.
- ๊ธฐ์กด ๋น๋ฐ๋ฒํธ ๋ฐ ๋น๋ฐ๋ฒํธ์ ์ฌํ์ธ ์๋ ฅ์ฐฝ์ด ๊ฐ์ง ์์ ๊ฒฝ์ฐ, ์๋ฌ ๋ฉ์ธ์ง๋ฅผ ์ถ๋ ฅํด์ค๋ค.
- ๋ชจ๋  ์กฐ๊ฑด์ ๋ง๊ฒ ์ ๋ณด๋ฅผ ์์ ํ์์ ๊ฒฝ์ฐ, ์๋ ฅํ ์ด๋ฆ, ์์ด๋, ๋น๋ฐ๋ฒํธ, ์ ํธ ์ฅ๋ฅด๋ฅผ DB์ local storage(๋น๋ฐ๋ฒํธ ์ ์ธ)์ ์ ์กํ๊ณ  ํ์๊ฐ์์ด ์๋ฃ๋๋ค.

### 4. ๋ฉ์ธ ํ์ด์ง
- ๋ฉ์ธํ๋ฉด ๊ฐ์ฅ ์์ชฝ์ ํ๋ฉด์ด ๊ฝ ์ฐจ๋๋ก ์ํ ์๊ณ ํธ์ ๋ฌดํ ์ฌ์๋๋๋ก ๋ณด์ฌ์ค๋ค.
- ์๋จ์ ์ํ๋ ์ฅ๋ฅด ํด๋ฆญ ์, ์ ํ๋ ์ฅ๋ฅด ํ์ด์ง๋ก ๋์ด๊ฐ๋ค.
- ์ํ API์์ TOP20, ์ต์  ์ํ ๋ฐ ์ทจํฅ ์ ๊ฒฉ ์ํ์ ๋ง๋ ์ํ ๋ชฉ๋ก์ ๋ถ๋ฌ์ ์ฌ๋ผ์ด๋ ํ์์ผ๋ก ์ ๊ณตํ๋ค.
- ์ฌ๋ผ์ด๋์ ์ด์ , ๋ค์ ๋ฒํผ ํด๋ฆญ ์, ์ข์ฐ๋ก ์ฌ๋ผ์ด๋๊ฐ ๋์ด๊ฐ๋ค. ๋์ด๊ฐ ์ฌ๋ผ์ด๋๋ ๋ฌดํํ์์ผ๋ก ์ผ์  ์ฌ๋ผ์ด๋๋ฅผ ๋์ด๊ฐ๋ฉด ์ฒ์์ด๋ ๋งจ ๋์ผ๋ก ๋์๊ฐ๋ค.

### 5. ํ์ ํ์ด์ง
- ๋ฉ์ธ, ์ฅ๋ฅด, ๊ฒ์, ์ฐํ๊ธฐ ํ์ด์ง์์ ์ํ๋ ์ํ๋ฅผ ํด๋ฆญํ์ ๋ ํ์์ฐฝ์ด ๋ณด์ธ๋ค.
- ์ํ API๋ฅผ ํตํด ์ ๋ชฉ, ํ์ , ์๊ณ ํธ, ์ค๊ฑฐ๋ฆฌ, ๊ฐ๋ด์ผ, ์ฅ๋ฅด, ์ด ์์ ์๊ฐ, ์ถ์ฐ ๋ฐฐ์ฐ ์ ๋ณด๊ฐ ๋ ๋๋ง ๋๋๋ก ํ๋ค.
- ํํธ ๋ฒํผ์ ๋๋ฅด๋ฉด ํํธ ์ ๋๋ฉ์ด์์ด ๋ํ๋๊ณ  '์ฐ ์๋ฃ!'๋ก ํ์๊ฐ ๋๋ฉฐ, ๋ถ๋งํฌ์ ์ฐํ ์ํ๊ฐ ๋ด๊ธด๋ค.
- ์ฐํ ์ํ์์ ๋ค์ ํํธ ๋ฒํผ์ ๋๋ฅด๋ฉด ๊ธ์๊ฐ '์ฐํ๊ธฐ'๋ก ๋ฐ๋๊ณ  ๋ถ๋งํฌ์์ ์ฐํ ์ํ๋ฅผ ์ ๊ฑฐํ๋ค. 

### 6. ์ฅ๋ฅด ํ์ด์ง
- ๋ฉ์ธ ํ์ด์ง์์ ์ ํํ ์ฅ๋ฅด์ ์ํ๋ค์ด ๋ ๋๋ง ๋๋ค.
- ์ฅ๋ฅด ํ์ด์ง์์ ๋ค๋ฅธ ์ฅ๋ฅด ํด๋ฆญ ์, ์ ํํ ์ฅ๋ฅด์ ์ํ๋ค์ด ๋ ๋๋ง ๋๋ค.
- ํ์ด์ง๋ค์ด์์ ๊ตฌํํด ์ฌ์ฉ์๊ฐ ์ํ๋ ํ์ด์ง๋ก ์ด๋ํ  ์ ์๊ฒ ํ๋ค.

### 7. ๊ฒ์ ํ์ด์ง
- ์ํ๋ ์ํ๋ฅผ ๊ฒ์ํ๋ฉด ๊ฒ์ API์ ์ํด ๊ฒ์๋ ์ ๋ณด๊ฐ ๋ ๋๋ง ๋๋ค.
- ๋ ๋ณด๊ธฐ ๋ฒํผ ํด๋ฆญ ์, ๋ค์ ํ์ด์ง๊ฐ ์๋์ ์ด์ด ๋ ๋๋ง ๋๋ฉฐ ๋ง์ง๋ง ํ์ด์ง๋ผ๋ฉด ๋ ๋ณด๊ธฐ ๋ฒํผ์ด ์ฌ๋ผ์ง๋ค.

### 8. ๋ถ๋งํฌ ํ์ด์ง
- DB์ ์ ์ฅ๋ ๋ถ๋งํฌ ์ํ๋ค์ ๋ณผ ์ ์๋ค.
- ๋ถ๋งํฌ ํ์ด์ง์์ ํ์์ฐฝ์ ํตํด ์ํ๋ ์ํ์ ๋ถ๋งํฌ๋ฅผ ์ ๊ฑฐํ  ์ ์๋ค. 

<br>

<div id='id-section4'/>

## ๐โโ๏ธ Project period
- 1์ฐจ ๊ตฌํ : 21.10.16 - 21.10.20
- 2์ฐจ ๊ตฌํ : 21.10.22 - 21.10.26 

<br>

<div id='id-section5'/>

## ๐  Tech Stacks
**Front-End**
- HTML5
- CSS3
- JavaScript(ES6+)

**ํ์**
- git/github
- Slack

**๊ฐ๋ฐ ํ๋ก์ธ์ค**
- Agile - Scrum

<br>

<div id='id-section6'/>


## ๐จโ๐ป Team Members
- [๊ณ ์์ ](https://github.com/Alex-Eojin) - ๊ธฐํ, 2,3 ํ์ด์ง HTML/CSS/Javascript,<br>
 2์ฐจ ๊ตฌํ(2,3 ํ์ด์ง ๋ฆฌํฉํ ๋ง, 6 ์ฅ๋ฅด ํ์ด์ง ์ถ๊ฐ, 6,7 ํ์ด์ง ํ์ด์ง๋ค์ด์ ์ถ๊ฐ)
- [์ด์ฌํธ](https://github.com/parksaneon) - ๊ธฐํ, 4,5 ํ์ด์ง HTML/CSS/Javascript, ์ ๋ฐ์ ์ธ ์งํ์ฌํญ QA์ญํ 
- [์ดํ์](https://github.com/do-mandoo) - ๊ธฐํ, 1 ํ์ด์ง HTML/CSS/Javascript, github ๊ด๋ฆฌ
- [์ ์ฌํ](https://github.com/hanseul-lee) - ๊ธฐํ, 5,7,8 ํ์ด์ง HTML/CSS/Javascript, <Br>
2์ฐจ ๊ตฌํ(2,3 ํ์ด์ง ๋ฆฌํฉํ ๋ง, 6 ์ฅ๋ฅด ํ์ด์ง ์ถ๊ฐ, 6,7 ํ์ด์ง ํ์ด์ง๋ค์ด์ ์ถ๊ฐ)
