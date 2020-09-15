# Denis Oleksiuk

## Contact Info
[email](DenisOleksiuk95@gmail.com) [telegram](https://t.me/Den_Iz_Kieva)

I very like programming and to see the result comleted of project.

- Skills:
  - HTML
  - CSS, SASS, SCSS
  - JavaScript (Simple React)

  
## Code example 
 
```javascript
use strict;
const inpRub = document.querySelector(‘#rub’), inpUsd = document.querySelector(‘#usd’);

inpRub.addEventListener(‘input’, () => { const request = new XMLHttpRequest();

request.open('GET', 'js/current.json');
request.setRequestHeader('Content-type', 'application/json; charset=utf-8');
request.send();

request.addEventListener('load', () => {
    if (request.status === 200) {
        const date = JSON.parse(request.response);
        inpUsd.value = (+inpRub.value / date.current.usd).toFixed(2);
    } else {
        inpUsd.value = "Что-то пошло не так";
    }
}); })
```

## Experiance 
  - Udemy cours web development   
  - JavaScript + React
  
## English
  - 2 mounth online cours
  - studying in the application lingualeo 
