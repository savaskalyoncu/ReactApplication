# ReactApplication

Note: this is an incomplete dummy application to learn REACT!
Not all part of it are fully implemented, e.g. radio buttons are not clickable on second page etc.

This is my first REACT page which i built 3 years ago as a quick exercise. The page is responsive and changes layout with the size of the window. The single page application consists of 2 pages:

1) first page shows a panel with an input form
2) second page shows a serach page where medical facilities or people can be searched


One can only navigate from first page to second page when checking a checkbox and filling the entire input form. There is a rudimentary input validation implemented, which for instance does not allow numbers for specifying a location.
The search page shows paginated search results once letters are typed into the search field. (Number of pagination links has to be fixed)

The application is using dummy data, which is hard-coded and thus not accessing a database.
Additionally the code could be better refactored instead of being all in two files(due to time issues this solution was implemented)
