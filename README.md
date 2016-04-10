# Introduction

This application is front-end for offline web audio book application

# Usage

## Setting the app:

> rm -rf $tomcat/webapps/offline-audiobook-static

> mkdir $tomcat/webapps/offline-audiobook-static

> cp -r *  $tomcat/webapps/offline-audiobook-static

> cd $tomcat/bin

> ./shutdown.bat

> ./startup.bat

Test if the application is running correctly:
http://localhost:8080/offline-audiobook-static/

## Note
Backed application needs to be deployed (offline-audiobook-app)