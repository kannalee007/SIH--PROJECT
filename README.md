Live Bus Tracking System 🚌
A full-stack, real-time transit tracking platform designed to provide live vehicle locations and precise ETAs. This system leverages high-velocity GPS data and intelligent chatbot integration to modernize the commuter experience.

🌟 Key Features
Real-Time Visualization: Interactive map interface built with React.js to show live vehicle movement.

Precise ETA Generation: Custom algorithms process GPS feeds to calculate arrival times based on current traffic and route data.

Dual-Database Architecture: * PostgreSQL: Handles relational data, including complex route schedules, stops, and user accounts.

MongoDB: Manages high-throughput, unstructured real-time GPS coordinates for low-latency updates.

Conversational Interface: Integrated Dialogflow Chatbot allowing users to query bus statuses ("Where is the 202 bus?") via natural language.

RESTful API: Robust Node.js/Express backend for seamless data flow between the hardware feeds and the frontend.

🏗️ Technical Architecture

Frontend: React.js, Tailwind CSS, Mapbox/Google Maps API

Backend: Node.js, Express.js

Databases: PostgreSQL (Relational), MongoDB (NoSQL/Real-time)

AI/NLP: Google Dialogflow

Data Feed: GTFS-Realtime / GPS JSON streams

🛠️ Future Roadmap

[ ] Implementation of GTFS-Static for nationwide route support.

[ ] Push notifications for delays based on geofencing.

[ ] Mobile application using React Native.
