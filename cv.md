##Timur Petrov
## Contacts
  * Location: Minsk, Belarus
  * Phone: +375 33 659 08 39
  * Email: timyr5239q@gmail.com
  * GitHub: Timur616
## Code Example
 function duplicateCount(text){
  let result = 0,
      soltingObject = {};
  text.toLowerCase().split('').map(str => {
      if (!soltingObject.hasOwnProperty(str)) {
        soltingObject[str] = 0;
      } else {
        if (soltingObject[str] === 0) {
          result += 1;
        }
        soltingObject[str] = soltingObject[str] + 1;
      }
  });
  return result;
}
