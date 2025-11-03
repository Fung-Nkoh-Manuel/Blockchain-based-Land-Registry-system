The Distributed Environmental and Alert Notification System

Cameroon faces challenges in effectively communicating critical information — such as weather alerts, flood warnings, and agricultural updates — to local communities, farmers, and regional authorities.Traditional methods like radio or word-of-mouth are slow, inconsistent, and limited to specific areas.
Moreover, government and research data (INS, Geoportal, Open Data platforms) are available online but underutilized due to lack of integration and accessibility.
To summarize it all, there is no unified system that automatically collects, analyzes, and distributes real-time environmental or socio-economic data to help citizens, farmers, and organizations make informed decisions.


The Distributed Environmental and Alert Notification System is a data-driven platform that aggregates and analyzes public datasets from different APIs — including:
INS Cameroon API: Population, education, and socio-economic statistics.
Geoportal API: Geographic and spatial data for mapping and visualization.
Weather API: Real-time and forecasted weather conditions.
Open Data Cameroon: Datasets on agriculture, health, and environment.
The system processes this information to generate alerts (e.g., rainfall warnings, crop disease risks, or environmental hazards) and distributes them to users across multiple devices.


Data Collection Layer
Pull data from public APIs (INS, Geoportal, Weather, Open Data).
Parse and store data in a distributed database (e.g., MySQL cluster or cloud database).
Data Processing Layer
Analyse weather and environmental data to detect anomalies (e.g., heavy rainfall, extreme temperatures).
Match environmental data with population data to estimate affected regions.
Alert Management Layer
Generate automated notifications based on thresholds (e.g., “Rainfall > 50mm triggers a flood alert”).
Send alerts through:
Web dashboard (real-time display)
Mobile push notifications
Email
User Layer
Citizens and organizations can:
Subscribe to specific regions or alert types
View analytics on the dashboard
Download reports from the system
System Administration
Admin panel to manage API keys, user subscriptions, and alert rules.

