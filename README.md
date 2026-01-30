# ShareGeno
### Problem Statement Id - CS01SW
### Team Name - Horizon Hacks
### College Name - Yenepoya School of Engineering and Technology (NIAT)

## Problem Statement:
Building a digital platform to connect surplus food sources with NGOs for the real-time redistribution and waste reduction

## Proposed Solution:
Food wastage and hunger coexist due to the absence of a real-time, reliable coordination system between surplus food sources and NGOs. Our solution is a web-based real-time platform designed to bridge this gap across Karnataka, enabling surplus food to reach those in need quickly and safely.

The platform allows food donors (restaurants, event halls, hostels, canteens) to post surplus food details in real time. Verified NGOs receive instant notifications based on proximity and availability, enabling fast pickup and redistribution. The system uses geo-location-based matching, real-time updates, and a structured pickup workflow to minimize delays and food spoilage.

By integrating multilingual support (English & Kannada), secure authentication, and impact analytics, the platform ensures inclusivity, trust, transparency, and measurable social impact. This solution transforms food redistribution from a manual, unorganized process into a data-driven, scalable digital ecosystem.

## Innovation & Creativity:
This project goes beyond a simple listing platform by introducing intelligent and real-time decision-making into food redistribution:

Real-Time Food-to-NGO Matching: Unlike traditional manual coordination, the system instantly connects donors and nearby NGOs using live databases and WebSockets.

AI-Based Spoilage Priority Scoring: Food is prioritized scientifically based on expiry time and food type, ensuring that high-risk food is redistributed first.

Geo-Optimized Distribution: NGOs are notified based on distance, reducing fuel usage, response time, and operational cost.

Transparent Impact Measurement: The platform converts food redistribution into measurable metrics such as meals served, food saved (kg), and CO₂ emissions reduced.

Trust & Accountability Layer: A two-way rating system between donors and NGOs encourages reliability and long-term ecosystem health.

The innovation lies in combining real-time systems, geospatial intelligence, and data-driven prioritization to solve a critical social problem efficiently.

## Technical Complexity & Stack:
We will be using Nextjs as aour primary framework.

This project involves high technical complexity as it goes beyond a basic CRUD application and implements a real-time, multi-user, geo-aware system.

The complexity arises from:

Real-time data synchronization between donors and multiple NGOs using WebSockets/Firebase

Concurrent request handling to prevent race conditions when multiple NGOs attempt to accept the same food listing

Geo-spatial computation for distance-based NGO prioritization and optimized pickups

Role-based access control (RBAC) ensuring secure, permission-driven workflows for donors, NGOs, and admins

Event-driven notification architecture for instant alerts and state updates

Algorithmic spoilage-priority scoring to rank food listings based on urgency

Secure cloud deployment with scalable backend services and protected APIs

Analytics computation for impact measurement and reporting

## Usability & Impact:
Simple role-based dashboards for Donors, NGOs, and Admins

One-click food posting and acceptance workflow

Instant notifications eliminate manual calls and delays

Language accessibility with English and Kannada support

Mobile-responsive web design for easy field usage

Social Impact

Reduces food wastage by ensuring surplus food is redistributed before expiry

Improves food access for vulnerable communities

Saves operational costs for NGOs through optimized routing

Builds trust through verified NGOs and transparent workflows

Provides donors with CSR-ready impact metrics

By enabling faster redistribution, reducing waste, and increasing accountability, the platform creates a sustainable, scalable, and real-world-ready solution to hunger and food waste.

## Setup Instructions:
Just clone the repo using http or ssh and then cd into the folder and run "npm run dev" to run the app.

## Presentation & Demo Link:
Coming soon... Stay Tuned.