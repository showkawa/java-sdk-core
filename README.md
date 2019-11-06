[![Build Status](https://travis-ci.com/IBM/java-sdk-core.svg?branch=master)](https://travis-ci.com/IBM/java-sdk-core)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.ibm.cloud/sdk-core/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.ibm.cloud/sdk-core)
[![CLA assistant](https://cla-assistant.io/readme/badge/ibm/java-sdk-core)](https://cla-assistant.io/ibm/java-sdk-core)

# java-sdk-core
This project contains the core classes used by Java SDK's generated by the IBM OpenAPI SDK Generator (openapi-sdkgen).
Java code generated by openapi-sdkgen will depend on the classes contained in this project.  Therefore, each Java SDK project will need to define a dependency on this project.

## Installation
You can use this project by defining it as a dependency within your "Java SDK" project (i.e. a project containing java code generated by the IBM OpenAPI SDK generator).
To find the correct version to specify in your dependency definitions, consult the `Releases` tab of this github repository.   There you will find the published releases (versions) of the project.

##### Maven
```xml
<dependency>
	<groupId>com.ibm.cloud</groupId>
	<artifactId>sdk-core</artifactId>
	<version>4.4.0</version>
</dependency>
```

##### Gradle

```gradle
'com.ibm.cloud:sdk-core:4.4.0'
```

## Prerequisites
- Java SE version 7 or newer is required

## Javadoc
You can find the Javadoc for this project here: https://ibm.github.io/java-sdk-core/

## Authentication
The java-sdk-core project supports the following types of authentication:
- Basic Authentication
- Bearer Token 
- Identity and Access Management (IAM)
- Cloud Pak for Data
- No Authentication

For more information about the various authentication types and how to use them with your services, click [here](Authentication.md)

## Issues

If you encounter an issue with this project, you are welcome to submit a [bug report](https://github.com/IBM/java-sdk-core/issues).
Before opening a new issue, please search for similar issues. It's possible that someone has already reported it.

## Open source @ IBM

Find more open source projects on the [IBM Github Page](http://github.com/IBM)

## License

This library is licensed under Apache 2.0. Full license text is
available in [LICENSE](LICENSE).

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Code of conduct

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).
