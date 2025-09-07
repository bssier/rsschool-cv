## [rsschool-cv](https://bssier.github.io/rsschool-cv/)

***

# Michael Tavyrin

***

### Contacts

* Phone: +375 33 6015968
* Telegram: @michaeltavyrin
* Discord: @potatoesismylife
* GitHub: [bssier](https://github.com/bssier)

---

### About me

I easily get in touch and find a common language with people. I always enjoy learning something new. \
I am hardworking and persevering. I'm not afraid to make mistakes, because it's mistakes that help you grow.\
I dream of becoming a frontend developer.

---

### Skills

* HTML & CSS
* Git
* JavaScript (basics)
* AWS (basics)

---

### Code example

> Kata description: Welcome. In this kata, you are asked to square every digit of a number and concatenate them.\
> For example, if we run 9119 through the function, 811181 will come out, because 92 is 81 and 12 is 1. (81-1-1-81)

```
function squareDigits(num){
  let numStr = num.toString();
  let arr = []
  for(const num of numStr){
    arr.push(parseInt(num)**2)
  }
  return +arr.join('')
 
}

```

