# NumerolJS [![NPM Module](https://img.shields.io/badge/NPM-V1.1.3-green)](https://github.com/alexagep/numerology-npm) [![Wikipedia](https://badgen.net/badge/about-numerology/wikipedia/blue?icon=wiki)](https://en.wikipedia.org/wiki/Numerology) [![project-type](https://badgen.net/badge/project-type/funny/orange?icon=github)](https://en.wikipedia.org/wiki/Numerology) 
A library to convert birthdate to numerology number. Can be used to study of numbers, such as the figures in a birth date, and of their supposed influence on human affairs.

## What is nomerology
Wikipedia describes numerology as below:

> Numerology (also known as arithmancy) is the study of an occult, divine or mystical relationship between a number and one or more coinciding events. It is also the study of the numerical value, via an alphanumeric system, of the letters in words and names. When numerology is applied to a person's name, it is a form of onomancy. It is often associated with the paranormal, alongside astrology and similar to divinatory arts.
> Despite the long history of numerological ideas, the word "numerology" is not recorded in English before c. 1907.

> The term numerologist can be used for those who place faith in numerical patterns and draw pseudoscientific inferences from them, even if those people do not practice traditional numerology. For example, in his 1997 book Numerology: Or What Pythagoras Wrought, mathematician Underwood Dudley uses the term to discuss practitioners of the Elliott wave principle of stock market analysis. 


## What Does this package do for you?
`NumerolJs` calculates the numerology number from your `birth-date` (Jalali & Gregorian) and your `name` therefor you can use that number to check your future or something like that.

## Install

For npm users:

```shell
npm i numeroljs
```

For yarn users:

```shell
yarn add numeroljs
```

## Usage

you can use this library for calculation in persian or gregorian dates, it converts itself in a correct way

``` javascript
var numerol = require('numeroljs');

const numerolInstance = new numerol.Numeroljs();

numerolInstance.handle('1989/05/22'); // 9
numerolInstance.handle('1368/04/07', 'jalali'); // 7
```

either you can write in american format
you can also use two date separators ('/' or '-') 


``` javascript
import { Numeroljs } from 'numeroljs';

const numerolInstance = new Numeroljs();

console.log(numerolInstance.handle('1989-22-05')); // 9
console.log(numerolInstance.handle('1368-04-07', 'jalali')); // 7
```


Also, you can use convertName method to calculate chaldean Numerology number of your name 


``` javascript
import { Numeroljs } from 'numeroljs';

const numerolInstance = new Numeroljs();

console.log(numerolInstance.convertName('John Doe')); // 7
```



## 🤝 Contribution

I will be grateful for any help you can provide to make this project better.
Thank you to all the people who already contributed to NumerolJS!


[![Contributors](https://contrib.rocks/image?repo=alexagep/numerology-npm)](https://github.com/alexagep/numerology-npm/graphs/contributors)


## License

numeroljs is released under the [MIT](LICENSE) license.


## Keywords
Numeroljs, Numerology
