
All Morning Challenges:  Challenges - Coder Academy

Day 02 - Terminal Stuff
Scott’s challenges
One: Terminal —
Using only terminal, navigate your file system to:
    1. Create a file structure that matches your family tree e.g. a root folder with 2 grandparents, 2 parent directories in each with child folders within those
    2. Create a folder called students. Inside the folder, create a few student text files 'jane.txt', etc
    3. Rename one of the student files to include full names ('jane doe.txt') - note what happens if you try to use a space. How can you get around this?
    4. Delete one student
Two: Running Ruby —
    1. Open IRB from your command line by running `irb`
    2. Try some basic math (1+1 *enter*)
    3. Quit IRB by sending the `exit` command
Three: Running Ruby from a file —
    1. Use terminal to create a new file (e.g. `touch my-cool-app.rb`)
    2. Open the file in your code editor (e.g. `atom my-cool-app.rb`)
    3. Write the same Ruby code (1+1) and save + close the file.
    4. Run the code! We can do this with the `ruby` command. (e.g. `ruby my-cool-app.rb`)
    5. The code runs, but nothing is returned on the screen. Add `puts` to the start of your code and try running the code again! (e.g. `puts 1+1`)
    6. Experiment with some basic ruby!
My Challenges
One: Man —
    1. Google some interesting commands
    2. Use the ‘man’ command to read about the command you have found
    3. Experiment with this command, and its flags
Two: Help —
    1. Repeat the above process, but use the —help flag to get info on the command

Day 03 - Strings and Numbers
Gretchen’s Morning Challenges
- check which version of ruby you have installed (if it isn’t 2.4.1, then please see a teacher)
- create a ruby folder inside of your apps folder (if you haven’t already done so)
- create a file inside the ruby folder called ‘strings’ with the ruby extension
Scott’s Challenges
One:
In IRB calculate — 
    1. How many hours are in a year.
    2. How many minutes are in a decade?
    3. How many seconds old are you?
Two:
What do you think happens when you combine the following floats and integers?
Is the result a float or an integer?
Try computing these in irb —
    1. 3.0 / 2
    2. 3 / 2.0
    3. 4 ** 2.0
    4. 4.1 % 2
Why is 4.1 % 2 => 0.099. Look up in the ruby docs or google modulo
Three:
put "Hello world!" onto the screen Make a new variable called 'name', set it's value to your name (as a string)
Beast Mode
    1. Use interpolation to put your name on the screen
    2. Make a new variable called 'siblings', set it's value to the number of siblings you have (integer) Use code to put your number of siblings on the screen. Use interpolation to pretty it up, E.g.: “Total Siblings: 3” Use code to increase your number of siblings by one.
    3. Use interpolation again to put your new number of siblings on the screen
My Challenges
1. Describe in words the following code (this could be done in front of the class):
    - this_var = 0
    - this_string = "a string"
    - x = 5.5
    - badly_named = x * 7
    - fergus = “christmas tree”
    - nigel = “one “ + “ “two “ + “three.”
    - beer = fergus
2. Take the calculations from earlier, and store them in variables. That is, as you do the mathematics, store each line of the calculation in a variable, and use this on the next line to calculate the next step. Many students will just string out the calculation on one line and not go through this process.
3. Write a program that asks the user for input that requests the user to input a number representing a temperature. If the number entered is above 30, reply to them “It’s too HOT!” or similar. Give appropriate responses for the temperatures between 20 and 30, 10 and 20, 0 and 10, and below zero.
4. Write a program that takes the user input of an animal that can be represented as an emoji. Use a case statement to print the emoji relating to the animal entered. Extension: use your code to change any instances of certain animal names with the relevant emoji.
5. Imagine you are standing at a vending machine (or fast food counter). Give some products (of your choice) some prices, and then ask the user for input. Depending on how much the user inputs, give the options for what they can buy given the amount of money they have. For part one just give the options as one product OR another. Extension: Now change it to be able to tell them all the combinations of products that they can buy with the given amount.
6. 

Day 04 - Arrays, if/else, loops
Gretchen’s Morning Challenges
- create a well named variable that contains the amount of time it took you to get to class
- create a complete sentence  that lets us know how you got to class and how long it took
- print this complete sentence

you are working at a bar where you have a current backlog of drinks to make:
 3 party parrot cocktails
2 party parrot waters
and
6 party parrot beers

write a program that asks the customer for their order.
if they order a party parrot cocktail, add one to the number of party parrot cocktails you need to make,
if they order a party parrot water, add one to the number of party parrot waters you need to make,
if they order a party parrot beer, add one to the number of party parrot beers you need to pour

print the final drinks order so you know what to make

****
cocktails sell for $22, and cost $8 to make
beer sell for $12, and cost $3 to pour
water sell for $6, and cost $0.15 to make

print out the total profit for the orders you have

Scott’s Challenges 
	One
    1. Create an array called four_letter_animals with the following animals (in this order):
        * Calf
        * Duck
        * Elephant
        * Goat
        * Lamb
        * Lion
        * Mule
        * Dog
    2. Add Puma to the end of the array
    3. Insert Joey after Goat and before Lamb
    4. Delete Dog
    5. Reverse the order of the array
    6. Replace Elephant with Foal
    7. Add Bear to the end of the array
Beast Mode
Ask the user for three or more grocery items, store them in a list (array). It's OK to ask three times. Show the list to the user. Can’t remember how to use a specific ruby feature/syntax? That’s normal! Google + Ruby docs :)
** Finish the challenge before moving onto any bonus points **
    * Bonus 1: Try using the `.length` method to tell the user how many items are in their list. 
    * Bonus 2: Sort the list alphabetically before showing it to the user 
    * Bonus 3: Are you using gets.chomp multiple times? A 3.times loop might tidy your code. 
    * Bonus 4: If the user tries to add 'Ice Cream', secretly replace it with 'Broccoli' 
    * Bonus 5: Ask the user for quantities too. You'll need to use a hash. Show a nice looking list back to the user.
My Challenges
	One
	Describe in words the following expressions:
        1. arr = []
        2. arr2 = [“this”, “that”, “other”]
        3. if (large <= small) etc
        4. etc.
	Two
        1. Make an infinite loop and have it print “I’m stuck!”
        2. Kill the loop
        3. Make the loop end after 20 iterations
	Three
        1. Use the Ruby inbuilt pseudorandom to create an array of 100 random numbers
        2. Sum the array without using the inbuilt sum method
        3. Sum the array using the inbuilt sum method
        4. Find the average of this array
	Four
Make four loops that iterates 10 times and then break using the four types of loops we have discussed so far (.each, for, while, and until)
	Five
Give the user a list of options: 1. Add dish, 2. Delete dish, 3. View selected dishes, p. Pay, and x. Exit. In your Ruby file, run a while loop that presents these options, gets input from a user (as a number), and then acts on this input. For example, if the user selects 1, you will add a dish, and so you will take further input from the user and add that into an array. Do a similar job for the rest of the options with the appropriate inputs from the user, or the appropriate output.
	Six
		Take the code from the problem above, and refactor it using a switch statement

Day 05
Morning Challenges
1. sit beside someone different in a different spot from yesterday
2. A business called “The Company” created a new phone called the companyPhone that needs packing to send away for sale. The Company needs to know how many phones in their pretty new packaging (rectangular prisms) that measures: with  width 5cm, length 7.4cm, and depth 4cm we can fit into a box that is 32cm wide,  43cm long and 22.1cm high.   (think about writing some pseudo code first that steps through all the commands you need to write. Keep it as simple as you can - this is not a ‘bin packing’ problem)
Scott’s Challenges
1. Partner up! Together and by hand with markers on the desk, describe your computer as a hash. Use any data types you can think of, as hash values can be anything!
2. When you're done, each of you, independently open your computer, write it out in IRB. Try getting each key out, adding in new ones, and deleting ones just for fun.
3. In your hash:
    * Include one array
    * Include another hash
4. person = {name: 'John', height: '2m', weight: '70kgs'}
    * Add to the hash: John's occupation (web developer) and hobbies (art).
    * Delete John's weight from the hash
    * Retrieve John's height from the hash
    * Iterate through the hash so we see John's details.
Beast
A group of friends have just finished lunch. Write an app to work out how much each person owes.
Parameters: - Your app should ask "Enter a customer's name" - Your first line of code is: items = [{ customer: "John", item: "Soup", cost: 8.50}, {customer: "Sarah", item: "Pasta", cost: 12}, {customer: "John", item: "Coke", cost: 2.50}] - Your app should output, for example: "John owes $11.0"
Extra
1. Format your total so it always shows two decimal places, e.g. $11.00 2. The list of items makes our code messy. Instead, see if you can read the items from a file. (Google will help here!) 3. Allow items to be added to the list. E.g. "Press 1 to add items, press 2 to work out a total". 4. Store these new items to the file. Beast++
Create a ruby application that requests the name of a classmate, and displays their birthday and your birthday. Use at least one Hash and one Array in the solution.
1. Display the number of days between your birthdays. 2. Create a method to display their star sign based on their birthday. 3. Someone's probably already coded this date to star sign functionality - replace your method with a gem

Week 02 Day 01
MORNING CHALLENGE:
1. sit beside someone new, at a new spot :slightly_smiling_face:
2. There is an odd employee at The Company who needs some code written that will provide them with the first 100 numbers of the Fibonacci sequence ….. (no one really knows why the odd employee needs this information - or why they can’t work it out themselves - but Monday mornings can be strange).
CHALLENGES
1. Implement methods that perform all of the basic arithmetic functions.
2. Write function that translates a text to Pig Latin and back. English is translated to Pig Latin by taking the first letter of every word, moving it to the end of the word and adding ‘ay’. “The quick brown fox” becomes “Hetay uickqay rownbay oxfay”.
Beast Mode
1. Implement a function that takes two numbers and an operator, and that uses your methods to perform the relevant operation
2. Implement your own versions of: .filter, .insert, .delete, .pop, .shift
Beast++
Implement a function that takes an operation involving three numbers and two operators. Have the function return the correct answer including the order of operation.

Week 02 Day 02
MORNING CHALLENGE:
The Company originally started in Melbourne with a product list that consisted of the following sku numbers: 

"112334", "276834", "098464", "356498", "065134", "124589", "132548", "102334", "278834", "078464",  "356298", "085134", "134589", "132598", "152334", "876834", "088464", "336498", "005134", "124580",  "132588", "102333", "268834", "098464", "956298", "081134", "134889", "132698"

They then expanded to Brisbane, and while Brisbane began with mostly the same product sku list (some items they stopped stocking because they didn’t sell so well), they also had some extras and ended up with the following list:
"132588", "102333", "268834", "098464", "956698", "081134", "134889", "132698", "112334", "276834", "098464", "356498", "065134", "132548", "102334", "278834", "078464", "356298", "005134", "134589", "132598",  "876834", "088464", "336498", "005134", "124588"

Head office want a complete sku list with no duplicates. 

Easy to do right? Now try working it out with three lines of code, you should be able to do it with 6 words and some operators and syntax.

Teacher notes: there will be 29 products in the final array, and I was expecting students to use .uniq


Week 02 Day 02
MORNING CHALLENGE:
The Company is currently wanting to produce another 500 units of product sku 276834, which is a lamp with a circular base. Unfortunately, a staff member forgot to order the plywood to make the base and didn’t account for the cost of this wood.
Plywood can be purchased in 1200 X 2400 mm sheets at a cost of $28.47 per sheet.
Each lamp base is a circle with a diameter of 320mm. 
What is the total cost of ordering the plywood for the bases, and how much plywood is wasted?

Teacher notes: there needs to be some value that allows for a gap between each of the circles (i.e. you can’t just say area of plywood / area of circle…..). The hope is to give a simple math problem and have students consider real world anomalies that often thwart the best code :) you can end up with optimisation code coming through…

CHALLENGES - for math bases
write a method (without using any inbuilt ruby functions) to take a string in base 3 and convert to a number in decimal
write a method (without using any inbuilt ruby functions) to take a string in base 7 and convert to a decimal
write a method (without using any inbuilt ruby functions) to take a string in binary and convert to a decimal

Beast
write a method (without using any inbuilt ruby functions)  to convert hex to integer
write a method (without using any inbuilt ruby functions)  that takes two parameters, a number and a base and can convert any base 10 number to any other base…. 


Week 02 Day 04
MORNING CHALLENGE:
A slightly different kind of challenge this morning - its ok to leave it and get on with your terminal app if you’d rather.

The Company has broken the keyboard not their one and only laptop, so can’t get this bit of code to run. What would the output of this code be (without running it on your own computer)? 

 def fib(num_
  if num < 2
     num
  else
     fib(num-1) + fib(num-2)
  end
end
puts fib(4)

Week 03 Day 01
Morning challenge was ruby fundamentals #24 (blocks)
Define a Cat/Dog class
1. Each cat/dog should have a name
2. Implement a speak method to say meow/woof.
3. Add each cat/dog’s name to the speak method (Pixie says meow).
4. Give the cat/dog an age
5. We've got name and age, let's give each cat/dog a location too. Test your location works by printing the cat/dog's location.
doggo = Dog.new('Rover', 2, 'Brisbane') puts doggo.location # -> Brisbane (You might get a no method error, remember attr_accessor?)
6. Create a walk method (or similar for a cat). This should say "I have been for X walks.". Every time you call walk, the number should increase by one E.g:
doggo = Dog.new(...) doggo.walk # -> I have been for 1 walks today doggo.walk # -> I have been for 2 walks today
7. Update the walk method so it only increases the walk count. Create a new method to display walks. E.g.: doggo = Dog.new(...)
doggo.walk # -> Shouldn't print anything on screen doggo.walk # -> Shouldn't print anything on screen doggo.display_walks # -> I have been for 2 walks today
8. Update the walk method so you can chain walk commands. E.g.: doggo = Dog.new(...) doggo.walk.walk.display_walks # -> I have been for 2 walks today

Beast Mode
1. Improve the walk method. Accept a location and a distance. e.g. doggo.walk('Brisbane', 20)
2. Update your display_walks method to show all of the walk details.
3. Implement a total_distance method to calculate the total distance of all the walks.
4. Track the time each walk is created. Update display_walks to show it back to your user in a readable format.
5. Research ruby gems. Use a gem to geocode a location and store it's latitude + longitude. E.g. "Brisbane" stores -27.44888,153.00531

Beast++
1. Define a continent class. Give this class a couple of attributes, one of which should be countries. This will be an attribute that is an array of country objects. Define a country class, state, and a city class. Make some objects relating to each class, and assign them to the relevant classes array attribute. Eg, cities would be in an array relating to the ‘cities’ attribute of a state or country object. 
2. Think about then define a bank class. Have the bank perform the typical bank operations and contain the relevant data. Extend this by defining a customer class, and have this class interact with your bank class. 

Week 03 Day 02
Morning challenge
The Company has two directors who are passionately disagreeing, they want to fight it out. Being the fantastic human you are, you propose creating a virtual fight to minimise physical harm.
You need to create a simple fighting game, where two opponents will fight until one of them loses.

Hints: start by creating a Player class (the instance variables could be name, health and power).
You’ll need a few methods, consider one that keeps track of whether a player is alive, another one that calculates the impact of hits (decreases the opponents heath by the the amount of the other players power). And a third that outputs the players information.

You’ll then need to make a fight method that uses a loop to make the players hit one another until  the is alive method returns false for one of them. When the loop is finished (which would mean one of the players has lost), show the players output.

Then create two Player objects (create a random value for each player’s health and power, make is so that the maximum health value for a player is 200, and the maximum power value is 25) and call the fight method.
Challenge
The Company has a new product range, ink and toner cartridges. These products are a little different from what is usually sold, so a new website is needed.
Your boss wants you to build a static website with a home page, a products page and a contact form on a separate page that will help sell the products (therefore it needs to look good).


Week 03 Day 03
Morning challenge
The Company is happy with the ink sales, and wants to collect data on their customers.
They want a ‘sign up’ page that has a form collecting the following information:
- name
- email
- DOB
- gender (with a radio button)
- State (from a drop down menu - so look up the select element)
- a checkbox that says they are happy for you to send them emails about special deals etc
- and a submit button

Week 03 Day 04
Morning challenge (Thursday 8 march 2018)
The Company is happy with the website’s functionality at this point in time, but really wants it to look better. They want you to make the home page with considered font and colour choices, as well as an attractive layout. 

Week 03 Day 05
Morning challenge (Friday 8 march 2018)
The Company directors are interested in tech and met a guy who was really passionate about Flexbox, they now want you to implement Flexbox in the ink website. They want a header across the top, nav down the left hand side, the main content in the middle and an aside down the right hand side with some featured product images.

Week 04 Day 01
Morning challenge (Tuesday 13 march 2018)
The company is pretty disappointed in the lack of responses 

Week 04 Day 02
Morning challenge (Wednesday 14 march 2018)
The Company have decided they don’t like the look and feel of the homepage. Instead of coding another page, you suggest coming up with two different design wireframes in Figma.

Misc - for blocks
Make your own .each method
array = ['cat', 'dog', 'fish']
class Array
    def my_each
        for element in self do
            yield element
        end
    end
end
array.my_each do |item|
    puts item
end
end
puts fib(4)

Week 05 Day 03 (really day 2 because Monday was a public holiday)
- Make a new directory called “practice-portfolio” with a HTML file (copy some code from other projects you have that will display something) and a README.md
- Set up a git repository with the same name and make your first commit.
- Create a new branch that adds a new form feature to your html file, and a CSS file for your stylings. Checkout this branch and ‘ls’ to see the file structure. Checkout your master and do the same. Now change back to the branch and add some styles.
- Commit this to your current branch
- (you need to do this:  git push origin my-new-feature-branch)
- Merge your branch with the master
- Now you want to add a CSS feature but aren’t sure how it will look on the page. Make a new branch and create a small feature to see how this will look. 
- Commit the master, push, and investigate the branches. 
  

Day 3: Week 1, Wednesday
- check which version of ruby you have installed (if it isn’t 2.4.1, then please see a teacher)
- create a ruby folder inside of your apps folder (if you haven’t already done so)
- create a file inside the ruby folder called ‘strings’ with the ruby extension

Day 4: Week 1, Thursday
- create a well named variable that contains a string of  your method of transport to class
- create a well named variable that contains the amount of time it took you to get to class
- create a complete sentence  that lets us know how you got to class and how long it took
- print this complete sentence

you are working at a bar where you have a current backlog of drinks to make:
 3 party parrot cocktails
2 party parrot waters
and
6 party parrot beers

write a program that asks the customer for their order.
if they order a party parrot cocktail, add one to the number of party parrot cocktails you need to make,
if they order a party parrot water, add one to the number of party parrot waters you need to make,
if they order a party parrot beer, add one to the number of party parrot beers you need to pour

print the final drinks order so you know what to make

****
cocktails sell for $22, and cost $8 to make
beer sell for $12, and cost $3 to pour
water sell for $6, and cost $0.15 to make

print out the total profit for the orders you have


DAY 5 :  Week 1, Friday
1. sit beside someone different in a different spot from yesterday
2. A business called “The Company” created a new phone called the companyPhone that needs packing to send away for sale. The Company needs to know how many phones in their pretty new packaging (rectangular prisms) that measures: with  width 5cm, length 8cm, and depth 4cm we can fit into a box that is 32cm wide,  40cm long and 20cm high.   (think about writing some pseudo code first that steps through all the commands you need to write.)

for in the challenges (not a morning challenge)

1. from the command line, create a file called ruby cheat sheet.rb
      list all the key words we covered in class yesterday with a description of what it does (and an   example)
3. talk to the person beside you and compare what you wrote….. share the knowledge and make both of your cheat sheets better.
4. if you didn’t get to do the logical operators from yesterday’s challenges, then go through those  Elementary
1. Write a program that prints ‘Hello World’ to the screen.
2. Write a program that asks the user for their name and greets them with their name.
3. Modify the previous program such that only the users Alice and Bob are greeted with their names.
4. Write a program that asks the user for a number n and prints the sum of the numbers 1 to n
5. Modify the previous program such that only multiples of three or five are considered in the sum, e.g. 3, 5, 6, 9, 10, 12, 15 for n=17
6. Write a program that asks the user for a number n and gives them the possibility to choose between computing the sum and computing the product of 1,…,n.
7. Write a program that prints a multiplication table for numbers up to 12.
8. Write a program that prints all prime numbers. (Note: if your programming language does not support arbitrary size numbers, printing all primes up to the largest number you can easily represent is fine too.)
9. Write a guessing game where the user has to guess a secret number. After every guess the program tells the user whether their number was too large or too small. At the end the number of tries needed should be printed. I counts only as one try if they input the same number multiple times consecutively.
10. Write a program that prints the next 20 leap years.
11. Write a program that computes4\cdot \sum_{k=1}^{10^6} \frac{(-1)^{k+1}}{2k-1} = 4\cdot(1-1/3+1/5-1/7+1/9-1/11\ldots).  
Lists, Strings
If your language of choice doesn’t have a build in list and/or string type (e.g. you use C), these exercises should also be solvable for arrays. However, some solutions are very different between an array-based list (like C++’s vector) and a pointer based list (like C++’s list), at least if you care about the efficiency of your code. So you might want to either find a library, or investigate how to implement your own linked list if your language doesn’t have it.
1. Write a function that returns the largest element in a list.
2. Write function that reverses a list, preferably in place.
3. Write a function that checks whether an element occurs in a list.
4. Write a function that returns the elements on odd positions in a list.
5. Write a function that computes the running total of a list.
6. Write a function that tests whether a string is a palindrome.
7. Write three functions that compute the sum of the numbers in a list: using a for-loop, a while-loop and recursion. (Subject to availability of these constructs in your language of choice.)
8. Write a function on_all that applies a function to every element of a list. Use it to print the first twenty perfect squares (a natural number n  is a perfect square if it can be written as n=m*m  for some other natural number m . 1,4,9,16,25  are the first 5).
9. Write a function that concatenates two lists. [a,b,c], [1,2,3] → [a,b,c,1,2,3]
10. Write a function that combines two lists by alternatingly taking elements, e.g. [a,b,c], [1,2,3] → [a,1,b,2,c,3].
11. Write a function that merges two sorted lists into a new sorted list. [1,4,6],[2,3,5] → [1,2,3,4,5,6]. You can do this quicker than concatenating them followed by a sort.
12. Write a function that rotates a list by k elements. For example [1,2,3,4,5,6] rotated by two becomes [3,4,5,6,1,2]. Try solving this without creating a copy of the list. How many swap or move operations do you need?
13. Write a function that computes the list of the first 100 Fibonacci numbers.
14. Write a function that takes a number and returns a list of its digits.
15. Write functions that add, subtract, and multiply two numbers in their digit-list representation (and return a new digit list). If you’re ambitious you can implement Karatsuba multiplication. Try different bases. What is the best base if you care about speed? If you couldn’t completely solve the prime number exercise above due to the lack of large numbers in your language, you can now use your own library for this task.
16. Write a function that takes a list of numbers, a starting base b1 and a target base b2 and interprets the list as a number in base b1 and converts it into a number in base b2 (in the form of a list-of-digits).
17. Implement the following sorting algorithms: Selection sort, Insertion sort, Merge sort, Quick sort, Stooge Sort. Check Wikipedia for descriptions.
18. Implement binary search.
19. Write a function that takes a list of strings an prints them, one per line, in a rectangular frame. For example the list ["Hello", "World", "in", "a", "frame"] gets printed as: *********
20. * Hello *
21. * World *
22. * in    *
23. * a     *
24. * frame *
25. ********* 
26. Write function that translates a text to Pig Latin and back. English is translated to Pig Latin by taking the first letter of every word, moving it to the end of the word and adding ‘ay’. “The quick brown fox” becomes “Hetay uickqay rownbay oxfay”. 
Intermediate
1. Write a program that outputs all possibilities to put + or - or nothing between the numbers 1,2,…,9 (in this order) such that the result is 100. For example 1 + 2 + 3 - 4 + 5 + 6 + 78 + 9 = 100.
2. Write a program that takes the duration of a year (in fractional days) for an imaginary planet as an input and produces a leap-year rule that minimizes the difference to the planet’s solar year.
3. Implement a data structure for graphs that allows modification (insertion, deletion). It should be possible to store values at edges and nodes. It might be easiest to use a dictionary of (node, edgelist) to do this.
4. Write a function that generates a DOT representation of a graph.
5. Write a program that automatically generates essays for you.
    1. Using a sample text, create a directed (multi-)graph where the words of a text are nodes and there is a directed edge between u and v if u is followed by v in your sample text. Multiple occurrences lead to multiple edges.
    2. Do a random walk on this graph: Starting from an arbitrary node choose a random successor. If no successor exists, choose another random node.
6. Write a program that automatically converts English text to Morse code and vice versa.
7. Write a program that finds the longest palindromic substring of a given string. Try to be as efficient as possible!
8. Think of a good interface for a list. What operations do you typically need? You might want to investigate the list interface in your language and in some other popular languages for inspiration.
9. Implement your list interface using a fixed chunk of memory, say an array of size 100. If the user wants to add more stuff to your list than fits in your memory you should produce some kind of error, for example you can throw an exception if your language supports that.
10. Improve your previous implementation such that an arbitrary number of elements can be stored in your list. You can for example allocate bigger and bigger chunks of memory as your list grows, copy the old elements over and release the old storage. You should probably also release this memory eventually if your list shrinks enough not to need it anymore. Think about how much bigger the new chunk of memory should be so that your performance won’t be killed by allocations. Increasing the size by 1 element for example is a bad idea.
11. If you chose your growth right in the previous problem, you typically won’t allocate very often. However, adding to a big list sometimes consumes considerable time. That might be problematic in some applications. Instead try allocating new chunks of memory for new items. So when your list is full and the user wants to add something, allocate a new chunk of 100 elements instead of copying all elements over to a new large chunk. Think about where to do the book-keeping about which chunks you have. Different book keeping strategies can quite dramatically change the performance characteristics of your list.
12. Implement a binary heap. Once using a list as the base data structure and once by implementing a pointer-linked binary tree. Use it for implementing heap-sort.
13. Implement an unbalanced binary search tree.
14. Implement a balanced binary search tree of your choice. I like (a,b)-trees best.
15. Compare the performance of insertion, deletion and search on your unbalanced search tree with your balanced search tree and a sorted list. Think about good input sequences. If you implemented an (a,b)-tree, think about good values of a and b.
Advanced
1. Given two strings, write a program that efficiently finds the longest common subsequence.
2. Given an array with numbers, write a program that efficiently answers queries of the form: “Which is the nearest larger value for the number at position i?”, where distance is the difference in array indices. For example in the array [1,4,3,2,5,7], the nearest larger value for 4 is 5. After linear time preprocessing you should be able to answer queries in constant time.
3. Given two strings, write a program that outputs the shortest sequence of character insertions and deletions that turn one string into the other.
4. Write a function that multiplies two matrices together. Make it as efficient as you can and compare the performance to a polished linear algebra library for your language. You might want to read about Strassen’s algorithm and the effects CPU caches have. Try out different matrix layouts and see what happens.
5. Implement a van Emde Boas tree. Compare it with your previous search tree implementations.
6. Given a set of d-dimensional rectangular boxes, write a program that computes the volume of their union. Start with 2D and work your way up.
GUI
* Write a program that displays a bouncing ball.
* Write a Memory game.
* Write a Tetris clone
Open Ended
1. Write a program that plays Hangman as good as possible. For example you can use a large dictionary like thisand select the letter that excludes most words that are still possible solutions. Try to make the program as efficient as possible, i.e. don’t scan the whole dictionary in every turn.
2. Write a program that plays Rock, Paper, Scissors better than random against a human. Try to exploit that humans are very bad at generating random numbers.
3. Write a program that plays Battle Ship against human opponents. It takes coordinates as input and outputs whether that was a hit or not and its own shot’s coordinates.


TERM 2 MORNING CHALLENGES

#MONDAY
# Interview style question prep: Don't Google (yeah, I said it).
# Whiteboard first. You don't need to know perfect syntax.
# Having a rough idea on how to approach the problem is just
# as good in an interview.
#
# Exes and Ohs
#
# Check to see if a string has the same amount
# of 'x's and 'o's. The method must return a boolean
# and be case insensitive.
#
# Examples:
# ExesAndOhs("ooxx") => true
# ExesAndOhs("xooxx") => false
# ExesAndOhs("sxoowxxoq") => true
# ExesAndOhs("oOxXxoXo") => true
# ExesAndOhs("oOxXxoX") => false
# ExesAndOhs("zpzpzpp") => true
#
# Check your answers by running the tests:
# ruby tests/15_exes_and_ohs_test.rb
#

def exes_and_ohs(string)
  # yo' co' here
end

#TUESDAY
It turns out that one of the directors of The Company is overly patriotic…. they want you to create an InstaRails that only features pictures of kiwis :kiwifruit:
The app needs to include a nav bar with a login, logout, signup and display of the users email address the logged in with (just like yesterday). 
It should also have rspec installed.
Create at least three users and have at least 15 photos.
And the home page should show 12 photos.

#WEDNESDAY - CSS THROW BACK

1. Positioning and layout: if you give a negative value to “top” property, in which direction with the box be moved.

    2. when the ‘float’ property is used with the values of ‘left’ or ‘right’, anything else that lives in the containing element will: a) become invisible b) be moved down from the element associated with the ‘float’ property c) flow around the element associated with the ‘float’ property
    3. when the text needs more space that the dimensions of the box it is contained in, the browser shows scrolls for the overflow property with the values of “scroll” and:………
    4. assign width of 500px to the “text” element and enable fixed scrollbars: #text { overflow: ……..; height: 200px; width:……;}
    5. Fill in the blanks and make the blue box disappear from the webpage: #red{……..: absolute; top: 100px; left: 100px, z-index: 20;} #blue{position: relative; z-index: 50; display:…….;}
answers
1. up
2. c 
3. auto
4. “scroll”, 500px

#THURSDAY - RUBY CONTROL FLOW THROW BACK
1. what is the result of (a&&b) || b, when a = true and b = false?
2. fill in the blanks to create a valid if/else statement. 
    1. status = 1
    2. ……. status ==1
    3. puts “Online”
    4. else
    5. puts “Offline”
    6. ………
3. how many numbers are there in the range (6..9)?
4. how many lines of code will the following code output?
    1. a=2
    2. loop do
    3. puts a
    4. a + 3
    5. break if a > 8
    6. end
5. fill in the blanks to create a valid case statement.
    1. temp = 5
    2. ….. temp
    3. when 0…19
    4. puts “low”
    5. …. 19…40
    6. puts “OK”
    7. else
    8. puts “wow”
    9. …..
6. what is the output of this code?
    1. x=0
    2. for i in 2…4
    3. x+=1
    4. end
    5. puts x


answers
1. false
2. if, end
3. 4
4. 3
5. case, when, end
6. 5

# FRIDAY MORNING CHALLENGE
The Company has purchased a small movie theatre and are currently showing https://www.youtube.com/watch?v=dtwpjnuaVTE Ready Player One. They are having trouble with their ticketing system and want you to write a program that won’t allow anyone under the age of 12 to buy a ticket, but will allow someone under the age of 15 (but over the age of 12) buy a child priced ticket ($10) and everyone else needs to buy a full priced adult ticket ($18). Management are yet to decide if they will offer a student priced ticket, but were thinking that if they did, it would be around $12. The end of the code should tell the customer what their ticket cost is.
Make sure to check your code works when people enter the ages of 12 and 15.


     1 puts "Enter the customer's age: "
     2 # Get an integer age value from the user
     3 age = gets.to_i
     4
     5 # Determine the cost based on age
     6 if (age < 12)
     7 puts “you are too young for this movie”
     8 elsif (age < 15)
     7 cost = 10
     8 elsif (age > 15)
     9 cost = 18
        else
        puts “please enter a real age: “
    10 end
    11
    12 # Print out the final cost
    13 puts "Ticket cost: " + cost.to_s

#Monday week 2 morning Challenge
The Company has come across a group of skilled coders and wants to make them work hard to make CompanyGram, a clone of Instagram.  The directors can get a bit distracted at times, and need help identifying the concerns and ethical issues that may arise from creating such an application. They are also open to suggestions / recommendations that would make the application better.





TERM 3 MORNING CHALLENGES  Week two:

HELLO REACT

Make a react app that takes the input from the text input field and outputs your input in realtime to the screen.  The input should be your name, and the output should say ‘Hello, your name’. Like the image.  
￼

PILL BOTTLES	
The company is selling vitamins (because everyone around seems to be getting sick), but there seems to be a quality assurance issue. 
They have 10 identical bottles of identical pills (each bottle contain hundred of pills). 
Out of 10 bottles 9 have pills that weigh 1 gram but 1 bottle has pills of weight of 1.1 gram. 
Given a measurement scale, how would you find the heavy bottle? 
You can use the scale only once.
Answer: 
First, arrange the bottles on shelf and now take, 1 pill from the first bottle, 2 pills from the second bottle, 3 pills from the third bottle, and so on. Ideally you would have (10)*(11)/2=55 pills weighing 55 grams, when you put the entire pile of pills on the weighing scale.The deviation from 55 g would tell you which bottle contains the heavy pills.
If it is .1 gram more, it is 1st bottle which has heavy pill, if it is .2 more, gram 2nd bottle has heavy pills, if it is .3 more, gram 3rd bottle has heavy pills.  https://daveceddia.com/react-practice-projects/

https://medium.com/@samerbuna/react-js-frequently-faced-problems-45e7060ef884


WEATHER APP

Display a 5-day weather forecast, where each day shows the high and low temperatures, and an image for sunny/rainy/cloudy/snowy. Use fake, hard-coded data until you’ve got everything rendering correctly.
￼

You might notice that the “days” look a lot like the cards from yesterday’s challenge
For added practice:
* Add the ability to click on a day, and see its hourly forecast. You can just maintain the current view in the top-level App state.
* Add React Router to the project (npm install react-router) and follow the quick start guide here to add routes, such that / shows the 5-day forecast, and /[name-of-day] shows the hourly forecast for a particular day.
* Sign up for a free API key from Open Weather Map, fetch a real 5-day forecast, and feed that data into your app.
* Want to get really fancy? Add a graphics library  to render a graph of the temperature over the course of a week or day.
* concentrate on the aspects you are looking to brush up on
* if you don’t want to do a weather api, you are free to use another one you prefer.  MusicPlayer
The Company needs music for in their office. Use the Spotify api to create an application that lets you discover music. It will help you find top songs, trending artists, and explore new genres. If you want to get really advanced, how about a music suggestion feature?
* https://developer.spotify.com/documentation/web-api/  
