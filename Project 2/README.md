# Assignments-of-DOM

## 2 Assignment

```
//Task 1 - applying background color to div
Array.from(accordian);
accordian.forEach((e)=>{
  e.style.backgroundColor='#DADAF8'
})

//  Task 2- adding Skills div and creating content inside this 

let div1=document.querySelector('.accordian-wrapper');
let div=document.querySelector('.accordian');
let skills =document.createElement('h3');
let para=document.createElement('p');

para.textContent='Hello';
skills.appendChild(para);
div.appendChild(skills)
skills.textContent='skills';
div.appendChild(skills)
div1.appendChild(div);
```

