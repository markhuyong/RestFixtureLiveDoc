RestFixture Live Documentation
==============================

Master Branch Build Status: [![Master branch build status](https://travis-ci.org/smartrics/RestFixtureLiveDoc.svg?branch=master)](https://travis-ci.org/smartrics/RestFixtureLiveDoc)

A suite of FitNesse tests built with the RestFixture, to document the RestFixture.

Download LiveDoc
----------------

LiveDoc is available for download from Maven Central
[smartrics-RestFixture-LiveDoc-4.0-documentation.zip](http://search.maven.org/remotecontent?filepath=smartrics/restfixture/smartrics-RestFixture-LiveDoc/4.0/smartrics-RestFixture-LiveDoc-4.0-documentation.zip)

```xml
<dependency>
  <groupId>smartrics.restfixture</groupId>
  <artifactId>smartrics-RestFixture-LiveDoc</artifactId>
  <version>${version}</version>
  <classifier>documentation</classifier>
  <type>zip</type>
</dependency>
```

Once downloaded, unzip the file and

* Slim tests are available in `smartrics-RestFixture-LiveDoc-4.0/livedocs/RestFixtureTests.html`
* FIT tests are available in `smartrics-RestFixture-LiveDoc-4.0/livedocs/RestFixtureFitTests.html`

Build LiveDoc
-------------

Execute

```
mvn test
```

To run the tests and generate the following reports:

* Slim tests: `target/fitnesse-junit/RestFixtureTests.html`
* FIT tests: `target/fitnesse-junit/RestFixtureFitTests.html`

Execute

```
mvn package
```

to generate the distributable zip file.

Run with -DwithLatestFitnesse to execute the tests with the latest version of Fitnesse:

```
mvn test -DwithLatestFitnesse
```

How to use RestFixture Live Documentation
-------------

 - [fitnesse - workflow of creating tests using RestFixture - Stack Overflow](https://stackoverflow.com/questions/35753103/workflow-of-creating-tests-using-restfixture)
