Artificer: Wildfly
======================

All individuals, teams, and organizations tend to have a tangled mess of "stuff". That bucket can include bits of information, logical metadata, and physical files. Those "artifacts" are almost never isolated in nature. They're all connected and inter-dependent, but the relationships can be difficult to understand.

In the software development world, this is an especially important problem to solve. The development process often spews out a huge amount of artifacts, needed for future analysis and actions. Without the ability to analyze how the information, artifacts, and content within the artifacts are connected, development processes become difficult, at best, or nearly impossible, at worst. Further, it's not enough to simply know how the bits are related. How do you correlate the artifacts/metadata with, for example, service endpoints, the responsible teams/individuals, and change histories?

In steps Artificer. Artificer is a software artifact, logical metadata, and information repository. It consists of a common data model, multiple interfaces, useful tools, and extensibility. In less words? It's a powerful platform that untangles everything.

Artificer is 100% open source -- contributions are welcome!

Visit [artificer.jboss.org](http://artificer.jboss.org) to learn more.

## Usage

To start Artificer

    docker run -it -p 8080:8080 jboss/artificer/wildfly[:tag]

## Building the image

    docker build -t jboss/artificer/wildfly[:tag] --rm .
