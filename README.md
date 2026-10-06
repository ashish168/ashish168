## Ashish Aggarwal

Software architect and builder. I design and build systems, and modernise the
ones that have outlived their stack — sold as **fixed-price modules**, each with
written acceptance criteria, a date, and a number that cannot grow.

Fifteen years of enterprise delivery. Most of it in **building management and
commercial real estate**: HVAC and metering telemetry, building operations,
workflow platforms, and the investment modelling behind the buildings
themselves.

The specialism is the problem and the sector, not the language. Java,
TypeScript, Node, Python, Go, Angular, React — the work decides the stack.

### What I take on

| | |
|---|---|
| **Architecture** | Target design, sequenced migration plans, service decomposition |
| **New builds** | Greenfield where the scope is defined, delivered module by module |
| **Modernization** | Framework and runtime upgrades, monolith decomposition, front-end rewrites |
| **Cloud** | On-prem → AWS. Terraform, containers, CI/CD, cutover runbooks |
| **Performance** | Named endpoints to an agreed p95, measured before and after |

Every engagement starts with a paid assessment: I read the codebase and return
every blocker, the effort behind each one, and a fixed price per module. Useful
on its own even if you stop there.

### Things you can look at

**[Estate operations console](https://ashish-ops-console.netlify.app)** ·
[source](https://github.com/ashish168/ops-console) — floor plans with devices
plotted by position and coloured by status, alert handling, and plant
telemetry across a two-building estate. Angular with standalone components and
signals; 142 kB and no charting library.

The plan is the point. "FCU 1.4 is 6.4°C above setpoint" says there is a
problem; the plan says it is the north-east meeting room, on the same riser as
the unit that failed last month.

**[Kelvin Supply](https://kelvin-supply.netlify.app)** ·
[source](https://github.com/ashish168/storefront) — a trade storefront for
architectural lighting. Specification filtering on colour temperature, beam
angle and ingress rating; trade accounts, cart, checkout, order history.

Colour temperature is rendered as colour, and each product is drawn in section
from its own data — beam at its real angle, filled at its real temperature.
Two products differing only in Kelvin look obviously different, which they
would not in a photograph.

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
