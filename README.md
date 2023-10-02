## Table of contents

- [Overview](#overview)
  - [Brief](#brief)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Our process](#our-process)
  - [Built with](#built-with)
  - [Code select](#code-select)
  - [Continued development](#continued-development)
- [Authors](#authors)

## Overview

### Brief

Users should be able to:

- View profile videos and information of Danielle's Dream Team

### Screenshot

![](./assets/images/readme-images/2023-10-02%2014_13_26-Production%20and%20HTML.png)
![](./assets/images/readme-images/2023-10-02%2014_13_51-Production%20and%20HTML.png)
![](./assets/images/readme-images/2023-10-02%2014_14_21-.png)
![](./assets/images/readme-images/2023-10-02%2014_14_37-Games.png)


### Links

- Live Site URL: [productionandhtml.com](https://productionandhtml.com/)

## Our process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow
- Flexbox
- CSS Grid
- Bootstrap v5.3.2 

### Code Select

```html
  <div class="container my-5 pt-5" style="padding-top: 70px !important;">
    <div class="row p-4 pb-0 pe-lg-0 pt-lg-5 align-items-center rounded-3 shadow-lg" style=" background-color: #ffffff;">
      <div class="col-lg-7 p-3 p-lg-5 pt-lg-3">
        <h3 class="display-5 fw-bold lh-1 pb-3">CDS Presents</h3>
        <h2 class="display-4 fw-bold lh-1 pb-3">Production and HTML</h2>
        <h2 style="padding-left: 50px;">we are&nbsp;<span class="typewriter"></span></h2>
      </div>
      <div class="col-lg-4 offset-lg-1 p-0">
          <img class="rounded-lg-3" src="./assets/images/lightbulb.jpeg" alt="" width="540" style="width: 540px; position: relative; top: 40px;">
      </div>
    </div>
    <div class="pt-lg-5" style="display: flex; justify-content: center;">
      <a href="#portfolios"><img src="./assets/images/scroll-down.png" alt="" style="padding-top: 90px; width: 4rem; opacity: .2;"></a>
    </div>
  </div>
```

```css
  /* Typewriter Effect */
  @keyframes typing {
    0%, 21% { content: ""; }
    1%, 20% { content: "c"; }
    2%, 19% { content: "cr"; }
    3%, 18% { content: "cre"; }
    4%, 17% { content: "crea"; }
    5%, 16% { content: "creat"; }
    6%, 15% { content: "creati"; }
    7%, 14% { content: "creativ"; }
    8%, 13% { content: "creative"; }
    9%, 12% { content: "creatives"; }

    22%, 41% { content: ""; }
    23%, 40% { content: "d"; }
    24%, 39% { content: "de"; }
    25%, 38% { content: "des"; }
    26%, 37% { content: "desi"; }
    27%, 36% { content: "desig"; }
    28%, 35% { content: "design"; }
    29%, 34% { content: "designe"; }
    30%, 33% { content: "designers"; }

    42%, 65% { content: ""; }
    43%, 64% { content: "d"; }
    44%, 63% { content: "de"; }
    45%, 62% { content: "dev"; }
    46%, 61% { content: "deve"; }
    47%, 60% { content: "devel"; }
    48%, 59% { content: "develo"; }
    49%, 58% { content: "develop"; }
    50%, 57% { content: "develope"; }
    51%, 56% { content: "developer"; }
    52%, 55% { content: "developers"; }

    66%, 77% { content: ""; }
    67%, 76% { content: "M"; }
    68%, 75% { content: "MM"; }
    69%, 74% { content: "MMI"; }
    70%, 73% { content: "MMIT"; }

    78%, 100% { content: "N"; }
    79%, 99% { content: "No"; }
    80%, 98% { content: "Nor"; }
    81%, 97% { content: "Nors"; }
    82%, 96% { content: "Norst"; }
    83%, 95% { content: "Norste"; }
    84%, 94% { content: "Norstel"; }
    85%, 93% { content: "Norstella"; }
  }
  @keyframes blink {
    0%, 100% { opacity: 1; }
    50% { opacity: 0; }
  }
```

```js
  const ctx = document.getElementById("chart").getContext('2d');
  const myChart = new Chart(ctx, {
    type: 'line',
    data: {
      labels: ["sunday", "monday", "tuesday",
      "wednesday", "thursday", "friday", "saturday"],
      datasets: [{
        label: 'Coffee',
        backgroundColor: 'rgba(161, 198, 247, 1)',
        borderColor: 'rgb(47, 128, 237)',
        data: [1000, 2000, 3000, 4000, 4000, 5000, 5000],
      }]
    },
    options: {
      scales: {
        yAxes: [{
          ticks: {
            beginAtZero: true,
          }
        }]
      }
    },
  });
```

### Continued development

We hope to add to this project throughout the next year of our team's growth.

## Authors

- Aaron Shields
- Carlie Sages
- Alison Jacobson
- Shakirah Ghant-David
- Danielle King
- Steven Noyes