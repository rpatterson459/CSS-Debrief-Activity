# CSS-Debrief-Activity

Skills based review for the Junior Web Developer CSS Introduction lesson.

## Directions

- When you get into your breakout room, select a team member to share their screen and record the answers the team finds
- With your Breakout Team, scroll through the CSS Code below and answer the questions in the comments
- Team members who are not sharing screen should also fill in the answers and make the changes in their own code
- Use your Google Foo skills to find the answers and explore what CSS can offer your website
- All team members should search for the answers, use the chat to send helpful links that are found
- Feel free to copy and paste useful links into comments in this file for easy reference in the future
- Communicate and work with your team to ensure all members understand the answers before you move on to answering the next question
- If you finish early, try the *BONUS* questions at the bottom of the file, and/or explore any concepts you come across that you find interesting or want to learn more about!
- HAVE FUN! :)

### Activity

## Part 1 - Clone the project

* Begin by _forking_ this project into a personal repository.
  * To do this, click the `Fork` button located at the top right of this page.
* Navigate to your github profile to find the _newly forked repository_.
* Clone the repository from **your account** into the directory on your computer that you use to keep your projects (ex. `dev` directory).
* Open the newly cloned project in a code editor (ex. Visual Studio Code).

### Part 2 - Edit the _cloned_ project

* from a text editor (i.e. - Visual Studio Code), select:
  * `File` > `Add Folder to WorkSpace`
    * Select the directory you use to store your projects (ex. `dev` directory)
    * From the text editor,in the directory you use to store your projects (ex. `dev` directory), locate the newly cloned project
    * Expand the project from the _project explorer (may just be called `explorer`)_
    * Modify the `index.html` and `style.css` per the directions provided.

1. Start by linking your css file to your html file

2. Open in browser/live server so you can see your changes

3. Let's change the font on the page to be more modern. Go to the Google Fonts website and find the 'Open Sans' font. Select all of the styles, and then paste the stylesheet link in the html, above the local CSS file. (This is linked for you)

4. In the body selector rule, add a font-family property with a value of ```'Open Sans', sans-serif```

5. Let's change the background of the body. Replace the background-color property with the background-image property. Add a value of linear gradient with ```whitesmoke``` as the first color, and ```rgb(35, 47, 58)``` as the second value.

6. Convert padding property on ```li a``` rule to shorthand

7. Add a text-align property with a value of center to the same ```li a``` ruleset.

8. Add Add a text-align property with a value of center to the center-title class selector.

9. Add a flex-direction property with a value of column to the ```section```, ```#about-sec```, and ```figure``` selectors.

10. Add a width property with the value of 50% to the ```figure``` selector.

11. Modify the colors, spacing, and transitions however you like to make the page look more legit!



### Part 3 - _Pushing_ new changes to repository

* From a _terminal_ navigate to the root directory of the _cloned_ project.
* From the root directory of the project, execute the following commands:
  * `git add .`
    * Add all files in current directory to the staging area
  * `git commit -m 'I have made an edit to a file!'`
    * Save all staged changes to local repository
  * `git push -u origin main`
    * Push changes from local repository to remote repository

### Part 4 - Submitting assignment

* From the browser, navigate to the _forked_ project from **your** Github account.
* Click the `Pull Requests` tab.
* Select `New Pull Request`

### Resources

- <https://www.w3schools.com/css/css_intro.asp>
- <https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS>

- <https://www.codecademy.com/learn/learn-intermediate-css/modules/layout-with-flexbox/cheatsheet>
