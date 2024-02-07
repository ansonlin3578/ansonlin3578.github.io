---
title: Transactions travel rule automated testing with CI/CD
summary: |
  <em><small style="background-color: #c5c5f7; color: #330066; padding: 5px;">python/pytest/docker/git/AWS lambda/AWS dynmodb/cloudflare</small></em><br>
  <small><em>Oct 2023 – now</em></small><br>
  To deploy the development environment using Docker for testing purposes and complete the end-to-end (E2E) automated testing process with pytest, including API functional testing, as well as performance testing of the web server using JMeter and k6.<br>
  --> [Maintanined producted](https://www.sygna.io/)
tags:
  - Automated testing
date: "2024-01-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: ''
  focal_point: Smart
---
1.Docker Deployment:
Set up Docker containers for the development environment, including web server and database.
Use docker-compose for orchestration and networking.

2.API Functional Testing:
Write pytest test cases to cover API functionality.
Utilize pytest fixtures for environment setup and teardown.

3.Performance Testing:
Use JMeter and k6 to simulate user scenarios and test web server performance under load.
Monitor metrics like response time, throughput, and error rate.

4.Resource Monitoring:
Monitor Docker container resource consumption (CPU, memory, network) using built-in tools or third-party solutions.
Store monitoring data in a database for analysis.

5.Data Integrity:
Verify correctness of data written to the database by the application.
Write test cases and use assertions to ensure data integrity.
--> [Maintanined producted](https://www.sygna.io/)