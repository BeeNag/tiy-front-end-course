1. setTimeout(function () {
    
    var elementNode = document.querySelector ('ul');
    var firstNode = elementNode.firstChild;
    var changeNode1 = firstNode.setAttribute ('class', 'first');
    
    console.log (changeNode1);
       
    var elementNode = document.querySelector ('ul');
    var lastNode = elementNode.lastChild;
    var changeNode2 = lastNode.setAttribute ('class', 'last');
       
    console.log (changeNode2);
       
    }, 0);

2. setTimeout(function () {
      
      var text = document.getElementById ('latest').textContent;
      
      document.getElementById ('latest').textContent = 'Monday is finally here';
      
      
    }, 0);

3. <!DOCTYPE html>
<html>
<head>
  <style>
    @import url(https://fonts.googleapis.com/css?family=Roboto+Condensed:400,400italic,300italic,300,700,700italic);
    
    * {
      font-family: 'Roboto Condensed', sans-serif;
    }
    
    h1 {
      font-weight: 500;
    }
    
    img {
      height: 400px;
      float: left;
      margin: 0 10px 0 0;
    }
    
    .fact {
      background-color: yellow;
    }
    
    footer {
      background-color: black;
      color: white;
      padding: 20px;
    }
  </style>
  <meta charset="utf-8">
  <title>JS Bin</title>
  <script>
    setTimeout(function () {
      
      var element = document.createElement ("h1");
      var text = document.createTextNode ("The Shard");
      element.appendChild (text);
      document.body.appendChild (element);
      
      var element2 = document.createElement ("h2");
      var text2 = document.createTextNode ("The tallest building in Western Europe");
      element2.appendChild (text2);
      document.body.appendChild (element2);
      
      var image = document.createElement ("img");
      var imgsrc = image.setAttribute ("src", "https://upload.wikimedia.org/wikipedia/commons/thumb/0/07/The_Shard_from_the_Sky_Garden_2015.jpg/480px-The_Shard_from_the_Sky_Garden_2015.jpg");
      var imgalt = image.setAttribute ("alt", "The Shard");
      document.body.appendChild (image);
      
      var element3 = document.createElement ("p");
      var text3 = document.createTextNode ("The Shard, also referred to as the Shard of Glass, Shard London Bridge and formerly London Bridge Tower, is an 95-storey skyscraper in Southwark, London, that forms part of the London Bridge Quarter development.");
      element3.appendChild (text3);
      var span = document.createElement ("span");
      var spanclass = span.setAttribute ("class", "fact");
      var text4 = document.createTextNode ("The Shard's construction began in March 2009");
      span.appendChild (text4);
      element3.appendChild (span);
      var text5 = document.createTextNode ("; it was topped out on 30 March 2012 and inaugurated on 6 July 2012. Practical completion was achieved in November 2012. The tower's privately operated observation deck, the View from the Shard, was opened to the public on");
      element3.appendChild (text5);
      var strong = document.createElement ("strong");
      var text6 = document.createTextNode ("1 February 2013");
      strong.appendChild (text6);
      element3.appendChild (strong);
      var text7 = document.createTextNode (".");
      element3.appendChild (text7);
      document.body.appendChild (element3);
      
      var element4 = document.createElement ("p");
      var span2 = document.createElement ("span");
      var spanclass2 = span2.setAttribute ("class", "fact");
      var text8 = document.createTextNode ("Standing 309.6 metres (1,016 ft) high");
      span2.appendChild (text8);
      element4.appendChild (span2);
      var text9 = document.createTextNode (", the Shard is currently ");
      element4.appendChild (text9);
      var span3 = document.createElement ("span");
      var spanclass3 = span3.setAttribute ("class", "fact");
      var text10 = document.createTextNode ("the joint 92nd tallest building in the world");
      span3.appendChild (text10);
      element4.appendChild (span3);
      var text11 = document.createTextNode (" and the fourth tallest building in Europe and the tallest building in the European Union. It is also the second-tallest free-standing structure in the United Kingdom, after the concrete tower at the Emley Moor transmitting station. The glass-clad pyramidal tower has 72 habitable floors, with a viewing gallery and open-air observation deck on the ");
      element4.appendChild (text11);
      var span4 = document.createElement ("span");
      var spanclass4 = span4.setAttribute ("class", "fact");
      var text12 = document.createTextNode ("72nd floor");
      span4.appendChild (text12);
      element4.appendChild (span4);
      var text13 = document.createTextNode (", at a height of ");
      element4.appendChild (text13);
      var span5 = document.createElement ("span");
      var spanclass5 = span5.setAttribute ("class", "fact");
      var text14 = document.createTextNode ("244.3 metres (802 ft)");
      span5.appendChild (text14);
      element4.appendChild (span5);
      var text15 = document.createTextNode (". It was designed by the Italian architect Renzo Piano and replaced Southwark Towers, a 24-storey office block built on the site in ");
      element4.appendChild (text15);
      var span6 = document.createElement ("span");
      var spanclass6 = span6.setAttribute ("class", "fact");
      var text16 = document.createTextNode ("1975");
      span6.appendChild (text16);
      element4.appendChild (span6);
      var text17 = document.createTextNode (". The Shard was developed by Sellar Property Group on behalf of LBQ Ltd, and is jointly owned by Sellar Property and the State of Qatar.");
      element4.appendChild (text17);
      document.body.appendChild (element4);
      
      var element5 = document.createElement ("ul");
      var list = document.createElement ("li");
      var text18 = document.createTextNode ("Cost: ");
      list.appendChild (text18);
      var span7 = document.createElement ("span");
      var spanclass7 = span7.setAttribute ("class", "fact");
      var text19 = document.createTextNode ("~£435 million");
      span7.appendChild (text19);
      list.appendChild (span7);
      element5.appendChild (list);
      var list2 = document.createElement ("li");
      var text19 = document.createTextNode ("Completed: ");
      list2.appendChild (text19);
      var span8 = document.createElement ("span");
      var spanclass8 = span8.setAttribute ("class", "fact");
      var text20 = document.createTextNode ("July 2012");
      span8.appendChild (text20);
      list2.appendChild (span8);
      element5.appendChild (list2);
      var list3 = document.createElement ("li");
      var text21 = document.createTextNode ("Opening: ");
      list3.appendChild (text21);
      var span9 = document.createElement ("span");
      var spanclass9 = span9.setAttribute ("class", "fact");
      var text22 = document.createTextNode ("1 February 2013");
      span9.appendChild (text22);
      list3.appendChild (span9);
      element5.appendChild (list3);
      document.body.appendChild (element5);
      
      var element6 = document.createElement ("p");
      var text23 = document.createTextNode ("Mr Prescott would only approve skyscrapers of exceptional design. For a building of this size to be acceptable, the quality of its design is critical. He is satisfied that the proposed tower is of the highest architectural quality.");
      element6.appendChild (text23);
      document.body.appendChild (element6);
      
      var element7 = document.createElement ("footer");
      var element8 = document.createElement ("p");
      var text24 = document.createTextNode ("Thanks for vising our website.");
      element8.appendChild (text24);
      element7.appendChild (element8);
      var element9 = document.createElement ("p");
      var small = document.createElement ("small");
      var text25 = document.createTextNode ("Designed in 2015");
      small.appendChild (text25);
      element9.appendChild (small);
      element7.appendChild (element9);
      document.body.appendChild (element7);
   
    }, 0);
  </script>
</head>
<body>

</body>
</html>

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