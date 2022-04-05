[__rsschool - cv__](https://github.com/Duke373/rsschool-cv/tree/gh-pages)

---
### Aleksandr Bondarenko

---

## Contacts

---

* Location: Minsk, Belarus
* Phone: +375 29 328 78 05 , +375293981887
* Email: duke373@mail.ru
* [GitHub](https://github.com/Duke373)

## About myself:
I want to learn Front-End Development in RSSchool!

## Code example:
```
function toReadable(num){
    let number1 = (x) => {
        switch (x) {
            case `0`:
                return ``;
            case `1`:
                return `one`;
            case `2`:
                return `two`;
            case `3`:
                return `three`;
            case `4`:
                return `four`;
            case `5`:
                return `five`;
            case `6`:
                return `six`;
            case `7`:
                return `seven`;
            case `8`:
                return `eight`;
            case `9`:
                return `nine`;
            case `10`:
                return `ten`;
            case `11`:
                return `eleven`;
            case `12`:
                return `twelve`;
            case `13`:
                return `thirteen`;
            case `14`:
                return `fourteen`;
            case `15`:
                return `fifteen`;
            case `16`:
                return `sixteen`;
            case `17`:
                return `seventeen`;
            case `18`:
                return `eighteen`;
            case `19`:
                return `nineteen`;
            case `20`:
                return `twenty`;
            case `30`:
                return `thirtye`;
            case `40`:
                return `forty`;
            case `50`:
                return `fifty`;
            case `60`:
                return `sixty`;
            case `70`:
                return `seventy`;
            case `80`:
                return `eighty`;
            case `90`:
                return `ninety`;
            
            
        }
    }
    return (`${num}`.length == 3 && `${num}`[1] == `1`)?(number1(`${num}`[0]) + ` hundred ` + ` ` + number1(`${num}`.slice(1))):
           (`${num}`.length == 3 && `${num}`[1] !== `1`)?(number1(`${num}`[0]) + ` hundred ` + ` ` +  number1(`${num}`[1] + `0`) + ` ` +  number1(`${num}`[2])):
           (`${num}`.length == 2 && `${num}`[1] == `1`)?(number1(`${num}`)):
           (`${num}`.length == 2 && `${num}`[1] !== `1`)?(number1(`${num}`[0] + `0`) + ` ` +  number1(`${num}`[1])):
           (`${num}`.length == 1 && `${num}` !== `0`)?number1(`${num}`):
           (`${num}`.length == 1 && num === 0)?`zero`:`Введи трехзначное число`;
}
```
## Work experience:

I have no experience as a programmer.

## Education and courses:

* CS50 video course
* JS, CSS, HTML 
* JavaScript https://learn.javascript.ru/

# Language:

English - Pre-Intermediate

