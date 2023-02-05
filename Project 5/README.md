# DomAssignments

## 5 Asignments

```

let button=document.createElement('a');
button.href='index.html';
button.className='btn';
button.textContent='Pro Subscription';

let navElement=document.querySelector('.nav-center div:nth-child(3)');
navElement.appendChild(button)


// TASK 2- ADDING ONE MORE ELEMENT IN RECIPE SECTION 

let recipe=document.querySelector('.tags-container div');

let recipeElement=document.createElement('a');
recipeElement.href='#';
recipeElement.textContent='Chinese(7)';

recipe.appendChild(recipeElement);

// adding one more card in recipe gallary


let maindiv=document.querySelector('.recipe-gallery');

let childDiv=document.createElement('div');
childDiv.className="card";

let anchor=document.createElement('a');
anchor.className='recipe-text';
anchor.href='#';

let image=document.createElement('img');
image.src='https://www.indianveggiedelight.com/wp-content/uploads/2022/07/poha-recipe-featured.jpg';
image.className='recipe-img';

let heading=document.createElement('h5');
heading.className='recipe-name';
heading.textContent='Poha';

let para=document.createElement('p');
para.className='recipe-disp';
para.textContent="Prep : 15min | Cook : 5min";

anchor.appendChild(image);
anchor.appendChild(heading);
anchor.appendChild(para);

childDiv.appendChild(anchor);

maindiv.appendChild(childDiv);

```
