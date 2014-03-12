#QA Tools Package

##Installation

Install Ant
http://ant.apache.org/bindownload.cgi

Install JDK
http://www.oracle.com/technetwork/java/javase/downloads/index.html

Add env variable: JAVA_HOME
Ex.: JAVA_HOME=C:\Program Files\Java\jdk1.7.0_45

While in project directory run:

    > ant

This will exececute included build file.

##Other tools

    > phpunit.bat # run php unit console
    > test.bat # run tests from ./tests directory
    > fixer.bat # run sensiolabs coding standards fixer on ./src
    > ant phpcs # run code sniffer
    > ant lint # check code for syntax errors

##Author
Jacek Kobus <kobus.jacek@gmail.com>