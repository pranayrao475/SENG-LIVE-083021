# Object Orientation in Ruby pt. 1

#### Lecture Objectives

- Demonstrate the power of OO in Ruby
- Demonstrate the essential steps to implementing OO in Ruby

### Lecture Deliverables

- Create and encapsulate logic for a donation class/instance

### Lecture Take aways 

- Classes
- Instances
- Initialize
- Instance Variables
- Instance Methods
- Setter & Getters
- Attribute Accessors
- Self

### Object-Orientation

- In the 1970's, Adele Goldberg (Links to an external site.) and Alan Kay (Links to an external site.) developed an object-oriented language at Xerox PARC called SmallTalk, which was used in the first personal computer.
- In Ruby, (almost) everything is an object. Every bit of information and code can be given their own properties and actions(aka methods).
- Ruby comes with a few types of Objects to get us started, things like:
 - [Integer](https://ruby-doc.org/core-2.5.0/Integer.html)
 - [String](https://ruby-doc.org/core-3.0.2/String.html)
 - [Array](https://ruby-doc.org/core-2.7.0/Array.html)

 - What is an object? An object is a combo of data and behaviors 

 ### Making Objects

 #### Classes
 
 - Outside of using prebuilt Ruby objects such as the ones listed above, we can also create our own custom ones.
 - To do so, we start by building a class. 
 - What is a class? A class is a blueprint that defines the way that each of its products will behave as well as what data will it contain
 
 Let's create a class for donations:

```ruby
class Donation

end 
```

- What can be done with a class? We can add methods that belong to each instance of the class, methods that belong to the class as a whole as well as data that belongs to each instance or the class as a whole. 

#### Instances 

- Once a class has been defined, we can now produce new objects (instances) from this class. 
- To create a new `instance`, `.new` will be called on the class itself 

```ruby
new_donation = Donation.new
```