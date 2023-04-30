Download Link: https://assignmentchef.com/product/solved-ece-210b-homework-2
<br>



In this homework, you will review some of the topics discussed in class this week, including approximating derivatives and integrals and different matrix operations. You will also see that for loops are usually not the best idea in MATLAB…

<ol>

 <li>Here you will be approximating derivatives and integrals on the sine function.

  <ul>

   <li>Create two vectors with entries evenly spaced between 0 and pi. One vector should be of length 100 and the other should be of length 1000. Then apply these vectors to the function <em>sin</em>(2<em>x</em>).</li>

   <li>Approximate the derivative of this function by taking differences of adjacent elements and dividing by the space between them. Do this for both vectors.</li>

   <li>What function should this be? (I hope you know this…) Check this by applying the original evenly-spaced vectors to this function, taking the elementwise difference between the resulting vectors and the derivative vectors and computing the magnitudes of the max differences between them. Which length produces better results?</li>

   <li>Now use <em>cumsum </em>and <em>cumtrapz </em>to approximate the integral of <em>sin</em>(2<em>x</em>). Do this for both lengths as before.</li>

   <li>Subtract 0.5 from every element of each integral vector to center their graphs at 0. Then compare the computed vectors with the analytic antiderivative as before. Return the magnitude of the max error for each of the four cases.</li>

   <li>Plot the best approximation for the integral. Add a title to the plot.</li>

  </ul></li>

 <li>Perform the following matrix operations:

  <ul>

   <li>Use <em>reshape </em>to create the 10×10 matrix.</li>

   <li>Flip <em>A </em>upside down.</li>

   <li>Flip the 3rd row left to right.</li>

   <li>Create a row vector which is the column wise sum of the entries of <em>A</em>.</li>

   <li>Create a column vector which is the row wise product of the entries of <em>A </em>(Check out <em>prod</em>).</li>

   <li>Delete the 6th row.</li>

  </ul></li>

 <li>Create a 300×500 matrix <em>B </em>where. Do this, and time how long each one takes with <em>tic toc</em>, using three methods:

  <ul>

   <li>Using a for loop without preallocation.</li>

   <li>Using a for loop with preallocation.</li>

   <li>Using only elementwise matrix operations (<em>meshgrid </em>may be useful here).</li>

  </ul></li>

</ol>


