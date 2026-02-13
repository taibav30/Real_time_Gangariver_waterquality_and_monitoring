# Real_time_Gangariver_waterquality_and_monitoring
Real-Time Ganga River Water Quality Monitoring &amp; Forecasting system built using the MERN stack. The platform visualizes 10-day historical data and 3-day forecasts using mock datasets, with interactive India map, pollution alerts, health impact classification, location comparison, downloadable reports, and a voice-enabled AI chatbot

This project is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) web application developed to monitor and forecast the water quality of the Ganga River. The platform is designed to transform complex environmental data into clear, interactive, and actionable insights for both citizens and policymakers.

The system visualizes the last 10 days of historical water quality data and provides a 3-day short-term forecast using realistic mock datasets, including rainfall, river flow, Dissolved Oxygen (DO), Biological Oxygen Demand (BOD), nitrate, and fecal coliform levels. The forecasting logic is rule-based for the hackathon prototype and can be extended to machine learning models in future implementations.

An interactive India map highlights the Ganga river path using a color-coded heatline (Green: Safe, Yellow: Moderate, Red: Polluted), along with key monitoring locations such as Haridwar, Kanpur, Varanasi, and Patna. Users can explore parameter-wise time-series charts and compare two locations side-by-side to better understand regional pollution trends.

The platform also features threshold-based smart alerts with contextual indicators explaining potential pollution causes. To make the system human-centric, water quality data is translated into safety classifications for drinking, bathing, and aquatic life.

Additionally, a voice-enabled AI chatbot, “Ask Ganga,” allows users to query water conditions at any location and receive instant summaries along with forecast insights. Downloadable PDF and CSV reports provide structured summaries including averages, forecast results, and alert status.

The architecture is modular and scalable, enabling future integration with IoT sensors, ML-based forecasting models, and real-time environmental data sources.
