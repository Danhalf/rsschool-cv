<h1><p align="center"> 
   Oleksii Suvorov
</p></h1>
<p align="center">
  <img src="avatar.jpg" />
</p>

---

## **About**

---

Hey! I'm Oleksii, 32 years old.  
Zhytomyr, UA.  
I began to be fascinated by web programming a years ago, e.g. developing apps and building websites.  
My goal is to become a successful developer and build my career in IT.  
This sphere develops every day, which gives me the opportunity to improve myself every day through hard work and learning new things.

---

## **My skills**

---

| Languages  | Frameworks |      Others |
| ---------- | :--------: | ----------: |
| HTML5      |    PUG     |    WebStorm |
|            |    TWIG    |      VSCode |
| CSS3       |    SCSS    |       Figma |
|            |   STYLYS   | Adobe PS/XD |
| Javascript |   React    |     Postman |
|            |    Vue     |      Docker |
|            |    Next    |      Trello |
| TypeScript |            |         Git |
| PHP        |            |       Linux |
| PostgreSQL |            | Open Server |
| MongoDB    |            |         API |
| Firebase   |            |         CMS |

---

## **My contacts**

---

- [E-mail](mailto:danhalf@ukr.net)
- [Telegram](https://t.me/Suvorov_Aleks)
- [GitHub](https://github.com/Danhalf)
- Discord – Oleksii Suvorov (@Danhalf)

---

## **Code example**

**Task**:  
_Write an algorithm that takes an array and moves all of the zeros to the end, preserving the order of the other elements._

**Solution**:

```javascript
const moveZeros = (arr) => [...arr.filter((e) => e !== 0), ...arr.filter((e) => e === 0)];
```

---

**Task**:  
_The rgb function is incomplete. Complete it so that passing in RGB decimal values will result in a hexadecimal representation being returned. Valid decimal values for RGB are 0 - 255. Any values that fall out of that range must be rounded to the closest valid value._

**Solution**:

```javascript
const rgb = (r, g, b) => {
  Number.prototype.clamp = function (min, max) {
    return Math.min(Math.max(this, min), max);
  };
  return [r, g, b].map((e) => e.clamp(0, 255)).map((x) => x.toString(16).padStart(2, '0')).join``.toUpperCase();
};
```

---

---

## **My education**

---

_2007 - 2009_  
Faculty of Computer Science, Physics and Mathematics

## **My experience**

---

_April 2012 - current_  
Sys. Administration, Armed Forces of Ukraine

---

## **My projects**

---

[CV](https://danhalf.github.io/CV/)

---

## **Languages**

---

**Ukranian** - _Native_  
**English** - _Pre-Intermediate_
