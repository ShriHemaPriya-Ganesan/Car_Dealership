**🚗 Car Dealership Web Application**

Car buyers expect seamless, data-driven experiences when evaluating dealerships and sharing feedback. However, many existing platforms lack intuitive interfaces, real-time sentiment insights, and secure, scalable infrastructure for handling both user-generated reviews and dealership data. This project bridges these gaps, delivering a robust, full-stack dealership solution with microservices at its core. They often face a fragmented online experience, limited transparency into dealership reputations, and cumbersome review processes. Car dealerships themselves often struggle with integrating user sentiment analytics and maintaining agile, responsive web platforms. There’s a strong need for a unified system that enables users to:

1. Discover dealerships and browse inventory nationwide.

2. Authentically review dealerships with built-in sentiment analysis.

3. Manage secure user registration and login.

4. Access all features across devices in a fast, cloud-native app.

**💡 Solution**

1. End users can register, log in, and interact via a React-powered frontend.

2. Car dealerships are managed through scalable backend services with robust data models.

3. Reviews are cross-checked for sentiment using NLP before posting, ensuring insightful feedback for both customers and dealerships.

4. Admins can oversee car models, makes, and dealership information using Django’s admin suite and APIs.

| Tech Stack                        | Reasoning                                                                            |
|-----------------------------------|--------------------------------------------------------------------------------------|
| React - Frontend                            | Used to build an interactive UI for login, registration, dealership listings, and reviews. |
| Python, Django, SQLite - Backend             | Rapid user auth, ORM-based modeling, tried-and-true session management.              |
| Node.js, Express, MongoDB - Dealership & Reviews           | Handles dealer and review management in a NoSQL schema for flexibility. Node.js + Express chosen for non-blocking I/O and scalability. |
| Python, Flask, NLTK -Sentiment Analysis       | Adds AI-driven insights to enhance decision-making for dealerships.        |
| Docker - Deployment                          | Each service is containerized with Docker for consistent environments.         |


🏗️ Solution Architecture

React Frontend → User interaction (login, register, view dealers, reviews).

Django Backend → User management, car models, proxy to microservices.

Express + MongoDB Service → Handles dealership and review data.

Flask Sentiment Analyzer → AI-powered sentiment classification.

Docker & Kubernetes → Containerized, scalable deployment.
