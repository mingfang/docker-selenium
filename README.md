docker-selenium
===============

Run Selenium Tests Inside Docker

1. ```./build``` Docker image
2. ```./shell``` Shell into Docker container
3. ```runsvdir-start&``` Use Runit to start Selenium Server
4. ```mocha test.js -t 10000``` Run sample test

Sample output

```
>mocha test.js -t 10000

=======================================================================================
Selenium 2.0/webdriver protocol bindings implementation with helper commands in nodejs.
For a complete list of commands, visit http://webdriver.io/docs.html. 
=======================================================================================



  Test example.com
[01:51:08]:  SET SESSION ID 818ea329-1118-4d96-a28d-beeed385bb72
    Check homepage
      ✓ should see the correct title (53ms)
      ✓ should see the body (137ms)


  2 passing (2s)

```
