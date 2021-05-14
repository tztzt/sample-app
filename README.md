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
  * Activation - using SendGrid to send emails
  * Login
  * Password Hash/Digest
  * Changing/Resetting Password 
* Login Features
  * 'Remember Me' token and digest   
* Other Account Features
  * Admin Users   
* Tweeting
  * Creating of microposts
  * Uploading of photos to host on AWS servers
* Following of users
  * Retrieval and display of following/followed users
  * Follow and unfollow of other users
  * Display of microposts of followed users    

## Concepts used in this Project
* Deployment of Project in Production
* Deployment of Project in Deployment to Heroku Apps
* Model-View Controller pattern
* Inheritance Hierachies
* Styling (using bootstrap)
* Use of cookies for local data storage
* Database Configuration (Production and Deployment)
* Partial Pages Refactoring
* Sending email templates via SendGrid
* Hosting of Images on Amazon Web Services 
