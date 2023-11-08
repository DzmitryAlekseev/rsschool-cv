## RSSCHOOL-CV
# Dzmitry Aliakseyeu
### Junior Fronend Developer
***

## Contact information:
#### Phone: +48690410321
#### Email: dmitry.alekseev.s@gmail.com
#### Telegram: @Dzmitry_Alex
***

## About myself
I have good communicative qualities, great teamwork. I like to develop myself. I assume that JS courses help me with this. Mastering new knowledge can help you get a new profession.
***

## Skills
* HTML
* CSS(BEM)
* JS(Basic)
* Figma
* Git
***

## Code Examples

```

function getCard() {
    function getRandom(min, max){
        let random = Math.floor(Math.random() * (max - min) + min);
        return random;
    }
  
    let arr = [];
    let arrB = [];
    let arrI = [];
    let arrN = [];
    let arrG = [];
    let arrO = [];
 
  
    while(arrB.length < 5 && Array.from(new Set(arrB)) != arrB){
        arrB = Array.from(new Set(arrB))
        let resGetRandom = getRandom(1, 15)
        arrB.push(`B${resGetRandom}`)
    }
  
    while(arrI.length < 5 && Array.from(new Set(arrI)) != arrI){
        arrI = Array.from(new Set(arrI))
        let resGetRandom = getRandom(16, 30)
        arrI.push(`I${resGetRandom}`)
    }
  
    while(arrN.length < 4 && Array.from(new Set(arrN)) != arrN){
        arrN = Array.from(new Set(arrN))
        let resGetRandom = getRandom(31, 45)
        arrN.push(`N${resGetRandom}`)
    }
  
    while(arrG.length < 5 && Array.from(new Set(arrG)) != arrG){
        arrG = Array.from(new Set(arrG))
        let resGetRandom = getRandom(46, 60)
        arrG.push(`G${resGetRandom}`)
    }
  
    while(arrO.length < 5 && Array.from(new Set(arrO)) != arrO){
        arrO = Array.from(new Set(arrO))
        let resGetRandom = getRandom(61, 75)
        arrO.push(`O${resGetRandom}`)
    }

    return arr.concat(arrB, arrI, arrN, arrG, arrO)
}

```
***

## Education
* Private Institute of Management and Entrepreneurship (lawyer);
* IT Academy (HTML,CSS,JS);
* RS School (in process...);
***

## Languages
* Russian - Native;
* Belarussian - B2;
* English - B1;
* Polish - A2;
* German - A1;
***

# Hobbies
* Learning new languages;
* Hikking;
* Traveling;
* Reading books;
* Listening to music;