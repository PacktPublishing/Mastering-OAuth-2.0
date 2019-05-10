Overview
--------

This is the server-side example from the book "Mastering OAuth 2.0".  It is a
basic web application with an HTML/JavaScript frontend powered by a Java backend.
This application interacts with Facebook via OAuth 2.0 using the authorization
code grant authorization flow.


Running it
----------

In order to run this application, navigate to the root folder and execute the
following Maven command (you will need Maven v3.3.3 or higher):

  $ sudo mvn -Dmaven.tomcat.port=80 -Dmaven.tomcat.path=/ tomcat:run


Dependencies
------------

The book utilizes the following software packages and libraries during this
application's construction:

  * Apache Maven 3.3.3 - https://github.com/apache/maven/releases/tag/maven-3.3.3
  * Apache HTTPClient 4.5.1 - https://github.com/apache/httpclient/releases/tag/4.5.1
  * jQuery 1.11.3 - https://github.com/jquery/jquery/releases/tag/1.11.3
  * Java Servlet API 2.5 - http://mvnrepository.com/artifact/javax.servlet/servlet-api/2.5


See it on GitHub
----------------

For a more detailed look at the code, including commit history, see this 
project on GitHub!  You can find it at:

  https://github.com/mastering-oauth-2/server-side-example
  