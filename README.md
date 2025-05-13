# inst326-exercise-9-car-class-solved
**TO GET THIS SOLUTION VISIT:** [INST326 Exercise 9-Car Class Solved](https://www.ankitcodinghub.com/product/inst326-exercise-9-car-class-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93594&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;INST326 Exercise 9-Car Class Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
# Background

For this exercise you will develop a module containing a Car class. Instances of the class will be able to turn and drive forward. They will have three attributes: x, y and heading. x and y will be the coordinates of the car object. For this assignment, x coordinates will increase as a car moves east; y coordinates will increase as a car moves south. Heading indicates the direction in which the car will drive, in degrees. For this assignment, a heading of 0 indicates due north; a heading of 90 is due east; etc.

# Instructions

**Car class**

Create a class called Car. Define the following methods:

**__init__() method**

Define a method called __init__() (note the double underscores). Your method should have one required parameter (self) and three optional parameters as follows (please use these exact names):

– x: the starting x coordinate of the car, as a float.[1] Default: 0.

– y: the starting y coordinate of the car, as a float. Default: 0.

– heading: the starting heading, as a float. Default: 0.

Your __init__() method should set three attributes (x, y, and heading) to the values of their

corresponding parameters.

**turn() method**

Define a method called turn() that has two required parameters, self and a number of degrees expressed as a float. A positive number of degrees indicates a clockwise turn; a negative number of degrees indicates a counterclockwise turn. Use the following steps to assign a new value to the heading attribute (these can be combined into a single expression):

– Add the specified number of degrees to the previous value of heading.

– Reduce the result of step 1 modulo 360 (this ensures that heading is between 0 and 360).

For example, if heading is 270 and the number of degrees is 100, the turn() method should set

heading to (270 + 100) mod 360, which is 10.

**drive() method**

Define a method called drive() that has two required parameters, self and a distance expressed as a float.

In the formulas below, d is the distance; h is the heading in radians (you will need to convert the heading from degrees to radians).

Update the x attribute by adding d sin(h) to the attribute’s current value. (Hint: the += operator is your friend).

Update the y attribute by subtracting d cos(h) from the attribute’s current value. (Hint: the -= operator is your friend).

**sanity_check() function**

Define a sanity_check() function that takes no arguments. This function is not supposed to be part of the Car class—please de-indent the function header accordingly.

Inside this function, create an instance of the Car class. Have your instance follow these steps:

– Turn 90 degrees.

– Drive 10 units.

– Turn 30 degrees.

– Drive 20 units.

Print the location of your instance on one line and the heading on the next line, in the following

format:

&gt; Location: 41.34235262, 17.999999999

&gt; Heading: 75

**if __name__ == “__main__”: statement**

At the end of your code, write an if __name__ == “__main__”: statement that invokes your sanity_check() function.

# driving_range.py

The program driving_range.py is designed to import your class and create a graphical representation of two instances of your Car class. Your class serves as the back-end for this program. The program depends upon your code following the naming conventions specified in these instructions.

driving_range.py requires the Tkinter module. If you installed Python 3.9 from Python.org, Tkinter should normally have been included. If you run into issues related to Tkinter, please contact the

instructor.

To use driving_range.py, ensure that it is in the same directory as car.py. Then, open the VS Code built-in terminal and type python3 (on macOS) or python (on Windows) followed by a space and the name of the program.

&nbsp;
