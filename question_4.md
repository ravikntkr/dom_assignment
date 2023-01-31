# Question 4
## Main Preview
![orignal](https://user-images.githubusercontent.com/97457589/215706865-f36dc645-3202-41c4-9664-bc9a0017cda2.png)

# Task
### Change card stats background Color
![DOM P1 SS](https://user-images.githubusercontent.com/97457589/215707532-8d4ad400-ccb6-43de-9a03-96f28f85801d.png)

```
// barbarian

let barbarian = document.querySelector(".clash-card__unit-stats--barbarian");
barbarian.style.background = "#ec9b3b";
barbarian.style.color = "#fff";

// changeing stats text color

let statColor = document.querySelectorAll("div .stat,.stat-value");
for (let i = 0; i < statColor.length; i++) {
  statColor[i].style.color = "#fff";
}

// archer
let archer = document.querySelector(".clash-card__unit-stats--archer");
archer.style.background = "#ee5487";

// giant
let giant = document.querySelector(".clash-card__unit-stats--giant");
giant.style.background = "#f6901a";

// goblin
let goblin = document.querySelector(".clash-card__unit-stats--goblin");
goblin.style.background = "#82bb30";

// wizard
let wizard = document.querySelector(".clash-card__unit-stats--wizard");
wizard.style.background = "#4facff";

```
