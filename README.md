# PooUI

A CSS file to help you quickstart development on the web.
PooUI supplies you with the basic needs of a website like buttons, cards, ropdowns.. with little to no effort, while also leaving room for creative reedom and customization.

Basic elements like button, input and text are already styled, and you can add custom elements with classes like a dropdown menu.

  
## Buttons
  
  ### Normal Button
  ![button](https://gcdnb.pbrd.co/images/EVTJn1p3jp0w.png?o=1)
  
  When adding a button element, if you have imported PooUI.css you should notice the button now has a shadow and a hover and click animation.
  ````
  <button> Button </button>
  ````
  
  
  ### Big Button
  ![big button](https://gcdnb.pbrd.co/images/I8haWNxLeCI2.png?o=1)
  
  This button is bigger than the normal one and has a bold text.
  ````
  <button class="button-big"> Big button </button>
  ````
  
  
  ### Outlined Button
  ![outlined button](https://gcdnb.pbrd.co/images/clTmy4YMq5Bh.png?o=1)
  
  This button has a transparent background and a border.
  ````
  <button class="button-outlined"> Outlined </button>
  ````
  
  
## Chips
  ![chips](https://gcdnb.pbrd.co/images/Cn5ArvAvL73A.png?o=1)
  
  There are two types of chips: A normal chip and a colored chip.
  ````
  <p class"chip">This is a Chip</p>
  <p class"chip-colored">Colored Chip</p>
  ````
  
## Dropdown Menu
  ![dropdown](https://gcdnb.pbrd.co/images/Y8L5yNrjNHMc.png?o=1)
  
  The dropdown menu opens when an item with the class of "has-dropdown" is clicked, and is hidden when the user clicks outside of it.
  
  For the dropdown menu to work, you must have a clickable element with the class of "has-dropdown", and a div with the class of "dropdown" directly below it.
  ````
  <button class="has-dropdown"> Click to open dropdown </button>
  <div class="dropdown">
      <button>Item 1</button>
      <button>Second Item</button>
      <button>Third</button>
      <button>Item 3!!</button>
  </div>
  ````
  
## Tooltip
![tooltip](https://gcdnb.pbrd.co/images/dvMUjq36HDyC.png?o=1)

For the tooltip to work, you must have any element with the class of "has-tooltip", and a div with the class of "tooltip" directly below it.
````
<span class="has-tooltip"> Hover over me </span>
<div class="tooltip"> This is a tooltip! </div>
````

## Cards

  ### Standard Card 
  ![card](https://gcdnb.pbrd.co/images/elT0Bz9EACD9.png?o=1)
  
  Card is used for grouping some information in one place. 
  
  The Card is a div element with the class of "card", and you can optionaly add a header image by adding an img element with the class of "card-header".
  ````
  <div class="card">
      <img class="card-header" src="..."/>
      <h3>Standard Card</h3>
      <p>This is a card for grouping some information in one place</p>
      <a href="...">Link to somewhere</a>
  </div>
  ````
  
  
  ### Alert Card
  ![alert card](https://gcdnb.pbrd.co/images/T8hhgwRnkQVY.png?o=1)
  
  The Alert Card is a div element with the classes of "card" and "card-alert".
  ````
  <div class="card card-alert">
      <p> This is an alert card, It can be used for important information! </p>
  </div>
  ````
  
  
  ### Button Card
  ![button card](https://gcdnb.pbrd.co/images/MPuwOhUl7YPb.png?o=1)
  
  The Button Card is a div element with the classes of "card" and "card-button".
  ````
  <div class="card card-button">
      <h3> Button card </h3>
      <p> This is a card that is also a button. It has a bold background color, and it can also be clicked on. </p>
  </div>
