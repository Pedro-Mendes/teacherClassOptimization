# Optimization for assigning teachers to classes

## Problem description

Given the following input:
* Number of teachers per subject
* Number of assistants per subject
* Availability of teachers
* Availability of assistants

I want to output the best solution which allocates the teachers in a more equally distributed week without overloading a volunteer (teacher). Actually the initial objective is to automatize this allocation process and then optimize it.


## Restrictions

* 4 days a week
* Each day a different subject (chemistry, physics, mathematics and portuguese)
* Minimum of one assistant per class
* There are 2 classes at the same time
* A day of class A can have a different subject than class B (e.g. class A on thursday: Portuguese, class B on thursday: Chemistry)
* It is possible that someone doesn't get a class
* A class is composed by 2 teachers plus assistants
* Assistants should be equally distributed in the classes
* Each person selected will work at least once a week
* Also note that the availability of the teachers and assistants will define the subject taught that specific day

## Extra information

* The classes are given from 19h15 through 20h30 and 21h through 22h30
* The classes are given from monday through thursday
* The classes are divided between theory and exercises classes
* The theory classes don't need assistants

## Example

* Work in progress...