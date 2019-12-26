# 100 Days Of Code - Log

### Day : January 30, 2020

**Today's Progress**: 

**Thoughts:** 

**Link(s) to work**
[Example](http://www.example.com)


### Day 1: December, 22, 2019 - Sunday

**Today's Progress**: I've gone through a MOOC about Python Classes using getter and setter with property.
I learned 3 special methods to implement in a class to use fancy ability of python. The `__len__(self)` to be able to do `len(instance)`, the `__contains__(self, item)` to use `item in instance` and the `__str__(self)` to use `print(instance)`
I also did a list challenge on HackerRank website

**Thoughts** I'm amazed to see how better the getter and setter concept is implemented in Python than C++ for example. I'm starting to understand more and find it more easily to use the concept of Classes.

**Link(s) to work**
1. [Fun MOOC about Python](https://www.fun-mooc.fr/courses/course-v1:UCA+107001+session02/courseware/39f73ecca8274b48b5edc06d00ab259c/3495acace4304b78b11ed18a2641367f)
1. [List challenge in HackerRank](https://www.hackerrank.com/challenges/python-lists)


### Day 2: December, 23, 2019 - Monday

**Today's Progress**: Following my classes learning, I discovered that `__eq__(self, other)` and `__hash__(self)`are usefull if you want to control the p == q test between your instances and the way your object is stored as a key in a dictionnary. I went through the Learn Python: Classes section in CodeAcademy.
A list of all the [special method names](https://docs.python.org/3/reference/datamodel.html#specialnames)

**Thoughts** I like to see how easy it is to handle those very usefull mechanism.

**Link(s) to work**
1. [Fun MOOC about Python](https://www.fun-mooc.fr/courses/course-v1:UCA+107001+session02/courseware/39f73ecca8274b48b5edc06d00ab259c/3495acace4304b78b11ed18a2641367f)
2. [CodeAcademy](https://www.codecademy.com/courses/learn-python-3/lessons/data-types/exercises/object-oriented-programming)


### Day 3: December 24, 2019 - Tuesday

**Today's Progress**: I continue with my classes tutorial. I've been practicing class inheritance and the concept of implicit, explicit and redefined method. Using a [namedtuple](https://docs.python.org/3/library/collections.html#collections.namedtuple) (a function that returns a class) or a @dataclass (frozen=True) you can easily create an immutable class.

**Thoughts:** A concept that took me long time to understand with C++ seems much more easier, and I quickly see how I could use all of this !

**Link to work:** 
1. [Fun MOOC about Python](https://www.fun-mooc.fr/courses/course-v1:UCA+107001+session02/courseware/39f73ecca8274b48b5edc06d00ab259c/3495acace4304b78b11ed18a2641367f)


### Day 4: December 25, 2019

**Today's Progress**: Training about multiple class inheritance, if you do class C(SuperA, SuperB) it will first look attributs in C, then SuperA then SuperB. You can find the order by calling the C.mro() method !

**Thoughts:** I'm happy to see I can commit even on christmas day !


### Day 5: December 26, 2019

**Today's Progress**: I did some exercise with multiple class inheritance. I also did my Pre Assessment test for the deeplearning nanodegres MOOC. Result are : Differential Calculus = 50% / Linear Algebra = 42% / Python = 72% / Algebra = 83%. They said that I am **modederately prepared** ahah. I will need to do more mathematics to follow up.
The scope resolution LEGB rule is important to know:
* Local(L): Defined inside function/class
* Enclosed(E): Defined inside enclosing functions(Nested function concept)
* Global(G): Defined at the uppermost level
* Built-in(B): Reserved names in Python builtin modules

This creates a special case to be aware of :
```
a = 1
class C:
  a = 3
  def f(self):
    print(a)
 ins = C()
 ins.f()
 ```
 
Following the LEGB rule, there are no local `a` variable in the function f, there are no enclosed function, and yes, there is a global variable called a. In this scenario the print(a) will print 1. the bloc a=3 in the class will be skipped. To avoid it and print 3 you must write print(self.a)

**Thoughts:** Not much today, I feel that a lot of work is coming on, this journey. Still 1000% motivated :)

**Link(s) to work**
[FunMOOC about Python](https://www.fun-mooc.fr/courses/course-v1:UCA+107001+session02/courseware/39f73ecca8274b48b5edc06d00ab259c/b07471402fd84892917c2b207a395b99/)
[DeepLearning Nanodegree](https://www.udacity.com/course/deep-learning-nanodegree--nd101)
