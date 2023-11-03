
Denis Artamonov
======
![Us5VbKsGKVo](https://github.com/mopiue/rsschool-cv/assets/123871595/5d3a68fc-d838-4e36-840c-c5562f4a6017)

Discord: Denis Artamonov (@mopiue)

[[Telegram](https://t.me/artham0n)]  

[[GitHub](https://github.com/mopiue)]  

[ iamnucassi@gmail.com ]

About me
---------
**Goals and priorites**
My goals and priorities, probably like every other aspiring developer, are to learn and improve my skills in order to eventually get my first offer.
**Strenghts**
I consider some of my main strongest qualities to be:
- Perseverance
- Determination
- Striving for constant learning and self-development
- Ability to adapt to new technologies
- Ability to find mistakes and solve problems

**Work experience**
I have no real work experience, but I have a great desire and eagerness to learn. I devote all my free time to learning, developing soft and hard skills.

Skills
---------
**Programming**: HTML, CSS, JavaScript, React, Redux/RTK, Tailwind, Styled Components
**Other**: Figma, Git

Example code
---------
**An example of solving a task on CodeWars**
[Task link](https://www.codewars.com/kata/57eb8fcdf670e99d9b000272/train)
>Given a string of words, you need to find the highest scoring word.
Each letter of a word scores points according to its position in the alphabet: a = 1, b = 2, c = 3 etc.
For example, the score of abad is 8 (1 + 2 + 1 + 4).
You need to return the highest scoring word as a string.
If two words score the same, return the word that appears earliest in the original string.
All letters will be lowercase and all inputs will be valid.

#### Solutioun
```javascript
function high(x){
  const alphabet = 'abcdefghijklmnopqrstuvwxyz'
  const splittedX = x.toLowerCase().split(' ')
  const pointsArr = []
  
  let wordScore = 0
  
  splittedX.map((el) => {
    for (let char of el) {
      wordScore += alphabet.indexOf(char) + 1
    }
    pointsArr.push(wordScore)
    wordScore = 0
  })
  
  return splittedX[pointsArr.indexOf(Math.max(...pointsArr))]
}
```

My pet-projects
---------
**A few of my recent projects that are on GitHub**: 
- [Tree Like Structure](https://github.com/mopiue/tree-like-structure)
- [Portfolio](https://github.com/mopiue/portfolio) (Unfortunately, for some reason, it's not finished)

Education
---------
I am self-taught. I learn from youtube, some free courses, official documentation and other publicly available information on the internet.

English level
---------
My level is probably between A1 and A2, but every day I am tightening up my knowledge of the language.
