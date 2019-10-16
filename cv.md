# **Krokh Nickolay**


## **Contact Info**

- **Telephone number**: +375336623761 

- **E-mail**: [375336623761@ya.ru](mailto:375336623761@ya.ru)

- **jobs.tut.by** - [jobs.tut.by/resume/c631eadbff05bdba340039ed1f616237566e7a](https://brest.jobs.tut.by/resume/c631eadbff05bdba340039ed1f616237566e7a)

- **github -** [github.com/NickolayKroh/](https://github.com/NickolayKroh/)


## **Summary**

A bit of web development experience (HTML, CSS, JavaScript, browser extensions) and Android apps development. I also have experience in graphic packages, such as Photoshop or Gimp.  
Good analytical skills, quick learner, motivated to professional growth.
Advanced linux and windows user.


## **Technical Skills**

**Programming languages and technologies:**
- JavaScript 
- HTML
- CSS/SCSS
- Node.js
- PHP
- Java
- Apex
- C/C++
- SQL

**Tools:** 
- GIT
- Webpack
- VS Code
- Webstorm
- Android Studio

**Other skills:**
- My profile with completed courses: [codecademy.com](https://www.codecademy.com/profiles/0239390839)
- My profile in [codewars.com](https://www.codewars.com/users/NickolayKroh)


## **Code example**
```javascript
function zeros(expression) {
  //we get 0 at the of the product when we had pair of 2 and 5 as factors
  let twos = 0;
  let fives = 0;
  let factorial = expression.split('*');
  
  for(let i = 0; i < factorial.length; ++i) {
    let factorialSign = 1; // n!
    if(factorial[i].substr(-2, 2) === '!!')
      factorialSign = 2; // n!!
      
      for(let n = factorial[i].slice(0, -factorialSign); n > 1; n -= factorialSign) {
        for(let m = n; m % 5 === 0 && m >= 5; m /= 5)
          fives++;
        for(let m = n; m % 2 === 0 && m >= 2; m /= 2)
          twos++;
      }
  }
  
  return Math.min(fives, twos);
} 
```


# **Professional Experience**

###  "Belarusbank"
   
**Position**: Systems Engineer (08.08.2015 - till now).


## **Projects**

### Browser game *2D-Race-Game*

**Project:** [github.com](https://github.com/NickolayKroh/2D-Race-Game)

**Position:** developer, designer

**Environment:** HTML, js


### Android App *DragAndDraw*

**Project:** [github.com](https://github.com/NickolayKroh/DragAndDraw)

**Position:** developer

**Environment:** Android, Java


### Android App *PhotoGallery*

**Project:** [github.com](https://github.com/NickolayKroh/PhotoGallery)

**Position:** developer,  designer

**Environment:** Android, Java


### Rolling scopes

Also I've made the following few talks:

- [Brackets](https://github.com/NickolayKroh/brackets)
- [Tic-Tac-Toe](https://github.com/NickolayKroh/tic-tac-toe)
- [Morse-Decoder](https://github.com/NickolayKroh/morse-decoder)


## **Education**

-   Higher, BREST STATE UNIVERSITY named after A.S. Pushkin, specialty **Mathematics and computer science**
-   Higher, BREST STATE TECHNICAL UNIVERSITY, specialty **Software for Information Technologies**


## **English**
    
-   I can easily read any documentation, watch videos and briefly talk in English with somebody. But without any practice at my current job my English level:  **B1 (Intermediate)**
- Daily I practice at [lingualeo.com](https://lingualeo.com/) and i've reached 31 level by now.
