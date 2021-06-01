## Assignment

Build a RESTful web API to manage _"Lessons"_ and _"Channels"_. A _Channel_ is a group chat channel that brings together an instructor and a group

A Lesson has: 

- a unique `id`
- a `name`


A Channel has: 

-a unique `id`
-a `name`
-a `lessonId` that connects it to the corresponding Lesson
-a `cohort`.


### Features

The Web API must provide a set of `endpoints` to fulfill the following needs:

- add a new Lesson.
- view list of existing Lessons.
- view details of a single Lesson.
- update the information of an existing Lesson.
- remove a Lesson from
- add a channel