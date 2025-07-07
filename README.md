# buzzword-bingo &  📇 Flashcards

### 📂 About Storage:

- no database, just browser local storage
- all data will be deleted when cache is cleared
- import & export in **`json`** format
- created data on the website will have timestamp ids

### :paperclip: Data Structure:

```json
{
  "stacks": [
    {
      "id": <number>,
      "title": <string>,
      "cardIds": [
        <number>,
        <number>
      ]
    }
  ]
  "cards": [
    {
      "id": <number>,
      "front": <string>,
      "back": <string>,
      "stackId": <number>,
      "status": <boolean>
    }
  ]
}
```

**front & back:** content of your flahscard  :information_source: \n will be replaced with \<br\> in frontend

**status boolean:**  
*`false`* =  :x: Need to learn!
*`true`* = :white_check_mark: Got it!
