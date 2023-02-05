# Assignments-of-DOM

## 7 Assignment


```
// Task -1 Removing Languages having 2.0


// Accessing main languages anchor tags
let Elements=document.querySelectorAll('.main__languages a');
console.log(Elements);

//now converting nodelist into array
let ArrayElements=Array.from(Elements);
console.log(ArrayElements);

//Removing langauges consisting 2.0;
ArrayElements.forEach((a)=>{
    if (a.textContent.includes('2.0')){
        a.style.display='none';
        console.log(a);
    }
    
})

//  Task 2-  Use JavaScript to write something in the input box
// and submit the form. This should refresh the page and the languages
// in the left card should come back.

// / Generating the reference to input and button in form
const mainFormInput = document.querySelector(".main__form-input");
const mainFormButton = document.querySelector(".main__form-btn");

// Enabling input and button
mainFormInput.removeAttribute("disabled");
mainFormButton.removeAttribute("disabled");

// storing the input value in local storage
mainFormButton.addEventListener("click", (e) => {
    e.preventDefault();
    localStorage.setItem("inputValue", mainFormInput.value);
    location.reload();
});


// storing the language in the left side even after  refresh
window.addEventListener("load", () => {

    const storedValue = localStorage.getItem("inputValue");
    mainFormInput.value = storedValue;
    const mainLanguages = document.querySelector('.main__languages');
    const a = document.createElement("a");
    a.target = 'blank';
    a.href = 'https://www.ineuron.ai';
    a.innerText = storedValue;
    mainLanguages.append(a);
});

```
