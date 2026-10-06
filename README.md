## Ashish Aggarwal

I modernise enterprise systems that have outlived their stack, and I sell the work
as **fixed-price modules** — each with written acceptance criteria, a date, and a
number that cannot grow.

Fifteen years of enterprise delivery. Most of it in **building management and
commercial real estate**: HVAC and metering telemetry, building operations,
and the investment modelling behind the buildings themselves.

### What I take on

| | |
|---|---|
| **Backend** | Spring Boot 2 → 3, Java 8/11 → 21, monolith decomposition |
| **Frontend** | AngularJS → Angular 17+, JSP/Struts → SPA |
| **Cloud** | On-prem → AWS. Terraform, containers, CI/CD, cutover runbooks |
| **Performance** | Named endpoints to an agreed p95, measured before and after |

Every engagement starts with a paid assessment: I read the codebase and return
every blocker, the effort behind each one, and a fixed price per module. Useful
on its own even if you stop there.

### Reference implementation

**[telemetry-pipeline](https://github.com/ashish168/telemetry-pipeline)** — an
event-driven pipeline for building sensor data. Ingest, windowed anomaly
detection, command dispatch over Kafka. Detection rules are a pure, unit-tested
module; the simulator models real occupancy curves and seeds three distinct
faults. Runs end to end in about a minute.

It exists because the interesting question in telemetry is not how to consume a
topic — it's noticing the sensor that stopped talking, which a purely reactive
consumer never does.

### Elsewhere

[ashishaggarwal168.com](https://ashishaggarwal168.com) ·
[LinkedIn](https://www.linkedin.com/in/ashish-aggarwal-b2a685a5/) ·
ashish@ashishaggarwal168.com

*Working IST. Overlaps the European afternoon and the Australian morning.*
