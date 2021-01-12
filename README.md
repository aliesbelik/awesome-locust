# Awesome Locust [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="assets/images/locust-logo.svg" align="right" width="260" alt="Locust">](https://locust.io/)

A curated collection of resources covering different aspects of load-testing using [Locust](https://locust.io/) framework and related stuff: plugins, integrations, testing techniques, devops practicies, etc.

> [Locust](https://locust.io/) is an open-source scalable load-testing framework written in Python.

## Contents

- [Official Resources](#official-resources)
- [Getting Started](#getting-started)
- [Tutorials](#tutorials)
- [Tools](#tools)
  - [Plugins](#plugins)
  - [Workers](#workers)
  - [Wrappers](#wrappers)
  - [Configuration Management](#configuration-management)
  - [Distributed](#distributed)
  - [Frameworks](#frameworks)
  - [Miscellaneous](#miscellaneous)
- [CI](#ci)
- [Trainings & Courses](#trainings--courses)
- [Videos](#videos)
- [Community](#community)
- [Related](#related)
  - [Awesome Lists](#awesome-lists)

## Official Resources

- [Homepage](https://locust.io/)
- [Documentation](https://docs.locust.io/en/latest/)
- [Source code](https://github.com/locustio/locust)

## Getting Started

## Tutorials

- [Locust for JMeter users](https://howardosborne.github.io/locust_for_jmeter_users/) - A tutorial on using Locust for people familiar with Apache JMeter.

## Tools

### Plugins

- [locust-plugins](https://github.com/SvenskaSpel/locust-plugins) - A set of useful plugins/extensions for Locust.

### Workers

- [boomer](https://github.com/myzhan/boomer) - A better load generator for Locust, written in `Golang`.
- [locust4j](https://github.com/myzhan/locust4j) - A load generator for Locust, written in `Java`.
- [swarm](https://github.com/anhldbk/swarm) - An elegant `Java` client for Locust.
- [node-locust](https://github.com/jspdown/node-locust) - A `Node.js` load generator for Locust.
- [ably-boomer](https://github.com/ably/ably-boomer) - Ably load generator for Locust, based on the [boomer](https://github.com/myzhan/boomer) library.

### Wrappers

- [invokust](https://github.com/FutureSharks/invokust) - A wrapper for Locust to allow running load tests in `Python` or on AWS Lambda.
- [strezz](https://github.com/abdoutelb/strezz) - A wrapper for stress testing using Locust based on `Jest`.
- [locust-runner](https://marketplace.visualstudio.com/items?itemName=VolkanOzdamar.locust-runner) - Marketplace extension for running Locust from `VS Code` IDE.
- [stormer](https://github.com/debugtalk/stormer) - Wrappers for making load test with Locust more convienient.

### Configuration Management

- [ansible-role-locust](https://github.com/tinx/ansible-role-locust) - An Ansible role to manage Locust master instances.
- [locust_slave](https://github.com/tinx/locust_slave) - An Ansible role to manage Locust slave instances.
- [terraform-aws-locust](https://github.com/mettjus/terraform-aws-locust) - Deploy a Locust stress test cluster on AWS based on CoreOS/Docker.

### Distributed

- [locust-swarm](https://github.com/SvenskaSpel/locust-swarm) - A tool for launching distributed Locust runs on a set of load generators.
- [azure-locust](https://github.com/ORBA/azure-locust) - Run distributed Locust load tests on Azure Container Instances.

### Frameworks

- [Taurus](https://gettaurus.org/docs/Locust/) - Locust Executor as part of `Taurus` framework.

### Miscellaneous

- [transformer](https://github.com/zalando-incubator/transformer) - A command-line tool and `Python` library to transform/convert web browser sessions (HAR files) into Locust load testing scenarios (locustfile).
- [swagger-to-locustfile](https://github.com/lieldulev/swagger-to-locustfile) - A command-line tool to create Locust tasks file (locustfile) from Swagger/OpenAPI spec.

## CI

- [locust-github-action](https://github.com/marketplace/actions/locust-load-test) - A GitHub action for load testing using Locust.
- [teamcity-locustio](https://plugins.jetbrains.com/plugin/13415-locust-io-test-runner) - Configurable Locust test runner plugin for JetBrains Teamcity.

## Trainings & Courses

- [Performance Testing Using Locust 1.0](https://www.udemy.com/course/performance-testing-using-locust/) - By Udemy.
- [Locust Performance Framework Development with Real Project](https://www.udemy.com/course/locust-performance-framework-development-with-real-project/) - By Udemy.

## Videos

## Community

- [`locust` on Stack Overflow](https://stackoverflow.com/questions/tagged/locust)
- [`@locustio` on Twitter](https://twitter.com/locustio)
- [`#locust` on Slack](https://slack.locust.io/)

## Related

### Awesome Lists

- [Awesome](https://github.com/sindresorhus/awesome) - The original awesome list of awesome lists.
- [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness) - A curated list of amazingly awesome awesomeness.
- [Awesome Software Quality](https://github.com/ligurio/awesome-software-quality) - A list of free software testing and verification resources.
- [Awesome Testing](https://github.com/TheJambo/awesome-testing) - A curated list of testing resources.
- [Awesome Page Speed Metrics](https://github.com/csabapalfi/awesome-pagespeed-metrics) - Metrics to help understand page speed and user experience.
- [Awesome Web Performance Optimization](https://github.com/davidsonfellipe/awesome-wpo) - A curated list of Web Performance Optimization.
- [Awesome Scalability](https://github.com/binhnguyennus/awesome-scalability) - The Patterns of Scalable, Reliable, and Performant Large-Scale Systems.
- [Awesome Site Reliability Engineering](https://github.com/dastergon/awesome-sre) - A curated list of Site Reliability and Production Engineering resources.
- [Awesome JMeter](https://github.com/aliesbelik/awesome-jmeter) - Open-source load testing and performance measurement tool, written in Java.
- [Awesome Gatling](https://github.com/aliesbelik/awesome-gatling) - Open-source load and performance testing framework based on Scala, Akka and Netty.
- [Awesome Tsung](https://github.com/aliesbelik/awesome-tsung) - Open-source multi-protocol distributed load testing tool, developed in Erlang.
- [Awesome k6](https://github.com/k6io/awesome-k6) - Open-source, developer-centric performance monitoring and load testing solution.

## Contributing

Contributions are welcome!<br>
Please take a look at the [contribution guidelines](CONTRIBUTING.md) first.

<a rel="license" href="https://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by/4.0/88x31.png" /></a>
