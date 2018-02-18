# e-Journal

This repository is meant to be a boilerplate to create a file system that helps people to complete online courses.

e-Journal is a system inspired by [Bullet Journal](http://bulletjournal.com/) which can be used with any project file system, but also by using a notebook or blank sheets.

## Recommended steps:

### Course:

#### Index

1. Write down the whole structure of the course in INDEX.md (no descriptions needed at this point). There are three levels: Course > Lesson > Activity | Attachment | Concept | Exercise . Write only to LESSON level. Each lesson has its own INDEX.md file.

2. Once you have the course structure clear, follow the STATS guidelines.

```md
### Stats

#### Legend
* 0: Not Completed
* 1: Completed

---

COURSE 0000

LESSON 1 X00
ACTIVITY 1 X
ACTIVITY 2 0
ACTIVITY 3 0

LESSON 2 0000
...
LESSON n 00000
```

- Each activity must have as much 0's as exercises, resources to read or watch. Every time you finish an exercise or resource, replace the 0 with an X.
- Each lesson must have as much 0's as activities. Every time you finish an activity (no activity 0's left!) replace a 0 with an X.
- Each course must have as much 0's as lessons. Every time you finish a lesson (no lesson 0's left!) replace a 0 with an X.

This is very helpful to visualize your progress and encourage yourself to complete all the progress bars.

**Note**: 0's and 1's are the default option. You can change the legends and, instead of using 0's and 1's, you can use, for instance, emoji.

### Calendar:

Everytime you finish an exercise, a lesson, an activity... write it down in the CALENDAR.md file using the following format:

```md
## DD/MM/YYYY

* I've finished lesson 1.
* I've finished the exercise "Exercise Title".
```

You can use this calendar as a TODO list with deadlines, but I do prefer to use it as a tracker of things I have already accomplished. **I prefer seing this done rather than things that are still to be done.**

### Lesson:

#### Index:
*Mandatory*

Keep an index of all the content of the lesson.

```md
# Lesson 1: Lesson Name

* 📝 [Activities](./LESSONS/LESSON_1/ACTIVITIES)
  * [Activity Name](./LESSONS/LESSON_1/1_Activity_Name.md)

* 📎 [Attachments](./LESSONS/LESSON_1/ACTIVITIES)

* 🧠 [Concepts](./LESSONS/LESSON_1/CONCEPTS)
  * [Concept Name](./LESSONS/LESSON_1/1_Concept_Name.md)

* ✏️ [Exercises](./LESSONS/LESSON_1/EXERCISES)
  * [Exercise Name](./LESSONS/LESSON_1/1_Exercise_Name.md)

* 📌 [Notes](./LESSONS/LESSON_2/NOTES.md)
* 🔗 [Resources](./LESSONS/LESSON_1/RESOURCES.md)
```

### Activity:
*Not Mandatory*

**Note** Activity directories are **optional**. You can track quizzes, tests and other exercises in the EXERCISES.md file under the LESSON directory. The idea of Activities is to help you with tests and exams you can repeat several times, so you can save and track your errors and learn from them.

1. In the RESULTS.md file [optional], write down all the attempt results of the activity chronologically. If the exercise consist in a test exam, try to add your answers and the correct / wrong answers too for every attempt.

```md
# Result

## DD/MM/YYYY
1. Question

Answer
```

### Attachments:
*Not Mandatory*

### Concepts:
*Mandatory*

Save all useful concepts you learn in CONCEPTS directory.

Each filename should have the following format:

`n_NameOfTheConcept.md`

Where `n` is the concept's index.

### Exercises:
*Not Mandatory*

In the EXERCISES directory, keep the different exercises. Remember to keep them as small and concise as possible. This file is optional, only needed if the activity has any exercise or if you want to put in practice a concept you have learned.


Each filename should have the following format:

`n_NameOfTheExercise.md`

Where `n` is the exercise's index.

### Notes:
*Not mandatory*

### Resources:
*Not mandatory*

In the RESOURCES.md file, keep a list with all the links you've used.
* Optionally, rank them with stars (`*`) from 1 to 5, where 5 is the maximum positive score you can give to rank this resource (remember you can use another character on an emoji).
* Optionally, add a short description of the resource.

```md
# Resources

* [Resource Name](https://examplelink.com/asdfy) *
* [Resource Name](https://examplelink.com/jklnfdsa) *****
  * Resource Description.
* [Resource Name](https://examplelink.com/qwersdf) **
```

## Examples

* [e-Journal: Introduction to Artificial Intelligence, by Udacity](https://github.com/elenatorro/e-journal_Intro-to-artificial-intelligence/blob/master/COURSE/INDEX.md) *not finished*
