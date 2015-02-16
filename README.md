FlyWatch
=====

Old PHP project created for [Sagatiba](http://www.sagatiba.com.br) circa 2002/2003.

FlyWatch took care of registering aircrafts, crew members, agents (handlers, caterers, ...),
flight permits and visa expiracy.

The goal is the make it easier (and way cheaper) to create the needed documentation for landing
executive airplanes.

Structure
-----

The structure of the project is simple.

* *cron*: jobs that run periodically
* *doc*: database schema project documentation in **sql** and **dia** format.
* *src*: all the source code goes here

Under *src* the main modules are:

* *admin*: user, group, permissions registry (admin dashboard)
* *agent*: permits, caterers, handlers
* *data*: registry point for aircraft, airport, citizenship, crew members, food
* *itinerary*: leg allocation, itinerary creation, pdf generation of needed documentation for landing
* *pax*: passengers
