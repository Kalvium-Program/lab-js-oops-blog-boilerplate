![Logo-nav](https://user-images.githubusercontent.com/109285740/201395942-2eb263fa-89b8-46bb-95f0-7d5d295074db.png)


# Kalvium Lab | JS BLOG

We have learned Object-oriented programming and how class and inheritance work in JavaScript. Now lets work with our Viking friends, applying all of the concepts we have just learned.

## Instructions
We must write the correct code in the src/app.js file. In this file you will find the following starter code:
```
class Blog{

}
```

In this case, it says that Blog class should receive 2 arguments (title & detail), so we have to write the correct code. Let's make the Blog class receive two arguments:
```
class Blog{
constuctor(title,detail){}

}
```
Make sure that all of your test cases are passed. Test cases can be checked - by opening -> index.html file.

### Progression 1: WRITE UP
Modify the Blog class and add two **methods** to it: addTitle(), and addDescription().

### class
- should receive two arguments title and detail.
- should receive title as first argument.
- should receive detail as second argument.

### addTitle()
- should be a method.
- should receive 0 arguments.
- should display the title of Blog as H1.
```
     var title_card = document.createElement('h1');
        title_card.setAttribute("id","blog-title");
        console.log(title_card);
        document.getElementById('card-text').appendChild(title_card);
        title_card.innerHTML += this.title;
```

### addDescription()
- should be a method.
- should have 0 arguments.
- should display the description as a paragraph.
![Image description](https://i1.faceprep.in/ProGrad/Mern-Blog-1.png)

![Image description](https://i1.faceprep.in/ProGrad/Mern-Blog-2.png)

### Progression 2:  SHOW EM UP

Setup `EventListeners`, so that we can display the entire blog for the users. 

Create two **functions** -

1. `helperAddPost()` - This function is called, when the user clicks on the Add new Post button.
                       Upon clicking on the button, the popup frame should display and close.
                       ( HINT: Do check the CSS )

2. `helperPost()` -  This function is called, when the user enters a title and the detail, and wants to
                     submit that information. So, when the submit is clicked, this function should be called. After clicking on the submit button, the content should be displayed on the screen itself.

![Image description](https://i1.faceprep.in/ProGrad/Mern-Blog-3.png)

Happy Coding Kalvium❤️

