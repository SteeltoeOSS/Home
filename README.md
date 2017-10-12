# Steeltoe

Steeltoe is an open source project aimed at taking the tremendously useful tools from Netflix, Spring Cloud and others and making them available to the .NET community.

It was built to work with .NET Core as well as .NET Framework 4.x.

Today, most of all of the components work stand-alone (e.g., on  your local computer) as well as on Cloud Foundry, the industry leading multi-cloud application platform. In the near future you will see us add to the list of supported cloud application platforms.

Steeltoe components typically build on other technology offerings, such as Netflix and Spring Cloud by providing several packages that enable .NET developers to leverage these tools when implementing some of the basic patterns (e.g. centralized configuration management, service discovery, circuit breakers, etc. ) typically found in highly scalable and resilient distributed applications.

For example, using Steeltoe together with Netflix and Spring Cloud, developers are able to quickly stand up micro-services based applications that utilize the above mentioned patterns and run them on Cloud Foundry and other cloud based application platforms.

Steeltoe provides services that broadly fall into two categories:

* Services that simplify using .NET and ASP.NET on cloud platforms like Cloud Foundry, etc.:
  * Connectors (e.g. MySql, Redis, Postgres, RabbitMQ, OAuth, etc)
  * Configuration providers
  * Security providers (OAuth SSO, JWT, Redis Key Ring Storage, etc.)
  * Logging providers

* Services that enable .NET and ASP.NET developers to leverage Netflix, Spring Cloud and other industry leading services:
  * Configuration providers (Spring Cloud, Vault, etc.)
  * Service Discovery client (Netflix Eureka, etc.)
  * CircuitBreaker (Netflix Hystrix, etc.)
  * Management

Steeltoe is freely [available](https://www.nuget.org/packages?q=steeltoe) for usage today.  See the [documentation](http://http://steeltoe.io/) on the Steeltoe web site.

## Project Repositories

Steeltoe is fully open source and is composed of several [repositories](https://github.com/SteeltoeOSS) all found under the SteeltoeOSS organization.  Here are some of the most commonly used:

* [Configuration](https://github.com/SteeltoeOSS/Configuration) - configuration providers which extend the reach of [.NET Configuration](https://github.com/aspnet/Configuration) services

* [Connectors](https://github.com/SteeltoeOSS/Connectors) - simplify the process of configuring and using back-end services locally and in the cloud

* [Discovery](https://github.com/SteeltoeOSS/Discovery) - provide the ability to register and discover services locally and in the cloud.

* [CircuitBreaker](https://github.com/SteeltoeOSS/CircuitBreaker) - monitor and isolate requests to remote dependent services with latency and fault tolerance logic.

* [Security](https://github.com/SteeltoeOSS/Security) - simplify integration of security services provided by the cloud platform.

* [Management](https://github.com/SteeltoeOSS/Management) - add monitoring and management to production based application

## Getting Started

1. Perform any of the several [Quick Starts](http://steeltoe.io/docs/steeltoe-configuration/#1-1-quick-start) you will find in the [Steeltoe documentation](http://steeltoe.io/docs/).

1. Review, run, and modify the extensive collection of [Samples](https://github.com/SteeltoeOSS/Samples) available on Github.

1. Run through the freely available [Workshop](https://github.com/SteeltoeOSS/Workshop) which contains labs and lab write-ups for most all of the Steeltoe packages.

1. And of course, last but not least, you can always read the [Steeltoe documentation](http://steeltoe.io/docs/).

## Getting the Code

All new Steeltoe development is done on the `dev` branch in each of the above mentioned repositories.

More stable versions of the Steeltoe code can be found in `master`.

All release and release candidate packages are produced from `master`.

The latest prebuilt packages from each branch can be found on one of two MyGet feeds shown below.

Released and release candidates can be found on [NuGet](https://www.nuget.org/).

* [Development feed (Less Stable)](https://www.myget.org/gallery/steeltoedev)

* [Master feed (Stable)](https://www.myget.org/gallery/steeltoemaster)

* [Release or Release Candidate feed](https://www.nuget.org/)

## Engage, Contribute and Provide Feedback

The Steeltoe project welcomes contributions both by filing issues and through PRs.

Check out the [contributing](https://github.com/SteeltoeOSS/Home/tree/master/project-docs/contributing.md) page to see how you can get involved and contribute to Steeltoe.

Also its worth noting, the Steeltoe project has adopted the code of conduct defined by the [Contributor Covenant](http://contributor-covenant.org/).
If you'd like more information, see the [.NET Foundation Code of Conduct](http://www.dotnetfoundation.org/code-of-conduct) write-up.

## Governance Model

As a member of the [.NET Foundation](https://dotnetfoundation.org/), the Steeltoe project has adopted a [project governance](https://github.com/dotnet/home/blob/master/governance/project-governance.md) model in line with that recommended by the Foundation.

## Licenses

The Steeltoe project uses the [Apache License Version 2.0](LICENSE) license for all of its code.  See the [contribution licensing](project-docs/contributing-license.md) document for more details.
