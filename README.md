# Stephen Daly

Software portfolio for early-career roles in software engineering, test automation, and platform / cloud engineering.

I am currently completing a Postgraduate Diploma in Software Development, Cloud Computing and DevOps at the University of Galway, building on prior experience in healthcare, clinical research, data, and regulated environments where accuracy, traceability and delivery discipline mattered.

Early-career software engineer focused on backend development, distributed systems, cloud, CI/CD, automation, and test automation. This portfolio highlights hands-on projects across Java, C#, C++, Python, Flask, Firebase, Spring Boot, React, Azure Functions, Jenkins, GitHub Actions, Docker, MySQL, AWS, and ESP32-based IoT telemetry.

## Start here

Best fit role families

* Software Engineering
* Test Automation / Software Test Engineering
* Platform / DevOps / Cloud Engineering

Key links

* [GitHub profile](https://github.com/sdaly-ie)
* [Firebase Serverless REST API Demo](https://github.com/sdaly-ie/firebase-serverless-rest-api)
* [Petitions CI/CD, Observability, and Browser Automation App](https://github.com/sdaly-ie/ct5209-springboot-war)
* [HiveWatch Cloud IoT](https://github.com/sdaly-ie/hivewatch-cloud-iot)
* [HiveWatch Lite](https://github.com/sdaly-ie/hivewatch-lite)
* [Distributed Flask Wiki Cache App](https://github.com/sdaly-ie/distributed-flask-wiki-cache)
* [Property Tracker CLI](https://github.com/sdaly-ie/property-tracker-cli)

## Featured projects

### Firebase Serverless REST API Demo (`firebase-serverless-rest-api`)

Comments application where users can submit and view comments through a Firebase-hosted front end and serverless REST API. I used it to demonstrate cloud API design, automated verification, Infrastructure as Code validation, deployed smoke checks, and operational alerting.

What it shows

* Serverless back-end development and deployment on Firebase Hosting, Cloud Functions v2, Express, and Firestore
* API contract visibility through OpenAPI and Swagger UI
* Layered automated verification using Jest, Pact, Playwright, Newman, and Go
* Practical CI/CD and Infrastructure as Code (IaC) hygiene
* Operational awareness through deployed smoke testing and Slack failure alerting

Links

* [Repository](https://github.com/sdaly-ie/firebase-serverless-rest-api)

### Petitions CI/CD, Observability, and Browser Automation App (`ct5209-springboot-war`)

Petitions web application that lets users create, browse, search for, and sign petitions. I used it as the basis for a deployment-focused engineering project covering CI/CD, WAR packaging, cloud-hosted runtime delivery, browser automation, and observability.

What it shows

* Java web application packaging and deployment with Spring Boot and Thymeleaf
* Jenkins-driven CI/CD workflow from build and test through to controlled deployment
* Dockerized Apache Tomcat runtime delivery on AWS EC2
* Browser-level automation using Cypress
* Metrics, monitoring, and tracing with Spring Boot Actuator, Prometheus, Grafana, OpenTelemetry, and Jaeger

Links

* [Repository](https://github.com/sdaly-ie/ct5209-springboot-war)

### HiveWatch Cloud IoT (`hivewatch-cloud-iot`)

Cloud-connected beehive monitoring project focused on automated temperature capture rather than manually maintained local records. The current public baseline validates a real temperature telemetry path from ESP32 firmware through Azure Functions, Azure Table Storage persistence, hosted telemetry retrieval, and a local ASP.NET Core Razor Pages monitoring dashboard with latest reading, recent readings, and freshness status.

What it shows

* Embedded telemetry development using Arduino/C++ firmware and a physical temperature probe
* C#/.NET 8 Azure Functions for telemetry ingestion and hosted retrieval
* Azure Table Storage persistence for accepted telemetry readings
* Local ASP.NET Core Razor Pages dashboard showing latest telemetry, recent readings, and freshness state
* Staged proof-of-concept progression across device, networking, cloud ingestion, persistence, retrieval, and dashboard layers
* Evidence-led troubleshooting, decision logging, and scope control during technical validation

Links

* [Repository](https://github.com/sdaly-ie/hivewatch-cloud-iot)

### HiveWatch Lite (`hivewatch-lite`)

Local full-stack beehive management prototype for manually recording hives and temperature readings, exploring practical application workflows, and generating a scoped Hive Health Insight. It combines CRUD, search, filtering, reassignment, aggregation, and optional OpenAI-backed summary generation with a deterministic local fallback.

Unlike HiveWatch Cloud IoT, this project is intentionally focused on local application design, business logic, UI/API integration, bounded AI feature integration, and layered automated testing rather than scalable field telemetry or near-real-time monitoring.

What it shows

* Full-stack development using Java, Spring Boot, React, and TypeScript
* Layered back-end design with controllers, services, repositories, DTOs, and JPA
* Domain behaviour including CRUD, search, filtering, relationships, aggregation, and API-driven UI flows
* Small-scope AI integration through the Hive Health Insight feature, with optional OpenAI-backed summaries and a deterministic fallback path
* Layered testing with repository, service, controller, component, and browser smoke coverage
* Supporting QA artefacts including traceability and AI-assisted test design notes

Links

* [Repository](https://github.com/sdaly-ie/hivewatch-lite)

### How the two HiveWatch projects differ

| Project | Problem it solves | Core design approach | Main engineering signal |
|---|---|---|---|
| **HiveWatch Lite** | Helps address the limitation of scattered or manually maintained hive temperature records by giving beekeepers a simple way to associate temperature readings with individual hives. It is a local full-stack beekeeping record application focused on hive records, temperature-reading entries, and scoped insight generation from the available temperature data. | Local Spring Boot and React full-stack application with REST API flows, domain modelling for hive records and temperature-reading records, bounded AI-assisted insight generation over the available temperature data, and layered automated testing across backend and frontend behaviour. | Full-stack application engineering, practical domain modelling, UI/API integration, manual temperature-record handling, pragmatic AI feature integration, and test-focused development in a realistic beekeeping context. |
| **HiveWatch Cloud IoT** | Supports beekeepers managing hives across dispersed apiary sites, where manual checks can become time-consuming, reactive, and difficult to prioritise. It is a cloud-connected beehive temperature-monitoring prototype that moves physical temperature telemetry through a staged sensor-to-cloud-to-dashboard path. | ESP32 and DS18B20 temperature telemetry using Arduino/C++ firmware; C#/.NET 8 Azure Functions for telemetry ingestion and hosted GetRecentTelemetry retrieval; Azure Table Storage persistence; and a local ASP.NET Core Razor Pages dashboard showing latest telemetry, recent readings, and freshness status. | End-to-end embedded-to-cloud engineering across real hardware, Wi-Fi/HTTPS telemetry, serverless ingestion, durable cloud storage, hosted read-back, and local dashboard monitoring, with evidence-led validation, staged delivery, and clear scope control. |

### Distributed Flask Wiki Cache App (`distributed-flask-wiki-cache`)

Wikipedia lookup application that retrieves article data through a distributed three-tier setup and caches repeat results to reduce unnecessary external lookups. It combines a Flask front end, remote Python execution on AWS EC2, and Dockerized MySQL caching on a separate virtual machine.

What it shows

* Python and Flask back-end development
* Distributed application flow across host, local virtual machines, and AWS EC2
* Remote script execution over SSH using Paramiko
* Dockerized MySQL caching with a cache-aside retrieval pattern
* Practical troubleshooting across networking, remote execution, and data boundaries

Links

* [Repository](https://github.com/sdaly-ie/distributed-flask-wiki-cache)

### Property Tracker CLI (`property-tracker-cli`)

Python command-line tool for analysing Irish new-house price data from a Google Sheets source, producing repeatable descriptive outputs and exportable results for review. A browser-based terminal demo wrapper makes the CLI easier to inspect online.

What it shows

* Python scripting and automation
* Google Sheets API integration and structured data handling
* Descriptive statistics and repeatable analysis workflows
* Defensive programming and validation
* TXT/CSV export and basic CI quality checks

Links

* [Repository](https://github.com/sdaly-ie/property-tracker-cli)

## How to review this portfolio

For QA / Test Automation roles

* Start with [Firebase Serverless REST API Demo](https://github.com/sdaly-ie/firebase-serverless-rest-api)
* Then review [Petitions CI/CD, Observability, and Browser Automation App](https://github.com/sdaly-ie/ct5209-springboot-war)
* Then review [HiveWatch Lite](https://github.com/sdaly-ie/hivewatch-lite)
* Then review [Property Tracker CLI](https://github.com/sdaly-ie/property-tracker-cli)

For Platform / DevOps / Cloud roles

* Start with [Petitions CI/CD, Observability, and Browser Automation App](https://github.com/sdaly-ie/ct5209-springboot-war)
* Then review [Firebase Serverless REST API Demo](https://github.com/sdaly-ie/firebase-serverless-rest-api)
* Then review [HiveWatch Cloud IoT](https://github.com/sdaly-ie/hivewatch-cloud-iot)
* Then review [Distributed Flask Wiki Cache App](https://github.com/sdaly-ie/distributed-flask-wiki-cache)

For Software Engineering roles

* Start with [HiveWatch Lite](https://github.com/sdaly-ie/hivewatch-lite)
* Then review [Petitions CI/CD, Observability, and Browser Automation App](https://github.com/sdaly-ie/ct5209-springboot-war)
* Then review [Firebase Serverless REST API Demo](https://github.com/sdaly-ie/firebase-serverless-rest-api)
* Then review [HiveWatch Cloud IoT](https://github.com/sdaly-ie/hivewatch-cloud-iot)
* Then review [Property Tracker CLI](https://github.com/sdaly-ie/property-tracker-cli)

## Profile links

* [GitHub profile](https://github.com/sdaly-ie)
* [Portfolio site](https://stephendaly.dev)

* * *

This site is published with GitHub Pages and served through my personal domain.

## About

Early-career software engineer building backend, distributed systems, cloud, CI/CD, automation, and IoT telemetry projects with Java, C#, C++, Python, Flask, Firebase, Spring Boot, Azure Functions, Jenkins, Docker, MySQL, and AWS.

[stephendaly.dev/](https://stephendaly.dev/)
