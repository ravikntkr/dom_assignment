# dom_assignment

## Main Preview

![orignal](https://user-images.githubusercontent.com/97457589/215492345-0eb81740-876f-4512-83cd-e868535c28de.png)

## Question 1
### Task 1
### Adding [hire me] button inside nav menu, change nav [Contact] buuton to [Projects] and Removeing footer social icons.
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

document.querySelector("footer ul").style.display = "none";

```
### Task 2
### Changeing Header search field Placeholder text and hide [Hire Me]  Button from nav menu.
![task2Output](https://user-images.githubusercontent.com/97457589/215342512-c72050e0-1ff9-477a-944c-a30e011f351e.png)

```
// Changeing Search field Placeholder

let inputText = document.querySelector("header .search-field input");
inputText.placeholder = "Search My Project";

// Hide Hire me button from nav menu

let removeItems = document.querySelector("ul");
removeItems.removeChild(removeItems.children[3]);

```
### Task 3
### Changeing hero paragraph span text and display footer social icons.
![task3Output](https://user-images.githubusercontent.com/97457589/215502198-8b2bf6b0-8fca-443b-a61f-b7d049586798.png)

```
// Changeing Hero paragraph span text 

let heroAboutSpan1 = document.querySelector(
  ".hero-section .hero-left-section p span:nth-child(3)"
);
heroAboutSpan1.innerText = "an Employee";

let heroAboutSpan2 = document.querySelector(
  ".hero-section .hero-left-section p span:nth-child(5)"
);
heroAboutSpan2.innerText = "iNeuron Intelligence Pvt Ltd.";

// Display footer social icon

document.querySelector("footer ul").style.visibility = "visible";

```

### Task 4
### Changeing hero avtar image and restore placeholder text.
![task4Output](https://user-images.githubusercontent.com/97457589/215511263-5b0bbcb6-f9a3-4159-beb8-0c1a6194b1c1.png)

```
// Change avtar image from hero section

let authorImage = document.querySelector(
  ".hero-section .hero-right-section img"
);

authorImage.src = "./HITESH CHOUDHARY.jpg";

// Restore placeholder text

let inputTextRestore = document.querySelector("header .search-field input");
inputTextRestore.placeholder = "Search";

```

### Task 5
### Restore paragraph span text, Hero avtar image and adding a [Support Me] Button.
![task5Output](https://user-images.githubusercontent.com/97457589/215519183-a354b270-38a6-4a39-973b-c5f753f2ec2a.png)

```

// Restore paragraph span text as original

let heroAboutSpan1Restore = document.querySelector(
  ".hero-section .hero-left-section p span:nth-child(3)"
);
heroAboutSpan1Restore.innerText = "a Freelancer";

let heroAboutSpan2Restore = document.querySelector(
  ".hero-section .hero-left-section p span:nth-child(5)"
);
heroAboutSpan2Restore.innerText = "National and International Client.";

// Restore avtar image

let authorImageRestore = document.querySelector(
  ".hero-section .hero-right-section img"
);

authorImageRestore.src = "./avtar.png";

// Add a [Support me] button

let supportMeBtn = document.createElement("button");
let supportMeBtnTxt = document.createTextNode("Support Me");
supportMeBtn.appendChild(supportMeBtnTxt);

let supportMe = document.querySelector(
  ".hero-section .hero-right-section .hero-right-section-btns"
);
supportMe.appendChild(supportMeBtn);

```

