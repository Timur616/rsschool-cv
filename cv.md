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
## About Me
Born in Minsk, finished 9 classes and went to college. At the moment I work for MTZ
I like to watch anime and draw
## Education
 * College: Belarusian State College of Building Materials Industry
