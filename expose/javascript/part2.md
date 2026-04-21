# Part 2
<ol>
  <li>It will print 3 because the for loop runs 3 times incrementing the value of i 3 times.</li>
  <li>It will print 150 because the final time discountedPrice was reassigned prices[i] = 300 and discount = 0.5 and 300*(1-0.5)=150.</li>
  <li>It will print 150 because the final time discountedPrice was reassigned its value was 150 and multiplying and dividing that value by 100 still gives 150.</li>
  <li>The code will return an array containing [50,100,150] because in each iteration of the for loop the price with the 50% discount is calculated and pushed to the array discounted which is then returned by the function discountPrices.</li>
  <li>There will be an error because the code is trying to access the variable i but it is out of scope.</li>
  <li>There will be an error because the code is trying to access the variable discountedPrice but it is out of scope.</li>
  <li>It will print 150 because the final time discountedPrice was reassigned its value was 150 and multiplying and dividing that value by 100 still gives 150. Because finalPrice is defined in the same code block as line 14 it is in scope and there is no error.</li>
  <li>The code will return an array containing [50,100,150] because in each iteration of the for loop the price with the 50% discount is calculated and pushed to the array discounted which is then returned by the function discountPrices. Because discounted is defined in the same code block as line 16 it is in scope and there is no error.</li>
  <li>There will be an error because the code is trying to access the variable i but it is out of scope.</li>
  <li>The code will print 3 because the const variable length was declared in the same scope as line 14 and it was assigned to be the value of prices.length which is 3.</li>
  <li>The code will return an array containing [50,100,150] because in each iteration of the for loop the price with the 50% discount is calculated and pushed to the array discounted which is then returned by the function discountPrices. Because discounted is defined in the same code block as line 16 it is in scope and there is no error.</li>
  <li>
    <ul>
      <li><code>student.name</code></li>
      <li><code>student["Grad Year"]</code></li>
      <li><code>student.greeting()</code></li>
      <li><code>student["Favorite Teacher"].name</code></li>
      <li><code>student.courseLoad[0]</code></li>
    </ul>
  </li>
  <li>
    <ul>
      <li>A. 32 because when adding a string and an integer the integer gets converted to a string and the 2 strings are concatenated together</li>
      <li>B. 1 because when subtracting a string and an integer the string is converted to an integer</li>
      <li>C. 3 because when adding an integer and null null is converted to 0</li>
      <li>D. 3null because when adding a string and null null is converted to a string</li>
      <li>E. 4 because when adding an integer and the boolean true true is converted to 1</li>
      <li>F. 0 because when adding false and null false and null both get converted to the value 0</li>
      <li>G. 3undefined because when adding a string and undefined undefined gets converted to a string</li>
      <li>H. NaN because when adding an integer and undefined undefined gets converted to NaN and any number-NaN=NaN</li>
    </ul>
  </li>
  <li>
    <ul>
      <li>A. true because comparing strings and integers converts the string to an integer</li>
      <li>B. false because comparing 2 strings compares them in alphabetical order and 2 is greater than 1</li>
      <li>C. true because comparing strings and integers converts the string to an integer</li>
      <li>D. false because the strict equality operator checks if the 2 values are equal without type conversion</li>
      <li>E. false because when comparing the boolean true and an integer true is converted to 1</li>
      <li>F. true because Boolean(2) returns true because 2 is a truthy value in JavaScript</li>
    </ul>
  </li>
  <li>The == operator compares the 2 values with type conversion and the === operator compares the 2 values without type conversion.</li>
  <li><a href="https://github.com/paulm130/sp26-cse110-lab4/blob/main/expose/javascript/part2-question16.js" target="_blank">part2-question16.js</a></li>
  <li>The value returned by modifyArray is [2,4,6]. This is because for each value in array it will pass that value into doSomething which will multiply that value by 2. Then that value will get pushed to newArr. When the for loop finishes running then modifyArr returns newArr with all the values of array doubled.</li>
  <li><a href="https://github.com/paulm130/sp26-cse110-lab4/blob/main/expose/javascript/part2-question18.js" target="_blank">part2-question18.js</a></li>
  <li>1 <br>
  4 <br>
  3 <br>
  2 but it takes a second for the 2 to print out.
  </li>
</ol>
