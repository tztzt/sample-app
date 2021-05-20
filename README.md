# Ruby on Rails Tutorial sample application
This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://www.railstutorial.org/)
(6th Edition)
by [Michael Hartl](https://www.michaelhartl.com/).
## License
All source code in the [Ruby on Rails Tutorial](https://www.railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.
## Getting started
To get started with the app, clone the repo and then install the needed gems:
```
$ gem install bundler -v 2.2.15
$ bundle _2.2.15_ config set --local without 'production'
$ bundle _2.2.15_ install
```
Next, migrate the database:
```
$ rails db:migrate
```
Finally, run the test suite to verify that everything is working correctly:
```
$ rails test
```


## About - Features

* Account Management
  * Creation
  * Activation - via email
  * Login
  * Password Hashing/Digest
  * Changing/Resetting Password 
* Administrative Account
  * User deletion  
* Login Features
  * 'Remember Me' token and digest   
* Tweeting/Posting of microposts
  * Creation of microposts
  * Upload of photos hosted on AWS servers
* Following of users
  * Retrieval and display following/followed users
  * Follow and unfollow other users
  * Display of microposts of followed users    

## Concepts used in this Project
* Database creation using migration - database creation without needing SQL
* Deployment of Project in Production and Deployment to Heroku Apps
* Database Configuration (Production and Deployment)
* Model-View Controller pattern
* Inheritance Hierachies
* Styling (using bootstrap)
* Use of cookies for local data storage to track sessions 
* Partial Pages Refactoring
* Sending email templates via SendGrid interface
* Hosting of Images on Amazon Web Services 
* Setup of SSL to encrypt sent data 
