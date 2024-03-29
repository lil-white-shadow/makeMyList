# makeMyList

## Link: https://lil-white-shadow.github.io/makeMyList/

## Demo

[Tab-1673001188804.webm](https://user-images.githubusercontent.com/96262157/210990707-afd3fd6e-c5b4-41f4-bd2e-aaee80e74e55.webm)


## About



Scope: 
To make a library application where user can add their favorite movies, shows, or books. I have used CSS grid to neatly display each title.

Functionality:
The user can add title name, director / author / actor name, and can give their rating from 1 to 5. There are three buttons at the bottom of each card to signify whether a particular movie or book had been watched or read by the user.
The title of the item is mandatory. The application gives 1 star to any item by default.
A user can only add one card at a time, if the add button gis clicked while one add card is open, the add button turns red to show the error.

Thoughts & Challenges:
There are no libraries or frameworks used to make this, all code is written from scratch.
While, there is a bunch of CSS to make it look neat, the heart of this app is JS. There is tons of DOM manipulation done in the background starting from creating card to submitting it. So, there were many challenges along the way.
- Adding cards was a little tricky at first. But then, just adding a single card only was bit more challenging.
- Once card was added, the next challenge was to get user input. While a modal window is an obvious solution for many reasons, I opted to use the card itself as a form. Since there are only 3 input fields, it looks much more nicer this way.
- There is basic validation built in the "form" but I spent more time in CSS to style when showing the validation error.
- Once user input is taken, it is validated and stored in an object from where it is displayed upon hitting the submit button. DOM elements are added and removed by JavaScript since the form needs to be "erased" before displaying the finished card in the same space after submitting.
