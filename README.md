# docker-compose-drupal
This is to Launch drupal container with postgres database
This contains a docker-compose file to launch drupal in a container with database as postgres.
Start the containers by typing this:
	
	> docker-compose up

This releases two containers, one of Drupal running on port 8080 and another of postgres. This also creates a docker network. Also the data of postgres and Drupal is persistantly stored through docker volumes.


To stop these things, type:
	
	> docker-compose down


#Drupal
Drupal is a free, open-source content management system (CMS) with a large, supportive community. It's used by millions of people and organizations around the globe to build and maintain their websites. You probably use Drupal every day without knowing it, as many top businesses and government organizations use Drupal, like the Government of Australia, Red Cross, Harvard, The Economist, BBC, NBC News, Whole Foods, Cisco, Twitter, and many, many more.

#Postgres
PostgreSQL is a general purpose and object-relational database management system, the most advanced open source database system. PostgreSQL was developed based on POSTGRES 4.2 at Berkeley Computer Science Department, University of California.
PostgreSQL was designed to run on UNIX-like platforms. However, PostgreSQL was then also designed to be portable so that it could run on various platforms such as Mac OS X, Solaris, and Windows.
PostgreSQL is free and open source software. Its source code is available under PostgreSQL license, a liberal open source license. You are free to use, modify and distribute PostgreSQL in any form.

