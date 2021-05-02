# Secrets
Course Project using NodeJS features!

# Using

Use "npm i" to install all packages.
Connect to a mongodb database, or change it to your own database.
To get a full experience, it needs a google oauth key, you can use yours to get started.

# The idea
Part of a Udemy Full Stack Course, this application takes part of several packages to create an "authenticated" page of secret logged users.

As a big part of that, it used md5 (inital, removed later, with mongoose-encryption), bcrypt (also removed, but used to resolve in salts), and uses 
at last PassportJS to que encryption to the files and get things done.

Also, it has an authentication on Google (but has path to get Facebook Login, as well) to enter on the page.

# Inside application

***Make sure, if you want to get all of the stuff, to use mongodb, as it was settled as the database.

There are pages to get logged or registered, after home. Then all you nedd to do is logout (have fun!) or submit your secret. As simple as that.
