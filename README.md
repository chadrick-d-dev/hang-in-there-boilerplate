# Hang In There

A boilerplate repo.

### Iteration 0 - Main Page

- On July 8, 2020 and July 9, 2020 we completed iteration 0 by creating variables, functions, and an event listener in order to get the Poster image, title, and quote to display randomly on load of page.

Random poster appears on page load: 

![gif of main page poster upon load](/ReadMeGifs/PageLoad.gif)

### Iteration 1 - Switching Views

Form page:

- On July 9, 2020 we completed iteration 1 by creating variables, functions, and event listeners that targeted buttons to change page views by being clicked.

"Make Your Own Poster" Button Click: 

![gif of Make Your Own Poster Button being clicked](/ReadMeGifs/viewForm.gif)

- Here we click the Make Your Own Poster button, which takes the user from the main page view to the form view.

"Show Saved Posters" Button Click: 

![gif of View Saved Posters button being clicked](/ReadMeGifs/showSavedPostersButton.gif)

- Here we click the View Saved Posters button, which takes the user from the main page view to the saved posters view.

"Nevermind, Take Me Back!" Button Click: 

![gif of Nevermind, take me back! button being clicked](/ReadMeGifs/takeMeBack.gif)

- Here we click the Nevermind, take me back! button, which takes the user from the form view to the main page view.

"Back To Main" Button Click: 

![gif of Back to Main button being clicked](/ReadMeGifs/backToMainButton.gif)

- Here we click the Back to Main button, which takes the user from the saved posters view to the main page view.

## Iteration 2 - Creating a New Poster

- We Began work on this iteration on July 10th 2020, and completed it on July 11th 2020.

Form being filled out: 

![gif of iteration 2 functionality](/ReadMeGifs/iteration-2.gif)


- When user completes the input fields and then clicks the "Show My Poster" button:
  - The values from the input fields are saved to respective arrays as well as placed in a new Class instantiation of Poster which will be used to display a custom poster on the main view page.
  - The user is taken back to the main view page.
  - The custom poster is displayed.
  - The values from user were also saved (temporarily) in their respective arrays.

## Iteration 3 - Saving & Viewing Posters

- On July 11th 2020 we began working on this iteration, and completed this iteration on July 12th 2020.

Saved posters view: 

![gif of iteration 3 functionality](/ReadMeGifs/iteration3.gif)

- When a user clicks "Save This Poster" the current poster is saved as an object to the savedPosters array.
- A poster cannot be saved more than once, based on comparing the poster id to the the id's of the posters in the array.
- At the same time that poster is added to the the saved posters view, that can be seen when "Show Saved Posters" Button is clicked.

## Iteration 4 - Deleting Saved Posters

- On July 12th 2020 we began working on this iteration, and completed this iteration on July 13th 2020.

User saving posters, then viewing saved posters and deleting posters by double clicking on them: 

![gif of iteration 4 functionality](/ReadMeGifs/iteration4.gif)

- When a user is on the saved posters view they can now double click on a poster, which results in the deletion of that specific poster from the saved posters view and the savedPosters array.

## Optional Extensions - Gettin' fancy

Here's a list of possible extensions to implement - but **ONLY IF** your team has completed all the previous iterations **AND** have cleaned up your code to make it DRYer and more readable.

You are welcome to add your own extensions. Be sure they are thoughtful in terms of UX/UI, and that they do not break any prior functionality.

- Implement data validation and error handling into the form (disable button, provide error messages if data entered is not correct, etc)
- In the main poster view, allow users to click each piece of the poster (image, title, quote) to update just that piece with another random item from the appropriate array
- When a user single clicks a saved poster, create a modal to view it larger
- Allow users to drag and drop saved posters into whatever order they want them to appear


Project spec & rubric can be found [here](https://frontend.turing.io/projects/module-1/hang-in-there.html)
