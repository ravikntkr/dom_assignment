# dom_assignment

## Question 1
### Task 1

![task1Output](https://user-images.githubusercontent.com/97457589/215341122-8a0e09d8-98eb-4a02-8ed0-129a22e6e61b.png)

```
// Add Hire me inside nav menu

let list = document.createElement("li");
let list_items = document.createTextNode("Hire Me");
list.appendChild(list_items);

let element = document.querySelector("ul");
element.appendChild(list);

// Change Contact to Projects

let lastitems = document.querySelector("header nav ul li:nth-child(3)");
lastitems.innerText = "Projects";

// Removeing Footer Social Icons

let removesocial = document.querySelector("footer ul");
removesocial.remove();
```
![task2Output](https://user-images.githubusercontent.com/97457589/215342512-c72050e0-1ff9-477a-944c-a30e011f351e.png)

```
// Changeing Search field Placeholder

let inputText = document.querySelector("header .search-field input");
inputText.placeholder = "Search My Project";
```
