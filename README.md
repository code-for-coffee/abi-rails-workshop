![ABI Local Chicago](https://local.anitaborg.org/wp-content/uploads/2016/03/21792173979-18842594.png)

Repository for Anita Borg Institute's Learn a Language series: Intro to Rails
_Saturday, June 18, 2016 from 9:30 AM to 1:30 PM (CDT)_


---

# Introduction to Ruby

### James Traver
Full Stack Web & Android Engineer @ GA Chicago

---

## Agenda
#### Part One: Ruby

* Overview
*	Icebreaker
* Everything is an Object
*	Intro to Ruby
* Variables
* Conditional Logic
* Conclusion

---

## Overview

Hi there! You're about to learn Ruby and Ruby on Rails. This workshop is broken up into a two parts: Ruby and Rails. We'll talk more about that soon.

---

## Community-driven

* The developer community is very small. Everyone seems to know everyone.
* We should strive to help others and support one another.
* Support each other; everyone will have different problems.
* Let me explain "I do, we do, you do"

---

## Everything installed?

* You should have installed Rails using **RailsInstaller.org**
* Windows users: look for **Ruby Command Prompt**
* Mac and Linux users: open your **terminal**
* Everyone, type in **irb**
* You should be given a new prompt
* Type in **exit** and then hit enter.

---

## Icebreaker

Turn and talk to the person next to you. Introduce yourself!

Trade **five** facts between each other!

Once you've done that, you will assign each other a spirit animal!

---

## Everything is an Object

* I am an Object
* I have attributes, such as my name and my age
* I have abilities, such as the ability to speak and the ability to jump

---

## Seriously, everything is an object

* Your laptop is an object.
* It has attributes, like the count of RAM and the size of your hard drive
* It has abilities, such as the ability to power on and to shut down

---

## Bicycles are objects

* Have you seen/used a Divvy bike?
* They are objects!
* They have attributes such as their wheel count and their colour
* They have abilities, such as the ability to accelerate and to brake

---

## Let's try something

* Open up an app on your phone that can share things.
* Find the *button* that does it
* Click it.

---

## Turn and talk

* That _button_ on your phone is an **object**
* It has attributes
* It has abilities
* Turn and talk to the person next to you to describe these attributes
* Take 2 minutes to do this

---

## Everything is an Object

* Everything is an object.
* In programming, we **model** things such as _Products_, _Users_, _Status Updates_, _Photos to share_, and countless other things.
* These _models_ have their own attributes and abilities
* In Ruby programming, everything is an object.

---

## Introduction to Ruby

1. What is Ruby?
2. What is Rails?
3. How to think like a programmer

---

## Ruby
### A programming language

*	An open source programming language
*	Easy to read and natural to write
*	Created by Yukihiro Matsumoto (aka Matz) with the goal of building a language FOR developers
*	Regularly maintained and evolving

---

## Rails
### A web application framework

*	Open source web application framework that is built in Ruby
*	Allows you to create web applications that query a database.
*	Created by DHH (David Heinemer Hansson) to simplify the task of building web applications, with the help of _conventions_



---


## Ruby and Rails
### Ruby first

*	It will be easier to navigate a Rails project once we have a basic understanding of Ruby.
*	We will first teach you how to write simple Ruby scripts
*	Once we have become familiarized with Ruby, we will build a Rails applications
* Rails is essentially a group of Ruby script files that work together to help you easily create web applications

---

## Computational Thinking
### What does it mean to program?

"Learning about “for” loops is not learning to program, any more than learning about pencils is learning to draw."

 –Bret Victor, Learnable Programming

---

## Programming
### Its about changing how you think

* Learning how to program is similar to learning french or mandarin
* You have to stumble a lot and make mistakes before you can speak it
* It is okay to get things wrong on the first few tries; **developers are paid to read error messages and then fix them**
* We're really detectives that have to solve problems
* As a developer, you'll think in logical steps to solve a problem

---

## Programming Fundamentals

* In order to start writing our own Ruby programs, we need to learn some of the basic fundamental tools
* Specifically, we need to learn:
	* Variables
	* Conditions
* We will first learn the basics on their own, and then try to apply our skills in a simple interactive Ruby script

---

## Learning Languages

* Do you speak multiple languages?
* I speak enough french to sort of maybe get by in Montreal
* In french, I can say _I am sleepy_
* It looks like _je suis endormie_
* In Ruby, I can do the same
* `i_am = 'sleepy'`
* Ruby is just another language (but written for computers)


---

## Let's learn to talk to Ruby

* If you've installed Rails, you will have an application called **IRB** installed
* You can speak Ruby to your computer here
* It will then reply or look at you funny
* This is what is called a **REPL**
* This tools _reads_ and then _executes_ your code
* It _prints_ your reply & then it _loops back_ to allow more input
* IRB is a REPL for Ruby

---

## Variables

1. Describe how the computer stores data as **variables**
2. Perform mathematical operations using **Numbers**
3. Store words and texts as **Strings**
4. Identify things as true or false using **Booleans**

---

## Saving Values
### Using Variables

* We can tell our program to remember values for us to use later on
* The action of saving a value to memory is called **assignment**
* The entity we use to store the value is called a **variable**
* The action of getting the value from a variable is called **accessing** the variable
* We will use all the above techniques to store values into variables, and generate new values using existing variables

---

## Let's see what Ruby variables look like


---


## Variables
### Storing Values


```ruby
name = "James"
=> "James"
age = 2016 - 1984
=> age # 32
```
---

## Data Types

* The types of different values we support include numbers, text, and other more complex ones we'll see in the future
* Before we dive into what these are, let's just see what they look like

```ruby
1						#Fixnum
1.99					#Float
'Hi! String here!' 		#String
"I'm a string too"		#String
```

---

## Common Data Types

* Ruby likes to store text as these things called **Strings**
* Ruby stores integers as **Fixnums**
* It stores values with decimals as **Floats**
* You can define something as true or false using a **Boolean**

---

## String

* Text values only
* Wrapped around in quotes
* `"looks like this"`
* `'but it can also use single quotes'`
* `current_location = 'aeon center @ thoughtworks'`

---

## Fixnums

* Integers, Whole Numbers, or Real Numbers
* No decimals allowed
* The answer to life, the universe and everything is a Fixnuym
* It is `42`
* `current_year = 2016`


---

## Floats

* Decimals club
* Pi, prices, anything with a **.**
* `19.99` is a common price
* `pi = 3.14`

---

## Fixnums vs Floats

* How does Ruby know which type is which?
* Ruby interprets your number and assigns the proper type
* This is awesome, right?

---

## Boolean


* Booleans represent **truth** and **false**
* We can state that I am not an alien; that is `false`
* We can state that I am a human; that is `true`
* `are_you_an_alien = false`
* ...maybe
* When variables are compared to each other, the result of that comparison is a boolean result (e.g. `5 < 7 => true`)

---

## Turn and Talk

* Take 60 seconds to turn and talk to the person next to you
* Identify a String, Fixnum, Float, and Boolean to each other

---

## Stop & Watch

* We're about to start our first **I do, we do, you do**
* I'm going to demonstrate how to use a few variables
* Make sure you're watching along
* Once I finish, we're going to try to solve a problem together
* After that, you'll work on a challenge yourself!

---

## Stop & Watch

Let's learn how to assign and access simple number and string variables

---

## Together

* Let's figure out how many people are here in this are wearing blue
* How many people do we have?
* Who is wearing green? How many people total?
* Let's assign a value to a variable named `blue_total` using some math

---

## Your challenge: Variables

* Create a **String** called `my_name` and _assign it_ your name
* Create a **Fixnum** caleld `my_birth_year` and _assign it_ the year you were born
* Create a **Fixnum** called `my_age` and _assign it_ your age by subtracting `my_birth_year` from the current year
* Take 5 minutes to complete this!
* If you're done, help others around you!


---


## Conditional Logic

We all have to make decisions.
---
## If I am sick, I need to go to the doctor.

---

## If I am on fire, I need to stop, drop, and roll.

---

## If they are under 21, do not serve them alcohol.
## Else, they can buy alcohol if they want.

---

## If you are tired, go to drink coffee.
## Else, you will drink water.

---

## Conditional Logic

Let's take a look at how we will make decisions with Ruby!

---

## Conditional Logic
### Decision Time

It's either TRUE or FALSE (like booleans)

If you are greater than 18
you are an adult

```ruby
if age > 18
	puts "You are an adult"
end
```

---

## If something doesn't match....


```ruby
guess = 7
if guess == 5
	puts "yes! you got it!"
else
	puts "sorry, you were wrong"
end
```

---

## Conditional Logic
### Multiple Conditions

```ruby
guess = 7
if guess > 5
	puts "Too high!"
elsif guess < 5
	puts "Too Low!"
else
	puts "You've guessed my hidden digit!"
end
```

---

## Stop & Watch

* We're about to start our first **I do, we do, you do**
* I'm going to demonstrate how to write a few conditional statements
* Make sure you're watching along
* Once I finish, we're going to try to solve a problem together
* After that, you'll work on a challenge yourself!

---

## Stop & Watch

Let's learn how to write conditional statements!

---

## Together

* If Chicago is sunny
* Everyone is outside
* Else if Chicago is snowy
* Everyone is grumpy
* Else
* The weather here is unpredictable

---

## Your challenge: Conditional Logic

* Create a **Fixnum** called `my_age` and _assign it_ your age by subtracting `my_birth_year` from the current year
* Create a variable called `age_you_can_drink_at` and _assign it_ to the legal age to buy alcohol
* If `my_age` is greater than or equal to `age_you_can_drink_at`
* `puts 'What are you having?'`
* Else `puts 'Get out of here!'`
* Take 5 minutes to complete this!
* If you're done, help others around you!


---


## Recap

* Data Types
* Conditional logic

---


## Break

