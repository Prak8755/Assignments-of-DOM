# Assignments-of-DOM

## 1 Assignment 

```


      // Task 1- (A)
      <!-- creating hire me in nav section  -->

      let nav=document.querySelector('nav');
      let ul=nav.querySelector('ul');

      let li=document.createElement('li');
      let a=document.createElement('a');
      
     
      a.innerText='Hire Me';
      a.href = "./hireMe";
      li.appendChild(a);
      ul.appendChild(li)


      // (B))Changing contact to projects

let ChangeLi=document.querySelector('#list');
ChangeLi.textContent='Projects';

//(C)- Deleting ul from footer section 

let footer=document.querySelector('footer');
let footerUl=footer.querySelector('ul');
footerUl.style.display='none';


//Task -2 (A)- Removing Hire me and adding placeholder for search bar

li.style.display='none'

//(B)- Adding placeholder in searchbar

let searchbar=document.querySelector('.search-field');
let searchTarget=searchbar.querySelector('input');
searchTarget.placeholder='Search My Project'

//Task 3- adding ul and changing the span in paragraph section 

let para=document.querySelector('.hero-left-section');
let spanText=para.querySelector('p');
spanText.children[2].innerHTML='an Employee'
spanText.children[4].innerHTML='iNeuron intelligence pvt Ltd'

//(b)- adding ul

footerUl.style.display='';

//Task 4- Adding an image

let image=document.querySelector('.hero-right-section');
let imageUpload=image.querySelector('img');
imageUpload.src='https://images.unsplash.com/photo-1518806118471-f28b20a1d79d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxjb2xsZWN0aW9uLXRodW1ibmFpbHx8MzgwNTI3N3x8ZW58MHx8fHw%3D&auto=format&fit=crop&w=420&q=60';

//(b)

let para1=document.querySelector('.hero-left-section');
let spanText1=document.querySelector('p');
spanText1.children[2].innerHTML='a Freelancer';
spanText1.children[4].innerHTML='National and International client  '

//c-

let search=document.querySelector('.search-field');
let searchChange=document.querySelector('input');
searchChange.placeholder='Search'

//Task 5- adding button element

let button2=document.querySelector('.hero-right-section-btns');
let ButtonCreate=document.createElement('button');
ButtonCreate.textContent='Support Me';


button2.appendChild(ButtonCreate)

```
