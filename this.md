## This istifadesi

This açar sözü istifade yerlerine görə fərqlənir

## Metod daxilində istifadəsi

Metod daxilində this metodun ozünə bərabərdir

```js
const obj = {
  name: "John",
  sayHello() {
    console.log(this);
  },
};
obj.sayHello(); //obj
```

## Globalda this

Globalda this windowsu obyektini gətirir

```js
consoleşlog(this); //window
```

## Function daxilində this

Function daxilində global obyekti gətirir

```js
function sayHello() {
  console.log(this); //window
}
```

## Constructor function daxilində

Burada həmişə boş obyekti gətirir

```js
function sayHello() {
  console.log(this);
}
const test = new sayHello(); // {}
```
