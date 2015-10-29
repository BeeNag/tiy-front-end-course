2.  setTimeout(function () {
      
      var text = document.querySelector ("p").firstChild.nodeValue;
      
      console.log (text);
      
    }, 0);

3. setTimeout(function () {
    
      var select = document.querySelector ("div");
      var text = select.firstChild;
      var value = text.textContent
      
      console.log (value);
    
    }, 0);

4. setTimeout(function () {
      
      var text;
      var link;
      
      var array = document.querySelectorAll ("li");
      
      
      for (iterator = 0; iterator < array.length; iterator++) {
        text = array[iterator].textContent;
        link = ["http://www.visitlondon.com/", "http://en.parisinfo.com/", "https://en.wikipedia.org/wiki/New_York_City"]
        array[iterator].removeChild (array[iterator].firstChild);
        var element = document.createElement ("a");
        var href = element.setAttribute ("href", link[iterator]);
        var newText = document.createTextNode (text);
        element.appendChild (newText);
        array[iterator].appendChild (element);
      }
      
    
    }, 0);

5. setTimeout(function () {
      
      var array = document.querySelectorAll ("li");
      
      for (iterator = 1; iterator < array.length; iterator = iterator + 2) {
        var atr = array[iterator].setAttribute ("class", "highlight");
      }
      
    
    }, 0);

6. setTimeout(function () {
     
     var sum = 0; 
     var images = [
  'http://valuestockphoto.com/freehighresimages/roast_veg_DSC2834.jpg',
  'http://valuestockphoto.com/freehighresimages/snowy_trees1995.jpg',
  'http://valuestockphoto.com/freehighresimages/nt_alice_springs140362.jpg',
  'http://valuestockphoto.com/freehighresimages/diwali_deepavali_DSC2292.jpg'
];
      
      
      var element = document.createElement("img");
      var imgsrc = element.setAttribute ("src", images[sum]);
      var imgalt = element.setAttribute("alt", "PICTURE");
      var imgWidth = element.setAttribute("width", "50%");
      document.body.appendChild(element);
      
      var intervalID = window.setInterval(myCallback, 2000, [images]);

      function myCallback() {
        var imgsrc = element.setAttribute ("src", images[sum]);
        sum++;
        
        if (sum >= images.length) {sum = 0};
      
    }
  }, 0);