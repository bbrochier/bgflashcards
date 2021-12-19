# bgflashcards

```
const url1 = 'https://raw.githubusercontent.com/bbrochier/bgflashcards/main/data.json'
const response = await fetch(url1)
const data = await response.text()
const jsonData = JSON.parse(data)
console.log(jsonData.cards[0].title)
```
