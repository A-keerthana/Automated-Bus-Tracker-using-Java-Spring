# Automated-Bus-Tracker-using-Java-Spring
Automated real‑time bus tracking system using Java Spring Boot, WebSockets, GPS integration, and geospatial APIs.


A fully automated bus-tracking system built with **Java Spring Boot**, designed to collect real-time GPS data from moving buses and relay location updates to connected clients.  
The backend handles GPS input parsing, ride assignments, real-time broadcasts over WebSockets, route-based geofencing, and integrates with mapping APIs for route visualization and alerting.


## Getting Started

1. Clone this repo  
2. Configure `application.yml` with GPS feed URL or mock provider  
3. Set up mapping API key and data source (e.g. PostgreSQL + PostGIS optional)  
4. Run with `mvn spring-boot:run` or `./gradlew bootRun`  
5. Connect client interface at `http://localhost:8080/` to view live tracking dashboard
