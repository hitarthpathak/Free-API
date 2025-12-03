# Free-API By Hitarth Pathak

A collection of completely **free, public JSON APIs**.

**No Authentication · No Rate Limits · No CORS · Forever Free**

### Available APIs :-
| Name                    | Endpoint                                                                                   | Items | Categories / Genres                          |
|-------------------------|--------------------------------------------------------------------------------------------|-------|----------------------------------------------|
| **E-Commerce Products** | https://hitarthpathak.github.io/Free-API/E-Commerce-Products.json                          | 36    | men · women · kids                           |
| **Jokes**               | https://hitarthpathak.github.io/Free-API/Jokes.json                                        | 50    |                                              |
| **Movies Collection**   | https://hitarthpathak.github.io/Free-API/Movies-Collection.json                            | 25    | horror · comedy · mystery · sci-fi · romance |


### How To Use :-
**E-Commerce Products :**
  <html>

    fetch("https://hitarthpathak.github.io/Free-API/E-Commerce-Products.json")
      .then(res => res.json())
      .then(data => console.log(data));

    OR

    axios.get('https://hitarthpathak.github.io/Free-API/E-Commerce-Products.json')
      .then(res => console.log(res.data));

  </html>

**Jokes :**
  <html>

    fetch("https://hitarthpathak.github.io/Free-API/Jokes.json")
      .then(res => res.json())
      .then(data => console.log(data));

    OR

    axios.get('https://hitarthpathak.github.io/Free-API/Jokes.json')
      .then(res => console.log(res.data));

  </html>

**Movies Collection :**
  <html>

    fetch("https://hitarthpathak.github.io/Free-API/Movies-Collection.json")
      .then(res => res.json())
      .then(data => console.log(data));

    OR

    axios.get('https://hitarthpathak.github.io/Free-API/Movies-Collection.json')
      .then(res => console.log(res.data));

  </html>
