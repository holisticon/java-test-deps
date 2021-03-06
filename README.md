# de.holisticon.dependencies:junit-mockito
[![Build Status](https://secure.travis-ci.org/holisticon/java-test-deps.png)](https://travis-ci.org/holisticon/java-test-deps)
## Introduction
This is just a dead simple pom that aggregates test dependencies. These are:

- [junit](https://github.com/junit-team/junit/wiki) as a general purpose testing framework.
- [hamcrest](https://code.google.com/p/hamcrest/) for better asserts.
- [equalsverifier](https://code.google.com/p/equalsverifier/) to test equals and hashcode methods.
- [mockito](https://code.google.com/p/mockito/) for convenient mocking.
- [tempus-fugit](http://tempusfugitlibrary.org/) for concurrent testing
- [fest-assert](https://code.google.com/p/fest/) for fluent assertions

in their current version. That's it.

## Getting started
Put it in your pom and be happy. ;)

``` 
<dependency>
	<groupId>de.holisticon.dependencies</groupId>
	<artifactId>junit-mockito</artifactId>
	<version>1.0</version>
	<scope>test</scope>
	<type>pom</type>
</dependency>
```

## Contribution
Have a neat tool for testing that is not in here? Let us know.

## Sponsoring
This project is sponsored and supported by [holisticon AG](http://holisticon.de/cms/About/Startseite)

## License
This project is released under the revised BSD License (s. [License](license.txt)).
