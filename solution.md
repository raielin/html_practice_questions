HTML and CSS practice questions
============

### 1. Make the following have each sentence on their own line without extra <p> tags
```
<p> Hi this is my opening sentence. <br> I want this to be on the line below it. </p>
```

### 2. Change the header to a link
```
<a href="#"><h2> Make me a Link </h2></a>
```

### 3. Write a css statement to change the second item purple
```
<ul>
  <li class="awesome" id="penguin"> Penguins</li>
  <li class="awesome" id="shark"> Whale Sharks</li>
  <li class="awesome" id="falcon"> Falcons! </li>
</ul>

<style>
  #shark{ color: purple; }
</style>
```

### 4. Debug the following
```
<h3><a href="#"> WHAT AM I DOINGS GAH! </a></h3>
```

### 5. Write css to change only the column1 heaer to tomato
```
<div class="wrapper">
  <div class="column1"><h2> I'm a column </h2></div>
  <div class="column2"><h2> Hey me too </h2></div>
</div>

<style>
  .column1 h2{color: tomato;}
</style>
```

### 6. Create a list without numbers
```
<ul>
  <li> hi </li>
  <li> im </li>
  <li> a list! </li>
</ul>
```

### 7. Make this image 400 pixels wide without changing the height/width ratio using css
```
<img src="http://www.maplewiki.net/images/c/c7/Monster_Giant_Tomato.png" alt="Tomato Monster">

<style>
  img{
    width: 400px;
    height: auto;
  }
</style>

```

### 8. Give the image above a border radius of 30 px using a css statement
```
<style>
  img {
    border-radius: 30px;
  }
</style>

```

### 9. Make a button that says "Click Me!" and color it blue
```
<button type="submit">Click Me!</button>
```

### 10. Write a css statement to color it blue
```
button{
  color:blue;
}
```

### 11. Make the two div's with class "happy" fit side by side in the wrapper div using css
```
<div class="wrapper">
  <div class="happy"><h2> HaPpY </h2></div>
  <div class="happy"><h2> hApPy </h2></div>
</div>
<style>
  .happy{
    width: 50%;
    margin: 0px;
  }
</style>
```

### 12. Create margin for the div  with 10px on the top, 20px on the bottom, 30px on the left, and 40px on the right. In one css statement
```
<div class="crazy">
  <h2>Crazy Larry's Crazy Emporium</h2>
  <p>We Have all the craziest discounts in town!</p>
</div>
<style>
  .crazy{
    margin: 10px 40px 20px 30px;
  }
</style>
```

### 13. Change the opacity of tomato div to 50% opacity
```
<div class="tomato">
  <h2>Crazy Tomatos's Crazy Tomato Emporium</h2>
  <p>We Have all the craziest tomatoes in town!</p>
</div>

<style>
  .tomato{
    color: tomato;
    height: 450px;
    width: 500px:
    opacity: 0.5;
  }
</style>
```

### 14. Using the same tomato div change the font of the header to Monotype Corsiva and size of 50px
```
<style>
  tomato h2{
    font-family: 'Monotype Corsiva';
    font-size: 50px
  }
</style>
```

### 15. Make all of the headers the same color in one css statement
```
<h1> Big! </h1>
<h2> Medium </h2>
<h3> Small </h3>

<style>
  h1, h2, h3, {
    color: tomato;
  }
</style>
```
