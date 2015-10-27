<p>1. function () {
	var message = 'Welcome!';
}

2. function validateParameter(message) {
  
  if (typeof message === 'string' && message.length > 0){
     return true;
  } else {
     return false;
  }
}
</p>
<br>
<p>3. function findInList (string, character) {
   var characterCounter = 0;
  
  if (typeof string === 'string' && typeof character === 'string') {
    for (var iterator = 0; iterator < string.length; iterator++) {
      if (string [iterator].toLowerCase () === character.toLowerCase ()) {
        characterCounter = characterCounter + 1;
      }
    }
  }
  
return characterCounter;  
}

findInList();
</p>
<br>
<p>4. function squareList (arrayOfNumbers) {
  var square = []; 
  
  if (typeof arrayOfNumbers === 'object') {
  
  for (var counter = 0; counter < arrayOfNumbers.length; counter++) {
    square.push ((arrayOfNumbers [counter])*(arrayOfNumbers [counter]));
  }
  }
  
  return square;
}

squareList();
</p>
<br>
<p>5.function filterList (array) {
  var filteredArray = [];
  
  if (typeof array === 'object') {
    for (var iterator = 0; iterator < array.length; iterator++) {
      if (typeof array [iterator] === 'string' && array [iterator].length > 0) {
        filteredArray.push (array [iterator]);
      }
    }
  }
  return filteredArray;
}

filterList();
</p>
<br>
<p>6. function iterateList (myArray, myFunction) {
  for (var i = 0; i < myArray.length; i++) {
    myFunction (myArray [i]);
  }
}
</p>
<br>
<p>7. var add5 = add(5);
var sum = add5(10);

function add(parameter) {
  return (function (parameter2) {
    return (parameter + parameter2);
  });
}

console.log (sum);
</p>
<br>
<p>8. Having message as a parameter produces the undefined, removing it will fix:

var message = (function () {
  var message = 'Welcome';

  function getMessage() {
    return message;
  }

  return {
    getMessage: getMessage
  };
})();

console.log(message.getMessage());
</p>
<br>
<p>9. function mergeArrays (array1, array2) {
  var finalArray = [];
  
  for (var counter = 0; counter < array1.length; counter++) {
    finalArray.push ([array1 [counter], array2 [counter]]);
    
  }
  return finalArray;
}

mergeArrays([1,2,3], ['a', 'b', 'c']);
</p>
<br>
10.

11.

12.

