# Refactor Mongoose Code
* Create a models directory
* Use module.exports
* Require everything correctly!

# Add the Comment model!
* Make our errors go away!
* Display comments on campground show page

# Comment New/Create
* Discuss nested routes
* Add the comment new and create routes
* Add the new comment form



Restful Routes

name    url             verb            desc.
========================================================
INDEX   /dogs           GET         Display a list of all dogs
NEW     /dogs/new       GET         Display form to make a new dog
CREATE  /dogs           POST        Add new dog to DB
SHOW    /dogs/:id       GET         Shows info about one dog


INDEX   /campgrounds     
NEW     /campgrounds/new
CREATE  /campgrounds
SHOW    /campgrounds/:id

NEW     campgrounds/:id/comments/new    GET
CREATE  campgrounds/:id/comments        POST