# Ajax Discussion Questions

## First Question

Given the following code list the order of console.logs:

```javascript
	console.log("Hello")
	
	$.ajax({
		url: 'https://randomuser.me/api/',
		success: function(data){
			console.log("Hi")
		}
	})
	
	console.log("Sup?")
```

## Second Question

When fetchData is executed what will be console logged?

```javascript
function fetchData(){
	var data = $.ajax({
		url: 'https://randomuser.me/api/',
		success: function(response){
			// Do something with response
		}
	})
	console.log(data)	
}

fetchData()
```

## Third Question

In your own words: what does asynchronous mean?

## Fourth Question

Write out the request and response cycle. What is it's purpose? How does it work?

## Fifth Question

Your task is to use [this](https://randomuser.me/api/) url to make an AJAX request. Have someone use the provided index.js to render the returned data to the provided index.html. Use the labels to append the right data in the h4's, h3's and img tags.