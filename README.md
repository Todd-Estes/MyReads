# MyReads

This React app allows users to to build and maintain a personal virtual library. Users can search an API for available titles, and add them to their own bookshelf. Within their bookshelf, users can categorize their selected books under three separate shelves: **Currently Reading**, **Want to Read**, and **Read**.



## Table of Contents
- [Notes and Design Decisions](#notes-and-design-decisions)
- [Get Setup and Running](#get-setup-and-running)
- [Using the App](#using-the-app)


## Notes and Design Decisions
1. I originally built this app out in a forked version of the Udacity starter repo. I wanted to build it out with create-react-app (which is now depricated 🤷🏻‍♂️), so I copied most of the work I did there into this project. That's why there aren't too many commits, because I handled most of the debugging work there. Here's the link to the original forked repo: https://github.com/Todd-Estes/nd0191-c1-myreads

2. I wanted to use some custom eslint configurations for the first time in a project. I created a .eslintrc.js file with different plugins and rules. Some of the plugind and rules might be depricated, but it was good practice.

3. I added the SEARCH_TERMS.md file that is missing from the original parent Udacity repo. The link to it on that repo is broken, as well.

4. This project was built with Node v18.16.0 and NPM 9.5.1. Hopefully that doesn't affect your ability to install the dependencies on your local machine...


## Get Setup and Running

1. Clone the repository:

    $`git clone git@github.com:Todd-Estes/MyReads.git`

2. Install dependencies:

    **First, cd into my my-reads!**

    This project was built with Node v18.16.0 and NPM 9.5.1.
   
    $`npm install`

4. Start the app:

    $`npm start`

    The app should run on localhost:3000
   
## Using the App
1. `You should see your MyReads home page:`



![Screenshot 2024-09-17 at 2 55 19 PM](https://github.com/user-attachments/assets/de23887e-b913-492d-a48a-426caf43ccf5)
   
2. `Click the down-arrow icon next to a book. When you select a new shelf, the book should move to that shelf immediately. If you select None, the book will disappear. Reload after you make a change - the changes should persist.`
   
![Screenshot 2024-09-17 at 2 55 50 PM](https://github.com/user-attachments/assets/ae1d6aba-713d-4bcc-b123-42a58f151dd6)

3. `Click the floating + icon on the bottom right of the page to get to the search page. Here, you can search for available titles to add to your bookshelves.  If you select the dropdown for a book you don't already have, you'll see the three shelf options.`

   ![Screenshot 2024-09-17 at 2 56 39 PM](https://github.com/user-attachments/assets/fd9c87df-b47c-411f-a0ba-308e7d5b91d2)

4. `Save a new book to one of your shelves. Clear out the search bar, and type back in the text that showed you the new book originally. Select the dropdown for the book you just added, and you should see the shelf that you selected, along with the None option.`

   ![Screenshot 2024-09-17 at 2 56 50 PM](https://github.com/user-attachments/assets/693e3f63-7771-4e3a-82a4-120ea7d4c03d)


5. Go back to the home page by clicking the back arrown next to the search bar, and you should see the new book that you selected on the selected shelf. Reload the page, and the book should persist on its selected shelf.
   
