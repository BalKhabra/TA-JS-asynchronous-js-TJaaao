## XMLHttpRequest + Promise

- Create a function named `fetch` which can accept one parameter a `url` and returns a promise.
- Use `XMLHttpRequest` to make a network request using the `url` from parameter
- When the data is loaded resolve the promise with the value
- If there is any issue loading data reject the promise with an error message

Add-on:

- Refactor the image search app you created (in previous exercise) to use the function `fetch` you created above.


```js

function fetch(url){
    return promise
}

let promise = new Promise(fetch)



```