# Simple Maven configuration for Tomcat

## First configure Tomcat users
To enable command-line deployment with Maven, username and password should be configured in `tomcat_directory/conf/tomcat-users.xml`.

## Some useful commands
`
catalina start
`

`
mvn tomcat7:deploy
`

`
mvn tomcat7:redeploy
`

`
mvn clean package tomcat7:deploy
`

`
mvn clean package tomcat7:redeploy
`