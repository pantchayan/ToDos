# Course Outlines

## 2D Visualisations and Animations using D3.js
#### TOTAL VIDEOS ~ 60

<br>

### 1. Intro to the course

-> D3.js is a library that helps us visualise data using SVGs. <br>
-> Show the official page and examples <br>
-> Sneak peak into the course
<br>
-> Pre-requisites
<br>
-> How to go about the course? EXplain Flow and Best practices
<br>

<br>

<hr>

## Module 1 - SVG basics [3 vids]

<br>

### 2. What are SVGs ?

-> Explain in detail how SVGs work. <br>
-> How they are more efficient than JPGs and PNGs <br>
-> Introduce SVG tags in HTML

### 3. Shapes in SVGs

-> Introduce < rect >, < circle >, < text >, < path > tags <br>
-> Dive deep into < path > tag and explain about _d string attribute_ <br>
(As D3.js is all about manipulating these complex d strings)<br>

### 4. Bonus: Advantages of SVG and free resources

-> Why switch graphics to SVG from PNG and JPEG?<br>
-> Free resources to do so.<br>
-> Next up D3.js<br>
<br>

<hr>

## Module 2 - D3.js Basics [7 vids]

<br>

### 5. Let's get started with D3.js (Intro)

-> Setting up D3
<br>
-> Data driven modification
<br>
-> Loading and Transforming
<br>

### 6. DOM Operations with D3

-> D3 DOM operations (Selection, Insertion, Updation)
<br>
-> Chaining methods and attributes in D3
(build a simple square and perform all these activities)

### 7. Shapes in D3

-> Build shapes using D3 and relate it to how we did it in 1st Module <br>
-> Texts in D3

### 8. Groups in D3

-> Grouping elements in D3 <br>
-> Helps transforming multiple elements at once <br>
-> Explain using an example

### 9. Using Data with D3

-> Explain data usage and joining using a rect <br>
-> Update height, width, and color <br>
-> Use arrow functions <br>

### 10. Joining to multiple Rects

-> Make a Bar graph structure with rects <br>
-> Update values and change height and color

### 11. Enter Selection in D3.js

-> Explain problem with previous method <br>
-> Introduce Enter selection and Updating
<br>
<br>
<hr>

## Module 3 - Digital Clock (Mini Project) [7 vids]

https://github.com/pantchayan/D3-learn/tree/main/Digital%20Watch


<br>
<img src="./img/digital-clock.png">


### 12. Overview of the project

-> List out the features and knowledge being used <br>
-> Set up project files

### 13. Logic for the clock

-> Explain the logic and structure behind implementation
<br>
-> Calling setInterval at every second and running render function to update digits
<br>
-> Code the above point and log out the time in console

### 14. Making a single digit

-> Explain how we can make a digit by grouping squares in D3

### 15. Make the digit tick

<br>
-> Data matrix of 0s and 1s
<br>
-> Make the digit count till 0-9


### 16. \*\* Implement structure for 6 digits

### 17. \*\* Make the clock work

### 18. Discuss learning outcomes

-> D3.js basics till enter selection

<br>
<br>

<hr>

## Module 4 - Graphs and Charts using D3.js [9 vids]

### 19. Lets make Bar graphs
-> How to go about it <br>
-> Why we need scales <br>

### 20. Linear Scale in D3.js
-> Linear scales <br>

### 21. Band Scale in D3.js
-> Band scales <br>


### 22. Making rects for Bar Chart
-> Importing data from JSON 
<br>
-> Updating positions (Maths) to match x-y axes

### 23. Axes Groups
-> Making axis in D3
<br>
-> Axis groups implementation 

### 24. Hooking up Firestore (Real time updation)
-> Firestore integration to the project.
<br>
-> Get data from firestore and log to console

### 25. D3 Optic Pattern (Updating elements)
-> Creating update function 
<br>
-> Explain: Enter and Exit selection
<br>
-> D3 Interval function
<br>
-> Explain steps

### 26. Join method in D3
-> Simpler way out 

### 27. Transitions in D3
-> Intro to simple transitions <br>
-> Make bar graph enter and update smooth

### Misc. Tweens and Interpolations
-> Give intro, and explain how basic transitions are easy


<br>
<br>

<hr>

## Module 5 - Investment Tracker (Doughnut Chart) [10 vids]
https://github.com/pantchayan/D3-learn/tree/main/Investment%20Tracker
<br>

<img src="./img/investment-tracker.png">

### 28. Overview of the project
-> List out the features and knowledge being used <br>
-> Set up project files

### 29. HTML and CSS Template
-> Use Bootstrap <br>
-> No need to code live: Just explain the code.

### 30. Integrate Firestore and Define schema
-> Use index.js to push data to the db
<br>
-> Use graph.js to retrieve data

### 31. Pie charts and arcs
-> Explain in detail how arcs are formed
-> .pie() function 
-> .arc() function
-> Pie chart to Doughnut chart conversion

### 32. Ordinal Scale

-> Bringing colors to the chart

### 33. Making Update function

-> d3 optic pattern in action

### 34. Enter and Update Tween

-> Adding transitions to data updation and initial injestion

### 35. Adding Legend

-> Adding circles
<br>
-> Adding texts


### 36. User Interactivity in D3
-> Handle Mouse events and hover  <br>
-> Click : Delete the item <br>
-> Hover : Show Details and Opacity change <br>

### 37. Ending notes and Learning Outcomes



<br>
<br>

<hr>

## Module 6 - More in D3.js [3 vids]

###  38. How to make elements Responsive

3 ways :
<ol>
    1. Event listener
</ol>
<ol>
    2. View box (Design course stuff)
</ol>
<ol>
    3. Media query + Event Listener
</ol>


### 39. Line graphs in D3

-> Make a simple line graph to demonstrate

### 40. **Racing graphs

<img src="./img/Racing-Bar-Chart.gif">


<br>
<br>

<hr>

## Module 7 - Google Fit UI [11 vids]

<img src="./img/google-fit-ui.png">

### 41. Overview of the project
-> Setting up project files
<br>
-> Discussion on flow / knowledge

### 42. HTML, CSS Template
-> Using a bit of Tailwind CSS

### 43. Make the main rings (Steps and heart points)
-> Use dummy data to make rings

### 44. Make the central numbers


### 45. Hook up Local Storage
-> Use user input data to update the rings

### 46. Update main stats

### 47. Make daily rings

### 48. Make weekly target bar

### 49. Make daily steps bar graph

### 50. Make energy expended bar graph

### 51. Finishing up the project and Learning outcomes

<br>

<br>

<hr>

## Module 8 - SVG animations [3 vids]
https://github.com/pantchayan/D3-learn/tree/main/SVG%20Animations

### 52. Intro to SVG Animations
-> How SVG animations are better than gifs and videos? <br>
-> How can D3 help? Very clean and systematic animations

### 53. Pepcoding logo animation

<img src="./img/Pep-animation.gif">

### 54. NADOS logo animation

<img src="./img/NADOS-Animation.gif">


<br>

<br>

<hr>

## Module 9 - SVG Football Game [6 vids]

https://github.com/pantchayan/football-game
<img src="./img/Football-Game.gif">


### Will take up around 6 videos (55 - 60)

<br>
<hr>
<hr>
<hr>


## FINISH









 










