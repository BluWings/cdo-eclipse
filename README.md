cdo-eclipse
===========

Provides Eclipse features and p2 repository to use the [Composite Data Objects for Java](http://www.github.com/buschmais/cdo) Framework in an Eclipse runtime environment. 


Build
-----
Start the Maven build on command line

	mvn -f com.buschmais.cdo.releng/pom.xml clean package

it will produce `com.buschmais.cdo.repository/target/repository` that contains Cdo and dependencies. 


Continuous Build
----------------

[![Build Status](https://secure.travis-ci.org/BluWings/cdo-eclipse.png)](http://travis-ci.org/BluWings/cdo-eclipse)
