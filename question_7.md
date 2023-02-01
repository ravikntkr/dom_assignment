# Question 7
## Main Preview
![orignal](https://user-images.githubusercontent.com/97457589/215985068-64568524-f37c-4ce7-bbc6-648322e51b74.png)

# Task
### Remove the languages that have 2.0 in their name and Use JavaScript to write something in the input box and submit the form. This should refresh the page and the languages in the left card should come back.
![ass7 1-after](https://user-images.githubusercontent.com/97457589/215985637-a61bab86-4fa8-47ac-a11e-0ce27d17c32e.png) 

```
// Removeing the languages that have 2.0 in their name

let removeLang = document.querySelectorAll(".main__languages a");

for (let i = 0; i < removeLang.length; i++) {
  if (removeLang[i].innerText.includes("2.0")) {
    removeLang[i].style.display = "none";
  }
}

// Enable button and Input field

let inputField = document.querySelector(".main__form-input");
inputField.disabled = false;

let submitBtn = document.querySelector(".main__form-btn");
submitBtn.disabled = false;

// Adding a eventlistener in submit button

submitBtn.addEventListener("click", click);
function click() {
  for (let i = 0; i < removeLang.length; i++) {
    removeLang[i].style.display = "inline-block";
  }
}

```
