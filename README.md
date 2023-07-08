## People Counter

This project is a simple people counter that allows you to increment a count and save the count for future reference. The webpage displays the number of people entered, provides buttons to increment the count and save the count, and shows a list of previous count entries.

### Usage
To use the People Counter, open the `index.html` file in a web browser of your choice. The webpage will display the heading "People entered" along with the current count, two buttons labeled "INCREMENT" and "SAVE", and a section for previous count entries. Click the "INCREMENT" button to increase the count and the "SAVE" button to save the current count and reset it to zero.

### Features
- Count Increment: The "INCREMENT" button allows you to increment the count by one with each click.
- Count Saving: The "SAVE" button saves the current count and adds it to the list of previous count entries.
- Previous Entries: The webpage displays a list of previous count entries, showing all the counts that have been saved.

### Technologies Used
- HTML
- CSS
- JavaScript

### How It Works
1. When the webpage loads, the initial count is set to 0.
2. Clicking the "INCREMENT" button triggers the `increment` function.
3. The `increment` function increments the count by one and updates the count displayed on the webpage.
4. Clicking the "SAVE" button triggers the `save` function.
5. The `save` function appends the current count to the list of previous count entries and resets the count to zero.
6. The updated count and previous entries are displayed on the webpage.

### Future Enhancements
- Reset Button: Add a button to reset the count to zero without saving.
- Local Storage: Implement local storage to store and retrieve previous count entries, allowing the counts to persist even after closing the webpage.
- Delete Entries: Include an option to delete individual count entries or clear all previous entries.

Feel free to explore the code and make modifications according to your requirements or to further enhance the project.

### Hosted Project
The People Counter is hosted on GitHub Pages. You can access it [here](https://utkarshkrishna2004.github.io/People-Counter/).

Thank you!
