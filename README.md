# cs1331---homework-02-solved
**TO GET THIS SOLUTION VISIT:** [CS1331 – Homework 02 Solved](https://www.ankitcodinghub.com/product/cs1331-homework-02-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123789&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1331 - Homework 02 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
Authors: Akul, Allison, Angela, Aanya, Aqdas, Julia

Problem Description

You are a developer for the legendary racer, Carroll Shelby, and his company Shelby American Inc. He needs your help to keep track of his various cars. Your job is to create a vehicle database representing all of the various vehicles that Shelby has that utilizes the basics of inheritance, hierarchies, and abstract classes.

Solution Description

You will be creating the files below with the following names:

• Car.java

• ShelbyMustang.java

• FordGT.java

Car.java

Instance Variables:

• String name o Every car person has a name for their prized car.

• String make

o This represents the make of the car (i.e. Ford, Shelby).

• double fuelLevel

o This represents the fuel level of the car.

• int horsepower

o This represents how much horsepower the car has.

• boolean previousUpgrade

o Shelby always wants to know if a car has been brought back to him for an upgrade before.

• double MAX_FUEL_LEVEL

o This represents the maximum fuel level that a car can have.

o Its value should initially be set to 100 and its value should not be able to be changed once it is initialized. It should be the same across all instances of the Car class.

o This variable should be directly accessible by all child classes of the Car class without getters and setters whether or not they are within the same package.

• All instance variables in this class should be private unless otherwise stated Constructors:

• Include a constructor that takes in name, make, fuelLevel, horsepower, and previousUpgrade in this exact order.

o Make sure the constructor parameters have the same type as their corresponding fields. o If the passed-in fuelLevel is greater than MAX_FUEL_LEVEL, set fuelLevel to be MAX_FUEL_LEVEL

Methods:

• toString()

o Must properly override Object’s toString() method o Should return:

“Car named: {name}, Make: {make}, Fuel Amount: {fuelLevel rounded to 1 decimal place}, HP: {horsepower}”

• equals()

o Must properly override Object’s equals() method

o Two Cars are equal if they have the same name, make, and horsepower values

• upgrade()

o This method increases the horsepower if this Car has not been upgraded before.

 If the car’s existing horsepower is less than 200 it increases the horsepower by 100. If the car’s existing horsepower is at least 200 then the horsepower is increased by 50.

o This method should also set previousUpgrade to true. A Car object can only be upgraded once.

o This method does not return anything.

• race()

o This method takes in a Car object, should be abstract, and does not return anything to the user.

• Necessary (and only necessary) getters and setters.

• All methods in this class should be public unless otherwise stated

ShelbyMustang.java

• int racesWon

o ShelbyMustangs are made to race. As such you should have an instance variable that keeps track of how many races the respective ShelbyMustang has won.

• All instance variables in this class should be private unless otherwise stated Constructors:

• Include a constructor that takes in name, make, fuelLevel, horsepower, previousUpgrade and racesWon values in this order.

o Ensure that you call the constructor located in the Car class from this constructor to maximize code reuse

• Include a no-arguments constructor that creates a ShelbyMustang with the following default values:

o name is “Carroll” make is “Shelby Automotives”, fuelLevel is 100, horsepower is 350, previousUpgrade is false, racesWon is 0

o Ensure that you use constructor chaining

Methods:

• toString()

o Must properly override Object’s toString() method

o Should return:

“Car named: {name}, Make: {make}, Fuel Amount: {fuelLevel rounded to 1 decimal place}, HP: {horsepower}, Races Won: {racesWon}” o Must utilize the toString() method from the Car class

• equals()

o Must properly override Object’s equals() method

o Two ShelbyMustangs are equal if they have the same name, make, horsepower, and racesWon values

o Must utilize the equals() method from the Car class

• race()

o This method takes in a Car object and overrides the abstract method present in the Car class.

o Two cars can race only if they are the same type (ShelbyMustang) and both fuelLevels are above 50. If either of the fuel levels are not greater than 50 or the type is not the same, then print to the console the following message:

“{name of car passed in} could not race {name of car invoking race}” o If both requirements are met, then two cars can race.

§ After each race decrease the fuel levels of each car by 25.

§ Increment the racesWon value (you’ll have to do some casting to be able to access it) for the winning car. The car with the greater horsepower wins. If their horsepower is equal, then the car with the greater number of races won wins the race. You should print to the console the following message:

“{name of winning car} won against {name of losing car}”

§ If the horsepower and racesWon values are the same, a tie will occur. You should print to the console the following message:

“{name of car passed in} tied with {name of car invoking race}”

• All methods in this class should be public unless otherwise stated

FordGT.java

This file represents the Ford GT that Carrol Shelby designed and developed for Ford Automotive. This class also must inherit from the Car class.

Instance Variables:

• double weight

o Ford GTs are designed to compete on the track against other trained drivers. Many things are considered for professional race cars and one of those things is weight.

• String driverName

o Along with a plethora of other factors, companies always want to find the best drivers to drive their cars in races.

• All instance variables in this class should be private unless otherwise stated Constructors:

• Include a constructor that takes in name, make, fuelLevel, horsepower, previousUpgrade, weight, and driverName values in that order.

o Ensure that you call the constructor located in the Car class from this constructor to maximize code reuse

• Include a no arguments constructor that creates a FordGT with the following default values o name is “Pony”, make is “Ford”, fuelLevel is 100, horsepower is 450, previousUpgrade is false, weight is 3300, and driverName is “Ken Miles”

o Ensure that you use constructor chaining Methods:

• toString()

o Must properly override Object’s toString() method o Should return:

Car named: {name}, Make: {make}, Fuel Amount: {fuelLevel rounded to 1 decimal place}, HP: {horsepower}, Weight: {weight}, Driver:

{driverName}

o Must utilize the toString() method from the Car class

• equals()

o Should override Object’s equals() method

o Two Ford GTs are equal if they have the same name, make, horsepower, and weight values

o Must utilize the equals() method from the Car class

• upgrade()

o This method overrides the upgrade method located in the Car class.

o This method increases the horsepower. If the car’s existing horsepower is less than 200 it increases the horsepower by 100. If the car’s existing horsepower is at least 200 then the horsepower is increased by 50.

o This method also increases the fuel level by 50.

§ If the fuelLevel goes above MAX_FUEL_LEVEL, set it to MAX_FUEL_LEVEL o This method does not return anything.

• race()

o This method takes in a Car object and overrides the abstract method present in the Car class.

o Two cars can race only if they are the same type (FordGT) and both fuelLevels are above 50. If either of the fuel levels are not greater than 50 or the type is not the same, then print to the console the following message:

“{name of car passed in} could not race {name of car invoking race}”

o If the fuel levels are above 50, then two cars can race.

§ After each race decrease the fuel levels of each car by 25.

§ The car with the greater horsepower wins. If the horsepowers are equal, then the car with the greater weight wins the race. You should print to the console the following message (you’ll have to do some casting to be able to access the driver):

“{name of winning car} with {driverName} as the driver won against {name of losing car} with {driverName} as the driver”

o If the horsepower and weight values are the same, a tie will occur. You should print to the console the following message:

“{name of car passed in} tied with {name of car invoking race}”

• All methods in this class should be public unless otherwise stated

Clarifications and Example Output

Allowed Imports

Feature Restrictions

There are a few features and methods in Java that overly simplify the concepts we are trying to teach or break our auto grader. For that reason, do not use any of the following in your final submission:

• var (the reserved keyword)

• System.exit

Checkstyle and Javadocs

You must run Checkstyle on your submission. The Checkstyle cap for this assignment is 7 points. If you don’t have

Checkstyle yet, download it from Canvas -&gt; Modules -&gt; Checkstyle Resources (Section B &amp; C) or General Information (Section D) -&gt; checkstyle-8.28.jar. Place it in the same folder as the files you want Checkstyled. Run checkstyle on your code like so:

$ java -jar checkstyle-8.28.jar yourFileName.java

Starting audit…

Audit done.

The message above means there were no Checkstyle errors. If you had any errors, they would show up above this message, and the number at the end would be the points we would take off (limited by the Checkstyle cap mentioned above). The Java source files we provide contain no Checkstyle errors. In future homeworks we will be increasing this cap, so get into the habit of fixing these style errors early!

Additionally, you must Javadoc your code.

Run the following to only check your Javadocs:

$ java -jar checkstyle-8.28.jar -j yourFileName.java

Run the following to check both Javadocs and Checkstyle:

$ java -jar checkstyle-8.28.jar -a yourFileName.java

For additional help with Checkstyle see the CS 1331 Style Guide.

Collaboration

No collaboration is allowed on this assignment. See syllabus for more details.

Turn-In Procedure

Submission

To submit, upload the files listed below to the corresponding assignment on Gradescope:

• Car.java

• ShelbyMustang.java

• FordGT.java

Make sure you see the message stating “HW02 submitted successfully”. From this point, Gradescope will run a basic autograder on your submission as discussed in the next section.

Gradescope Autograder

For each submission, you will be able to see the results of a few basic test cases on your code. Each test typically corresponds to a rubric item, and the score returned represents the performance of your code on those rubric items only. If you fail a test, you can look at the output to determine what went wrong and resubmit once you have fixed the issue.

The Gradescope tests serve two main purposes:

• Prevent upload mistakes (e.g. non-compiling code)

• Provide basic formatting and usage validation

In other words, the test cases on Gradescope are by no means comprehensive. Be sure to thoroughly test your code by considering edge cases and writing your own test files. You also should avoid using Gradescope to compile, run, or Checkstyle your code; you can do that locally on your machine.

Important Notes (Don’t Skip)

• Non-compiling files will receive a 0 for all associated rubric items

• Do not submit .class files

• Test your code in addition to the basic checks on Gradescope

• Run Checkstyle on your code to avoid losing points

• Submit every file each time you resubmit

• Read the “Allowed Imports” and “Feature Restrictions” to avoid losing points

• Check on Piazza for a note containing all official clarifications
