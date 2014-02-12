sort-exercise
=============

For simplicity, I created a data file where I created an example set of people in an oject array.
To view, open the people.html page.

The goal, as I interpreted the exercise, was to be able to display the information, and provide various ways to sort the info. I included 3 ways to sort.

Since Julian date is not really recognizable, I converted the dates to gregorian. I looked up how someone else did this and just borrowed the code for it. I didn't like how it included the day of the week, and time, so I formatted the date to mm/dd/yyyy format.

I then created jQuery objects to populate the #listPeople div.

I originally had separate functions for each type of sort, but then decided to consolidate it into 1 and allow a value to be added to choose the type of sort.

I hope this provides a good example of my JavaScript capabilities. I have actually done a similar type of exercise (a little be more advanced) that I did for fun recently. It can be found at http://rainshinemedia.com/portfolio/dev/us_map/us_map.html
