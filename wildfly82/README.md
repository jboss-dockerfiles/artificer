Artificer: Wildfly 8.2
======================

Artificer is an metadata and software artifact repository comprised of a common data model, multiple interfaces, powerful tools, and exensibility. It implements the [OASIS S-RAMP specification](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=s-ramp) which defines the data model, query language, and an Atom REST binding.

In addition to implementing the spec, Artificer provides a suite of powerful, flexible, and extensible capabilities, described below.

Artificer is 100% open source -- contributions are welcome!

Visit [artificer.jboss.org](http://artificer.jboss.org) to learn more.

## Usage

To start Artificer

    docker run -it artificer/wildfly82[:tag]

You may want to map the port(s) so you can access the app

    docker run -it -p 8080:8080 artificer/wildfly82[:tag]

## Building the image

    docker build -t artificer/wildfly82[:tag] --rm .
