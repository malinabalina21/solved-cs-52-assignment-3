Download Link: https://assignmentchef.com/product/solved-cs-52-assignment-3
<br>
<h3><strong>part_a: pi_approximator</strong></h3>

<p style="font-weight: 400;"> is a mathematical quantity that associates the area of a circle to its radius.  Write a program that approximates the value of  by using the Leibniz formula:

<p style="font-weight: 400;">Since this formula is an infinite series, you will need to prompt the user for how accurate they want the calculation to be.  Rather than using one big pile of main( ), you need to use functions for this calculation and pass parameters and work with return values.  In addition, you need to include atleast one const int or const double declaration.  Finally, embed your program in a loop so that the calculation can be repeated as often as the user wishes. Round to two decimal places.

<table>

 <tbody>

  <tr>

   <td>Iterations: <strong>1</strong>Pi is approximated to be <strong>4.00</strong>.</td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td>Iterations: <strong>2</strong>Pi is approximated to be <strong>2.67</strong>.</td>

  </tr>

 </tbody>

</table>

<table>

 <tbody>

  <tr>

   <td>Iterations: <strong>10</strong>Pi is approximated to be <strong>3.04</strong>.</td>

  </tr>

 </tbody>

</table>

<p style="font-weight: 400;">

<ul style="font-weight: 400;">

 <li>Write a program which produces this output as the examples above:</li>

</ul>

<table>

 <tbody>

  <tr>

   <td>Iterations: <strong>{USER INPUT}</strong>Pi is approximated to be<strong> {approximation rounded to 2nd decimal place}</strong>.</td>

  </tr>

 </tbody>

</table>

<ul style="font-weight: 400;">

 <li>You are provided the flexibility to create your own files.</li>

 <li>While there will likely be mutliple methods, the main method must be named getPi(…) as a simple interface to a user.</li>

</ul>

<h3><strong>part_b: inventory_system</strong></h3>

<p style="font-weight: 400;">Write a C++ program that calculates the inventory on-hand for Widget Co, an internationally renowned Widget maker located in Santa Monica.  Each month, Widget Co. produces 123 new widgets from its production line during a good month, but only 52 widgets from its production line during a bad month.  In addition, each month, its sales team takes orders for some number of widgets.  If they are on-hand, Widget Co. reduces its inventory of widgets.  If not on-hand, it compiles a back-order for the requested widgets.  In order to receive full credit, you must use functions for this calculation and pass parameters and work with return values.  The program dialogue should look like this:

<table>

 <tbody>

  <tr>

   <td>Welcome to Widget Co.!Month: <strong>0</strong>    Number of widgets on-hand: <strong>0</strong>  Number back-ordered: <strong>0</strong>Was it a good or bad month (g/b)? <em><strong>g</strong></em>How many did the sales force sell? <em><strong>15</strong></em>Continue(y/n)? <strong>y</strong>Month: <strong>1</strong>    Number of widgets on-hand: <strong>108</strong>  Number back-ordered: <strong>0</strong>Was it a good or bad month (g/b)? <strong>b</strong>How many did the sales force sell? <em><strong>150</strong></em>Continue(y/n)? <strong>y</strong>Month: <strong>2</strong>    Number of widgets on-hand: <strong>10</strong>  Number back-ordered:<strong> 0</strong>Was it a good or bad month (g/b)? <strong>b</strong>How many did the sales force sell? <em><strong>100</strong></em>Continue(y/n)? <strong>y</strong>Month: <strong>3</strong>    Number of widgets on-hand: <strong>0</strong> Number back-ordered: <strong>38</strong>Was it a good or bad month (g/b)? <strong>g</strong>How many did the sales force sell? <strong><em>2</em></strong><em><strong>00</strong></em>Continue(y/n)? <strong>n</strong>At the end of month <strong>3</strong>, you wound up with <strong>0</strong> widgets on-hand and <strong>115</strong> widgets back-ordered</td>

  </tr>

 </tbody>

</table>

<ul style="font-weight: 400;">

 <li>Again, you are expected to create all files.</li>

 <li>The main high level method must be named runInvSys(…).</li>

</ul>

<h3><strong>Overall</strong></h3>

<ul style="font-weight: 400;">

 <li>Your submission should follow this organization:

  <ul>

   <li>part_a

    <ul>

     <li>main.cpp</li>

     <li>my_pi_approximator.h</li>

     <li>my_pi_approximator.cpp</li>

    </ul></li>

   <li>part_b

    <ul>

     <li>main.cpp</li>

     <li>my_inventory_system.h</li>

     <li>my_inventory_system.cpp</li>

    </ul></li>

  </ul></li>

</ul>