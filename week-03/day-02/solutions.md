1.

2.

3.

4. function greeting(greetingText) {
  return (function salutation(name) {
    return greetingText + ' , ' + name;
  });
}

var dayGreeting = greeting('Good morning');
var nightGreeting = greeting('Good evening');

var name = 'Art';

console.log(dayGreeting(name));
console.log(nightGreeting(name));