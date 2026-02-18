# Blackjack Game
Project aimed for Advanced Students learning javascript.

First hands-on-built game of my life. 🎉, 👏, 🎊, 🎈

Congratulations to me.

## Logical Ques
1. Why use 
```
Math.floor( Math.random()*13 ) + 1
```
where I can use 
```
Math.ceil( Math.random()*13 )
```
? - > No, you can’t just use Math.ceiling() because the range from Math.random is [0,1). That means it includes 0 but not 1. On the extremely rare chance you roll a 0