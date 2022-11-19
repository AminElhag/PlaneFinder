# PlaneFinder
a small Spring Boot RESTful web service called PlaneFinder to serve as an API gateway that I can poll for current aircraft and positions within range of a
small device on my desk. This device receives Automatic Dependent Surveillance—Broadcast (ADS-B) data from airplanes within a certain distance and shares them
with a service online, PlaneFinder.net. It also exposes an HTTP API that my gateway service consumes, simplifies, and exposes to other downstream services like the ones
