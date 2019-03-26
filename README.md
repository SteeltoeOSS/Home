# Steeltoe

* [Introduction](#introduction)
* [Project Repositories](#project-repositories)
* [Roadmaps](#roadmaps)
* [Getting Started](#getting-started)
* [Getting the Code](#getting-the-code)
* [Contributing](#contributing)
* [Governance Model](#governance-model)
* [Licenses](#licenses)

## Introduction

Steeltoe is an open source project aimed at making the tremendously useful tools from Netflix OSS, Spring Cloud and others available to the .NET community.

Steeltoe is built to work with .NET Core and .NET Framework 4.x. Steeltoe is compatible with .NET Standard 2.0. 

Today, most Steeltoe components work stand-alone (on your local computer) as well as on Cloud Foundry, the industry leading multi-cloud application platform.

Steeltoe components typically build on other technology offerings, such as Netflix OSS and Spring Cloud by providing several packages that enable .NET developers to quickly leverage these tools when implementing some of the basic patterns (for example: centralized configuration management, service discovery, circuit breakers, etc.) typically found in highly scalable and resilient distributed applications.

Steeltoe provides services that broadly fall into two categories:

* Services that simplify using .NET and ASP.NET on cloud platforms like Cloud Foundry:
  * Connectors (MySql, PostgreSQL, Microsoft SQL Server, RabbitMQ, Redis, OAuth, etc)
  * Configuration
  * Security (OAuth SSO, JWT, Redis Key Ring Storage, etc.)
  * Logging

* Services that enable .NET and ASP.NET developers to leverage Netflix OSS, Spring Cloud and other industry leading services:
  * Configuration providers (Spring Cloud, Vault, etc.)
  * Service Discovery client (Netflix Eureka, etc.)
  * CircuitBreaker (Netflix Hystrix, etc.)
  * Management

[Steeltoe is freely available](https://www.nuget.org/packages?q=steeltoe) for production application usage today. Be sure to visit the [official Steeltoe site](https://steeltoe.io/).

## Project Repositories

Steeltoe is fully open source and is composed of several [repositories](https://github.com/SteeltoeOSS) all found under the SteeltoeOSS organization.  Here are some of the most commonly used:

* [Configuration](https://github.com/SteeltoeOSS/Configuration) - configuration providers which extend the reach of [.NET Configuration](https://github.com/aspnet/Configuration) services

* [Common](https://github.com/SteeltoeOSS/Common) - Common packages to other Steeltoe components

* [CircuitBreaker](https://github.com/SteeltoeOSS/CircuitBreaker) - monitor and isolate requests to remote dependent services with latency and fault tolerance logic

* [Connectors](https://github.com/SteeltoeOSS/Connectors) - simplify the process of configuring and using back-end services locally and in the cloud

* [Discovery](https://github.com/SteeltoeOSS/Discovery) - provide the ability to register and discover services locally and in the cloud

* [Dockerfiles](https://github.com/SteeltoeOSS/Dockerfiles) - Our collection of docker files we have on dockerhub

* [eShopOnContainers](https://github.com/SteeltoeOSS/eShopOnContainers) - Sample reference microservice and container based application with added Steeltoe capabilities (Forked and updated from dotnet-architecture org)

* [Logging](https://github.com/SteeltoeOSS/Logging) - adds logging extensions

* [Management](https://github.com/SteeltoeOSS/Management) - add monitoring and management to production based application

* [Samples](https://github.com/SteeltoeOSS/Samples) - Our collection of Sample applications used as a reference for Steeltoe .NET Application development

* [Security](https://github.com/SteeltoeOSS/Security) - simplify integration of security services provided by the cloud platform

* [steeltoe-site](https://github.com/SteeltoeOSS/steeltoe-site) - All of the steeltoe.io website and documentation artifacts

* [Tooling](https://github.com/SteeltoeOSS/Tooling) - Steeltoe SDK and Tooling 

View the [Steeltoe project list](project-docs/project-list.md) for brief descriptions of all projects, build statuses, and links to the source code.

## Roadmaps
* [2.2.0](roadmaps/2.2.0.md) - In Progress
* [2.1.0](roadmaps/2.1.0.md) - Released
* [2.0.0](roadmaps/2.0.0.md) - Released

## Getting Started

1. Perform any of the several [Quick Starts](https://steeltoe.io/docs/steeltoe-configuration/#1-1-quick-start) you will find throughout the [Steeltoe documentation](https://steeltoe.io/docs/).

1. Review, run, and modify the extensive collection of [Samples](https://github.com/SteeltoeOSS/Samples) available on Github.

1. To get down into the details of any Steeltoe project, read the [documentation](https://steeltoe.io/docs/).

## Getting the Code

All new Steeltoe development is done on the `dev` branch in each of the above mentioned repositories.

More stable versions of the Steeltoe code can be found in `master`.

All release and release candidate packages are produced from `master`.

The latest prebuilt packages from each branch can be found on one of two MyGet feeds shown below.

Released and release candidates can be found on [NuGet](https://www.nuget.org/).

* [Development feed (Less Stable)](https://www.myget.org/gallery/steeltoedev)

* [Master feed (Stable)](https://www.myget.org/gallery/steeltoemaster)

* [Release or Release Candidate feed](https://www.nuget.org/)

## Contributing

The Steeltoe project welcomes contributions both by filing issues and through PRs. You are also welcome to join us on [Slack](https://slack.steeltoe.io/)

Check out the [contributing](https://github.com/SteeltoeOSS/Home/tree/master/project-docs/contributing.md) page to see how you can get involved and contribute to Steeltoe.

Also its worth noting, the Steeltoe project has adopted the code of conduct defined by the [Contributor Covenant](https://contributor-covenant.org/).
If you'd like more information, see the [.NET Foundation Code of Conduct](https://www.dotnetfoundation.org/code-of-conduct) write-up.

## Governance Model

As a member of the [.NET Foundation](https://dotnetfoundation.org/), the Steeltoe project has adopted a [project governance](https://github.com/dotnet/home/blob/master/governance/project-governance.md) model in line with that recommended by the Foundation.

## Licenses

The Steeltoe project uses the [Apache License Version 2.0](LICENSE) license for all of its code.  See the [contribution licensing](project-docs/contributing-license.md) document for more details.
