# Teterev Vladislav
## Contacts
* Phone: +375291272395
* Gmail: vladtett2000@gmail.com
* Telegram: https://t.me/Ydenn
* LinkedIn: https://www.linkedin.com/in/vlad-teterev-b355331a1/
## About me
Purposeful, responsible and handsome front-end developer in future:)
## Skills
* HTML/CSS
* JS/NodeJS
* Webpack
* Git
* React
* ESLint
* Docker
## Sample code

```
function spyOn (func) {
  let count = 0;
  let callingValuesCollection = new Set();
  let returningValuesCollection = new Set();
  
  const spy = (...args) => {
    const returnValue = func(...args);
    
    args.forEach((item) => {
      callingValuesCollection.add(item);
    });
    returningValuesCollection.add(returnValue);
    count++;
    return returnValue;
  };
  
  spy.callCount = () => count;
  spy.wasCalledWith = (val) => callingValuesCollection.has(val);
  spy.returned = (val) => returningValuesCollection.has(val);
  
  return spy;
}
```
## Education
**Secondary, Gymnasium №41 2017.**
**Student in Vistula university in Warsaw**

## English 
B2 Upper-Intermediate

Certificate: https://www.efset.org/cert/ryD3Kz.


