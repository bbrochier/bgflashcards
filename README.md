# bgflashcards


### Async/await
```
const url1 = 'https://raw.githubusercontent.com/bbrochier/bgflashcards/main/data.json'
const response = await fetch(url1)
const data = await response.text()
const jsonData = JSON.parse(data)
console.log(jsonData.cards[0].title)
```

### Promise
```js
fetch('https://raw.githubusercontent.com/bbrochier/bgflashcards/main/data.json')
  .then((response) => response.json())
  .then((data) => { 
    console.log(data)
  })
```
