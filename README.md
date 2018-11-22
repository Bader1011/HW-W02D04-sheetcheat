# HW-W02D04 - make a cheatsheet for yourself!

Your review sheet can be in any digital format you want, a word document, a google doc, a markdown file… whatever you want! Submissions will be done via email.

> 📢 📢  *NOTE:*  This is not all what we cover in the class so feel free to customize your own sheet and add more content

## Your cheatsheet should include the following topics:

* ### Variables:
  * How to declare a variable: (code)
  
  
    ```javascript
    // write the syntax
     ``` by using (var) for example: var user
  * How to console.log the value of a variable: (code)
    ```javascript
    // write the syntax
     ```console.log();
* ### conditionals:
  * ##### Operators:
    * How to use the `"=="` operator: 
       `write a definition ` 
       
   it used to make sure that the two value are equle.       
    * How to use the `"==="` operator: 
       `write a definition ` 
       
 it used to make sure that the bouth of value and types are equle.      
       
    * How to use the `">"` operator: 
        `write a definition `
 it used to  cheak wich varibles' value greater than others.       
   * ##### How to write an if Statements 
      ```javascript
        // write the syntax
   if statements are group of conditions  that need to run/executed a condation if it's true, or go to other condation if it's false.     
   if (condition) is true
       return value
     var number = 7;
       if (number <9){
       return "the value is greater than your number";
       } else {
       return "Go ahead";
       }         
           
       ``` 
 * ### functions:
    * How you declare a function: 
      ```javascript
        // write the syntax 
   funcation () {
   }
             
       ```
    * This is the other way to declare a function: 
      ```javascript
        // write the syntax 
var newFuncation= funcation (){
}
                
       ```
    * This is a function that adds 4 to any number:
        ```javascript
        // write the syntax
       ```
     function newF(num){
     return num +4;
     } 
     
    * This is a function that capitalizes any word: 
        ```javascript
        // write the syntax
       ```
   var newText="generalassembly";
   var upperText = newText.toUpperCase();
   
    * We use functions because:
    
 we need it to perform a particular task   
    
     `write a definition `
* ### datatypes:
  * ##### Strings
    * A string is: 
    a text value must be between duble quotes "" or even single''.
        `write a definition `
    * You can capitalize a string by: 
    adding new funcation than create new varibles in it. the first one to store the text inside it and the other one for capitalize it. for examle : funcation = newFuncation (){
    
    var newText="generalassembly";
    var upperText = newText.toUpperCase();
        ```javascript
        // write the syntax```
        stringname.toUpperCase();
    
    * Concatentation is: 
    to make to strings in one string
        `write a definition `
    * An example of concatenation:
         ```javascript
        // write the syntax ```
    var name1= "general";
    var name2= "assembly";
    var togather= name1.concat(name2);          
       
        
        
  * ##### Numbers:
    * The `%` operator is: 
       `write a definition ` 
    it is an operator to deviend a number for example : 15%2 =1
    
    * Here is an example of the `%` operator in use:
       ```javascript
        // write the syntax
       ```
  function newFunction() {
    var i = 15;
    var x = i % 2;
    
    
  * ##### Arrays:
    * An index is: 
    (definition) It is a variable that store more than one elements 
    * You can access an element in an array like this: (code) 
    (Array name)[element order started from 0] for example: var array2 = cars[0];
    * Map:
      * .map is an array method that: 
      
     create new array and change the elements without change the original array
         `write a definition `
      * An example of map is: 
        ```javascript
           // write the syntax
   var pizzaToppings = [
  'pepperoni',
  'cheese',
  'sardines',
  'mushrooms',
  'pineapples',
  'soap',
  'sausage'
];

var pizzaToppingsCaps = pizzaToppings.map(function(topping){
  return topping.toUpperCase();
})
         ```
    * Filter:
      * .filter is an array method that: 
 it is like if statement but inside a loop.   
     
          `write a definition `
            
      * An example of filter is: 
        ```javascript
           // write the syntax
           
var fullTimeAndRate = employees.filter(function(FullAndRate){

    
  return (FullAndRate.status =='full-time' && FullAndRate.weeklyPay < 500);
  });   

console.log(fullTimeAndRate); 
         ```
    * forEach:
      * .forEach is an array method that: 
         `write a definition `  
         
         to callback every property inside the array
         
      *  An example of forEach is: 
         ```javascript
           // write the syntax
     var array2 = [9, 4, 3]; 
    arr.forEach(function(element) {
         console.log(element);
         
      });              
         ``` 
         
         
         
  

   * ##### objects
     * How to access a property  
        ```javascript
           // write the syntax
        ``` 
  opject.property
  
* ### loops
     *   how to make for loop 
         ```javascript
           // write the syntax
          ```
          for (i = startValue; i <= endValue; i++){
          }
* ### Querying the DOM
  ```javascript
 it is a method that match all the elements and select the first element that match. 
   // write the syntax
  ```
  
  document.querySelector(CSS selectors)
 
* ### Creating a new element in the DOM
  ```javascript
   // write the syntax
  ```
  var new1 = document.createElement("p");
* ### Appending a new element to the DOM
  ```javascript
   // write the syntax
  ```
  wlwmwnt.appendsChild(varible name);
* ### Updating the style properties
  ```javascript
   // write the syntax
  ```
  
  element.setAttribute(the name of the attribute, the value of the attribute)
