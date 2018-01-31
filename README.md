# e-Journal

This repository is meant to be a boilerplate to create a file system that helps people to complete online courses.

e-Journal is a system inspired by [Bullet Journal](http://bulletjournal.com/) which can be used with any project file system, but also by using a notebook or blank sheets.

## Recommended steps:

### Course:

1. Write down the whole structure of the course in INDEX.MD (no descriptions needed at this point). There are three levels: Course > Lesson > Activity. Create all the needed directories and files and link them in the INDEX.md file properly.

2. Once you have the course structure clear, follow the STATS guidelines.

  - Each activity must have as much 0's as exercises, resources to read or watch. Every time you finish an exercise or resource, replace the 0 with an X.
  - Each lesson must have as much 0's as activities. Every time you finish an activity (no activity 0's left!) replace a 0 with an X.
  - Each course must have as much 0's as lessons. Every time you finish a lesson (no lesson 0's left!) replace a 0 with an X.

This is very helpful to visualize your progress and encourage yourself to complete all the progress bars.

3. Everytime you finish an exercise, a lesson, or an activity, write it in the CALENDAR.md using the following syntax:

```
## DD/MM/YYYY

* I've finished lesson 1.
* I've finished the exercise "Exercise Title".
```

### Lesson:

1. In the RESOURCES.md file, keep a list with all the links you've used. Rank them with stars (`*`) from 1 to 5, where 5 is the maximum positive score you can give to rank this resource.

```
# Resources

- https://examplelink.com/asdfy *
- https://examplelink.com/jklnfdsa *****
- https://examplelink.com/qwersdf **
```


### Activity:

1. Note all useful concepts you learn in CONCEPTS.md

```
# Concepts

## Concept 1

Concept description
```

2. In the EXERCISES.md file, write down all the different exercises. Remember to keep them as small and concise as possible. This file is optional, only needed if the activity has any exercise.

```
## Exercise Name

**Exercise statement**

Exercise...
```

3. In the RESULTS.md file, write down all the attempt results of the activity chronologically. If the exercise consist in a test exam, try to add your answers and the correct / wrong answers too for every attempt.

```
## Result


### DD/MM/YYYY
1. Question

Answer
```
