services-parent
===

Services parent pom.

[![Build Status](https://travis-ci.org/nmdp-bioinformatics/service-parent.svg?branch=master)](https://travis-ci.org/nmdp-bioinformatics/service-parent)


Projects that use the services parent pom include
 * [service-common](https://github.com/nmdp-bioinformatics/service-common) - Services common libraries
 * [service-epitope](https://github.com/nmdp-bioinformatics/service-epitope) - T-cell epitope group matching service for DPB1 locus
 * [service-feature](https://github.com/nmdp-bioinformatics/service-feature) - Enumerated sequence feature service
 * [service-hml](https://github.com/nmdp-bioinformatics/service-hml) - HML service


###Using service-parent

Artifacts from this project are available from the Maven Central repository.

E.g.
```xml
<dependency>
  <groupId>org.nmdp.service</groupId>
  <artifactId>service-parent</artifactId>
  <version>${version}</version>
</dependency>
```

 * [Maven Central artifact search](http://search.maven.org/#search|ga|1|g%3A%22org.nmdp.service%22)


###Hacking service-parent

Install

 * JDK 1.7 or later, http://openjdk.java.net
 * Apache Maven 3.2.5 or later, http://maven.apache.org

To build

    $ mvn install