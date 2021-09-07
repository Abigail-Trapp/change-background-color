# change-background-color
a basic app that changes the background color at the click of a button

padding: 1 rem p rem; influences width and height of a button

text-transform: capitalize; capitalized every first letter

.colorBtn:hover{background: rgb(0,0,0);} changes color when cursor is over button with cursor pointer

My biggest challenge was creating the changeColor function. However, what I learned was I don't need to actually loop through the color array. Using Math.floor(Math.random) times the length of the array will already randomly select an index from the array. This creates the randomly selected index that exists inside the colors array. the background color of the web page's body then equals to that random index when the button is clicked.  