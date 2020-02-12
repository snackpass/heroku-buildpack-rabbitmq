Heroku buildpack: rabbitmq
======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks)
for adding rabbitmq to your application.

Testing
-------
heroku build -b .

This is designed to be used during Testing on Heroku CI. Add it in your app.json as a testing buildpack
