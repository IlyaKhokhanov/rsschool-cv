# [rsschool-cv](https://IlyaKhokhanov.github.io/rsschool-cv)

# Ilya Khokhanov

## Contacts

- Phone: +7 920 130 40 10
- E-mail: hohanov.ilya@gmail.com
- Telegram: @hohanhoh

## Information about me

I am a project manager in IT company, but my work more related with physical equipment, a few years ago I decided to study Frontend development. The training was slow, but now with small steps reached to study React. One month ago I started writing an application with a dictionary and tests, now two pages are ready in the application and is in the process of development.
Now I need to finish study and start to work in development, I have more time and motivations to do it.

## My skills

- HTML, CSS, JS
- Git, GitHub
- SCSS, React

## Code example

**Find The Parity Outlier:** You are given an array (which will have a length of at least 3, but could be very large) containing integers. The array is either entirely comprised of odd integers or entirely comprised of even integers except for a single integer N. Write a method that takes the array as an argument and returns this "outlier" N.

```
function findOutlier(integers){
  let odd = []
  let even = []
  integers.forEach(num => {
    num % 2 === 0 ? odd.push(num) : even.push(num)
  })
  return odd.length > even.length ? even[0] : odd[0]
}
```

## Work experience

- [TODO with Drag & Drop](https://ilyakhokhanov.github.io/DNDtodo/)
- In process write application on React with dictionary and tests on Russian language. [Repository with App](https://github.com/IlyaKhokhanov/dictionary_and_test)

## Education

- Read JavaScript textbook on [learn.javascript.ru](https://learn.javascript.ru/)
- In the process of reading React manual on [reactjs.org](https://reactjs.org/)

## Languages

- English - Basic
- Russian - Native
