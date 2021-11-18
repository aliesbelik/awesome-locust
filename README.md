# Awesome Locust [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<!--lint ignore double-link-->
[<img src="assets/images/locust-logo.svg" align="right" width="260" alt="Locust">](https://locust.io/)

<!--lint ignore double-link-->
A curated collection of resources covering different aspects of load-testing using [Locust](https://locust.io/) framework and related stuff: plugins, integrations, testing techniques, DevOps practices, etc.

<!--lint ignore double-link-->
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
  - [CI/CD](#cicd)
  - [Reporting](#reporting)
  - [Miscellaneous](#miscellaneous)
- [Trainings & Courses](#trainings--courses)
- [Videos](#videos)
  - [Talks](#talks)
  - [Video Tutorials](#video-tutorials)
- [Community](#community)
- [Related](#related)
  - [Awesome Lists](#awesome-lists)

## Official Resources

<!--lint ignore double-link-->
- [Homepage](https://locust.io/)
- [Documentation](https://docs.locust.io/en/latest/)
- [Source code](https://github.com/locustio/locust)

## Getting Started

## Tutorials

- [Locust for JMeter users](https://howardosborne.github.io/locust_for_jmeter_users/) - A tutorial on using Locust for people familiar with Apache JMeter.
- [How do I Locust](https://github.com/pglass/how-do-i-locust) - A quick overview and random tips for Locust.

## Tools

### Plugins

- [locust-plugins](https://github.com/SvenskaSpel/locust-plugins) - A set of useful plugins/extensions for Locust.

### Workers

<!--lint ignore double-link-->
- [boomer](https://github.com/myzhan/boomer) - A better load generator for Locust, written in Golang.
- [locust4j](https://github.com/myzhan/locust4j) - A load generator for Locust, written in Java.
- [swarm](https://github.com/anhldbk/swarm) - An elegant Java client for Locust.
- [node-locust](https://github.com/jspdown/node-locust) - A Node.js load generator for Locust.
- [ably-boomer](https://github.com/ably/ably-boomer) - Ably load generator for Locust, based on the [boomer](https://github.com/myzhan/boomer) library.

### Wrappers

- [invokust](https://github.com/FutureSharks/invokust) - A wrapper for Locust to allow running load tests in Python or on AWS Lambda.
- [strezz](https://github.com/abdoutelb/strezz) - A wrapper for stress testing using Locust based on Jest.
- [locust-runner](https://marketplace.visualstudio.com/items?itemName=VolkanOzdamar.locust-runner) - Marketplace extension for running Locust from VS Code IDE.
- [stormer](https://github.com/debugtalk/stormer) - Wrappers for making load test with Locust more convenient.

### Configuration Management

- [ansible-role-locust](https://github.com/tinx/ansible-role-locust) - An Ansible role to manage Locust master instances.
- [locust_slave](https://github.com/tinx/locust_slave) - An Ansible role to manage Locust slave instances.
- [terraform-aws-locust](https://github.com/mettjus/terraform-aws-locust) - Deploy a Locust stress test cluster on AWS based on CoreOS/Docker.

### Distributed

- [locust-swarm](https://github.com/SvenskaSpel/locust-swarm) - A tool for launching distributed Locust runs on a set of load generators.
- [azure-locust](https://github.com/ORBA/azure-locust) - Run distributed Locust load tests on Azure Container Instances.
- [kangal](https://github.com/hellofresh/kangal) - Run performance tests in Kubernetes cluster using multiple load generators.
- [klocust](https://github.com/DevopsArtFactory/klocust) - A command-line tool for managing Locust distributed load testing on Kubernetes.
- [zelt](https://github.com/zalando-incubator/zelt) - Zalando End-to-end Load Tester, a command-line tool for orchestrating the deployment of Locust in Kubernetes.
- [locust-on-azure](https://github.com/yorek/locust-on-azure) - Running distributed Locust on Azure Container Instances.

### Frameworks

- [Taurus](https://gettaurus.org/docs/Locust/) - Locust Executor as part of Taurus framework.
- [httprunner](https://github.com/httprunner/httprunner) - A HTTP/S testing framework with reuse of Locust.

### CI/CD

- [locust-github-action](https://github.com/marketplace/actions/locust-load-test) - A GitHub action for load testing using Locust.
- [teamcity-locustio](https://github.com/orn0t/teamcity-locustio) - Configurable [Locust test runner plugin](https://plugins.jetbrains.com/plugin/13415-locust-io-test-runner) for JetBrains Teamcity.
- [Keptn Locust Service](https://github.com/keptn-sandbox/locust-service) - [Keptn integration](https://medium.com/keptn/automating-evaluating-load-testing-with-locust-and-keptn-6cf5c8f76bed) to performance test application using Locust.

### Reporting

- [Locust Exporter](https://github.com/ContainerSolutions/locust_exporter) - A Locust metrics exporter for Prometheus.
- [locust-reporter](https://github.com/benc-uk/locust-reporter) - Generate HTML reports from Locust load test output.
- [JtlReporter](https://github.com/ludeknovy/jtl-reporter) - Online reporting application to generate performance reports from Locust by either uploading CSV file or streaming data from the test run continuously.

### Miscellaneous

- [transformer](https://github.com/zalando-incubator/transformer) - A command-line tool and Python library to transform/convert web browser sessions (HAR files) into Locust load testing scenarios (locustfile).
- [swagger-to-locustfile](https://github.com/lieldulev/swagger-to-locustfile) - A command-line tool to create Locust tasks file (locustfile) from Swagger/OpenAPI spec.

## Trainings & Courses

- [Performance Testing Using Locust 1.0](https://www.udemy.com/course/performance-testing-using-locust/) - By Udemy.
- [Locust Performance Framework Development with Real Project](https://www.udemy.com/course/locust-performance-framework-development-with-real-project/) - By Udemy.

## Videos

### Talks

- [An Intro to Load Testing with Locust and Python](https://www.youtube.com/watch?v=uvs4cq6JCeU) - Gabriel Boorse @ PyBay 2019.
- [Load test your backend with locust.io](https://www.youtube.com/watch?v=1_xROmLYvtY) - Ivan Matellanes @ PyLondinium 2018.
- [Load testing with Locust](https://www.youtube.com/watch?v=XjSEgiFDARw) - Kubilay Kahveci @ FOSDEM 2018.
- [Performance Testing with Python and Locust](https://www.youtube.com/watch?v=5sSouciEgWE) - Michael Sluyter @ PyTexas 2017.

### Video Tutorials

- [Load Testing with Python and Locust.io](https://www.youtube.com/playlist?list=PLotCx_Au_rT1LW_qpMWU40Q-vegZua-i8) - Tutorial series by Nicolai Gram.

## Community

- [`locust` on Stack Overflow](https://stackoverflow.com/questions/tagged/locust)
- [`@locustio` on Twitter](https://twitter.com/locustio)
- [`#locust` on Slack](https://slack.locust.io/)

## Related

### Awesome Lists

- [Awesome Software Quality](https://github.com/ligurio/software-quality-wiki) - A list of free software testing and verification resources.
- [Awesome Testing](https://github.com/TheJambo/awesome-testing) - A curated list of testing resources.
- [Awesome Page Speed Metrics](https://github.com/csabapalfi/awesome-pagespeed-metrics) - Metrics to help understand page speed and user experience.
- [Awesome Web Performance Optimization](https://github.com/davidsonfellipe/awesome-wpo) - A curated list of Web Performance Optimization.
- [Awesome Scalability](https://github.com/binhnguyennus/awesome-scalability) - The Patterns of Scalable, Reliable, and Performant Large-Scale Systems.
- [Awesome Site Reliability Engineering](https://github.com/dastergon/awesome-sre) - A curated list of Site Reliability and Production Engineering resources.
- [Awesome JMeter](https://github.com/aliesbelik/awesome-jmeter) - Open-source load testing and performance measurement tool, written in Java.
- [Awesome Gatling](https://github.com/aliesbelik/awesome-gatling) - Open-source load and performance testing framework based on Scala, Akka and Netty.
- [Awesome Tsung](https://github.com/aliesbelik/awesome-tsung) - Open-source multi-protocol distributed load testing tool, developed in Erlang.
- [Awesome k6](https://github.com/grafana/awesome-k6) - Open-source, developer-centric performance monitoring and load testing solution.

## Contributing

Contributions are welcome!<br>
Please take a look at the [contribution guidelines](CONTRIBUTING.md) first.
