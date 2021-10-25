# Kenneth Chen's Notes

## Summary 

This repository contains all of the notes taken by [Kenneth Chen](https://github.com/chenken12) for the Lighthouse Labs Web Development Bootcamp.

* [Week 1](/Week_1)
  * [Day 1](/Week_1/Day_1)
    1. What_Should_I_Do_for_Lunch_Tips.md

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  //console.log("I don't know what to do!");
  if (hungry === true) {
    if (availableTime < 20) {
      console.log("Pick something up and eat in back in the Lab");
    } else if (availableTime <= 30) {
      console.log("You deserve a break and could try a place in Gastown");
    } else if (availableTime > 30) {
      console.log("This is a bootcamp after all and you should probably reconsider");
    }
  } else {
    console.log("Get back to work");
  }
};
```
