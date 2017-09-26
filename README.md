# Ajax Discussion Questions

## First Question

Given the following code list the order of console.logs:

```javascript
console.log("Hello")

fetch('https://randomuser.me/api/')
  .then( res => res.json() )
  .then( data => {
    console.log("Hi") 
  })

console.log("Sup?")
```

## Second Question

When fetchData is executed what will be console logged?

```javascript
function fetchData(){
        var data = fetch('https://randomuser.me/api/')
          .then( res => res.json() )
          .then( res => res )
        console.log(data)	
}

fetchData()
```

What will be console logged when the following code is run? Why?

```javascript
function fetchData(){
        var data = fetch('https://randomuser.me/api/')
          .then( res => res.json() )
          .then( console.log )
}

fetchData()
```

## Third Question

In your own words: what does asynchronous mean?

## Fourth Question

Write out the request and response cycle. What is it's purpose? How does it work?

## Fifth Question

Check out the JSON you get from making a GET request to [this](https://randomuser.me/api/) url (https://randomuser.me/api/).
Open up the Github repositiory for this reading and view the provided `src/index.html` file in the browser. In `src/index.js`, make an AJAX request to that url when the button is clicked and append the retrieved information to the DOM. Use the labels to append the right data in the appropriate h4's, h3's and img tags.
