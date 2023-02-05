# Assignments-of-DOM

## 6 Assignments

```


// TASK-1 - To add image logo of ineuron

let header=document.querySelector('header img');
header.src='ineuron-logo.png';

// TASK-2 CHANGING PRICE 

let text=document.querySelector('.app_price span');
text.textContent='$10'

// Adding list item 

let list=document.querySelector('.footer_social');

let element=document.createElement('div');
element.className='footer_social_ico';

let icon=document.createElement('i');
icon.classList='fa-brands fa-linkedin '

element.append(icon);
list.append(element)
```
