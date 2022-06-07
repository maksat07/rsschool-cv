# Asanbekov Maksat
## Junior Frontend Developer
### Contacts
#### Phone: +41766204850;
#### Email: asanbekov.max.kk@gmail.com
#### Telegram: @Max
#### LinkedIn: [My LinkedIn](https://www.linkedin.com/feed/)

---
## Briefly About Myself:
As future an engineering technician i have to know provide and support to an engineer, and may work in the fields of mechanical,industrial, civil, electrical, aerospace,environmental engineering or IT. Currently with my ability to work well on a team, and strong analytical and problem-solving skills I will be Fullstuk Engineer in IT.

## Skills

___HTML___
1. HTML5
2. Pug(jade)

___CSS___
1. Sass
2. SCSS

___JavaScript___
1. OOP
2. Vue (15%)
3. React(50%)
	Redux(thunk)

   
___Node JS___
1. ExpressJS

___Git___
1. Github
2. Gitlab

___Other___
1. VScode
2. WebStorm

## Languages

-  Kyrgyz (native)
-  Russian (fluent)
-  Français (B1)

## Codwars
#### task 
Peak array index KATA from CODEWARS: Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.
```
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```