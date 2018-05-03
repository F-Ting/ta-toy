# ta-toy
Toy application to learn how to use Vue.js

## Task

Working together, you will create a one-page Vue.js app that acts like an oversimplified
TA feedback application. The app's default page wills show a list of classes. Upon clicking a class,
a list of TAs for that class will be displayed. Upon clicking a TA, a list of tutorial/lecture sections
assigned to that TA will be displayed. In all, there are four views:

1. A parent view which provides consistent navigation for the child views.
2. A view that allows the user to select a course.
3. A view that allows the user to select a TA provided a course is selected.
4. A view that displays all tutorial/lecture sections taught provided a course and TA are selected.

## What's provided

## Getting Data

A dummy php script `get_info.php` is provided with some data. To get a list of courses

	get_info.php

To get a list of TAs

	get_info.php?course=THECOURSE

To get a list of sections

	get_info.php?course=THECOURSE&ta=THETA

Every query returns a JSON object with a `TYPE` attribute which is either `courses`, `tas`, `sections`, or `error`.

