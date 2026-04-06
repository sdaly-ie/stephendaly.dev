# Stephen Daly

I am currently completing an NFQ Level 9 Postgraduate Diploma in Software Development, Cloud Computing and DevOps, building on prior experience in healthcare, clinical research, data, and regulatory environments where accuracy, traceability, and delivery discipline were important.

Early-career software engineer focused on backend development, cloud, CI/CD, automation, test automation, and platform engineering.

This repository serves as a landing page for my portfolio. It highlights projects that show how I approach software delivery, automated testing, deployment, observability, and operational thinking across Java, Python, Firebase, Spring Boot, React, Jenkins, GitHub Actions, AWS, Prometheus, Grafana, and OpenTelemetry.

## Relevant role families

This portfolio is currently most relevant to early-career software roles, including Intern, Graduate, and Junior positions in software engineering, platform / cloud / DevOps-adjacent engineering, and test automation.

- Software Engineering
- Platform / DevOps / Cloud Engineering
- Test Automation / Software Test Engineering

## Featured projects

### Firebase Serverless REST API Demo (`firebase-serverless-rest-api`)

Serverless REST API and static front end on Firebase Hosting using Cloud Functions v2, Express, and Firestore, with layered automated testing, Terraform validation, a deployed smoke check written in Go, and failure-only Slack alerting.

What it shows:
- Serverless back-end development and deployment on Firebase
- API contract visibility through OpenAPI and Swagger UI
- Layered automated verification using Jest, Pact, Playwright, Newman, and Go
- Practical CI/CD and Infrastructure as Code (IaC) hygiene
- Operational awareness through deployed smoke testing and Slack failure alerting

Repo:
- https://github.com/sdaly-ie/firebase-serverless-rest-api

### Petitions CI/CD, Observability, and Browser Automation App (`ct5209-springboot-war`)

Spring Boot web application packaged as a WAR file and deployed through a Jenkins pipeline to a Dockerized Apache Tomcat container on AWS EC2. The project also includes a local observability setup using Spring Boot Actuator, Prometheus, Grafana, OpenTelemetry, and Jaeger, along with Cypress browser automation for key end-to-end user flows and a supporting GitHub Actions workflow.

What it shows:
- Java web application packaging and deployment using Spring Boot, WAR packaging, and Apache Tomcat
- Jenkins-driven CI/CD with manual deployment approval and EC2 delivery
- Docker-based runtime deployment on AWS EC2
- Local observability using Spring Boot Actuator, Prometheus, Grafana, OpenTelemetry, and Jaeger
- Browser-level end-to-end verification using Cypress for petition creation and search flows
- Practical use of complementary pipelines, with Jenkins handling deployment and GitHub Actions handling lightweight browser automation checks

Repo:
- https://github.com/sdaly-ie/ct5209-springboot-war

### HiveWatch Lite (`hivewatch-lite`)

Full-stack beehive monitoring prototype built with a Spring Boot REST API and a React + TypeScript front end for managing hives and temperature readings, designed around a realistic beekeeping use case. The project includes layered back-end testing, front-end component testing, browser-level smoke testing, CI-based quality checks, and a small practical AI-enhanced feature with deterministic fallback behaviour.

What it shows:
- Full-stack development using Java, Spring Boot, React, and TypeScript
- Layered back-end design with controllers, services, repositories, DTOs, and JPA
- Real domain behaviour including CRUD, search, filtering, relationships, aggregation, and API-driven UI flows
- Service-layer validation and business rules beyond thin CRUD
- Layered automated testing with repository, service, and controller coverage, plus JaCoCo reporting and traceability notes
- Front-end component testing with Vitest and React Testing Library
- Browser-level smoke testing with Selenium WebDriver
- CI-based quality signals through GitHub Actions and SonarQube Cloud
- A practical AI-enhanced feature through Hive Health Insight, with optional OpenAI-backed summaries and deterministic fallback behaviour
- AI-assisted QA notes that show selection and judgement rather than blind acceptance

Repo:
- https://github.com/sdaly-ie/hivewatch-lite

### Property Tracker CLI (`property-tracker-cli`)

Python command-line application for analysing Irish new-house price data via the Google Sheets API, with export workflows and a browser-based terminal demo wrapper.

What it shows:
- Python scripting and automation
- Google Sheets API integration and structured data handling
- Descriptive statistics and repeatable analysis workflows
- Defensive programming and clear validation/error handling
- TXT/CSV export and basic CI quality checks

Repo:
- https://github.com/sdaly-ie/property-tracker-cli

## Portfolio structure

The projects are ordered to show a practical spread of engineering capability across:

1. Cloud and back-end automation
2. Java deployment, CI/CD, observability, and browser automation
3. Full-stack application development, layered testing, and AI-assisted feature integration
4. Python scripting and data tooling

## GitHub profile

- https://github.com/sdaly-ie

---

This site is published with GitHub Pages and served through my personal domain.
