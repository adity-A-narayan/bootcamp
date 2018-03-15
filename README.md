# bootcamp on web development

A complete RESTful webapp to create and manage camping playgrounds.

RESTFUL ROUTES

name      url         description
===============================================
INDEX   /campgrounds        Display a list of all campgrounds
NEW     /campgrounds/new    Displays form to make a new campground
CREATE  /campgrounds        Add new campground to DB
SHOW    /campgrounds/:id    Shows info about particular campground

NEW     campgrounds/:id/comments/new    GET
CREATE  campgrounds/:id/comments      POST
