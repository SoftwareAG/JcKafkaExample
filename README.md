# Package Name : JcKafkaExample
This is a webMethods package and requires a webMethods Integration Server v. 11.0 to host it. Package versioning and configuration can be found in the package [manifest](./JcKafkaExample/manifest.v3) file. Service and API documentation is available on the package's home page http://&lt;server&gt;:&lt;port&gt;/&lt;packagename>.

## About

This is a demo package to show case the new event trigger introduced with webMethods 11.0. The event trigger can be used in conjunction with any event streaming provider as long as you have required plug-in. Currently Kafka is bundled with the WmStreaming package. We will releasing both plugins for other providers as well as SDK to allow developers to develop plug-ins themselves.

## How to use this package

* [webMethods Service Designer 11.0 Preview](https://tech.forums.softwareag.com/t/webmethods-service-designer-download/235227) - We have already pre-installed our new messaging package in this release.
* [Rancher Desktop](https://rancherdesktop.io) or [Docker Desktop](https://www.docker.com/products/docker-desktop/) - This will allow you to spin up your own Kafka confluence engine locally to complete the messaging end to end.

Then follow the tech article [An Introduction to our new messaging tools](https://tech.forums.softwareag.com/t/an-introduction-to-our-new-messaging-tools/289927) explains how to use our new event trigger and references this package as the example shown.

---
These tools are provided as-is and without warranty or support. They do not constitute part of the Software AG product suite. Users are free to use, fork and modify them, subject to the license agreement. While Software AG welcomes contributions, we cannot guarantee to include every contribution in the master project.

