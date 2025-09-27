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

🛠️ Tech Stack & Reasoning
🎨 Frontend: React.js

Used to build an interactive UI for login, registration, dealership listings, and reviews.

Chosen for its component-based architecture, reusability, and seamless integration with backend APIs.

⚙️ Backend Core: Python, Django, SQLite

Django manages user authentication, models, and proxy services.

SQLite stores structured data like Car Make and Car Model.

Provides a secure, fast, and maintainable backend for the core web application.

🗄️ Reviews & Dealers Service: Node.js, Express, MongoDB

Handles dealer and review management in a NoSQL schema for flexibility.

Dockerized for portability and deployed as a microservice.

Node.js + Express chosen for non-blocking I/O and scalability.

🤖 Sentiment Analysis Service: Python, Flask, NLTK

Deployed on IBM Cloud Code Engine.

Analyzes review text and classifies sentiment as positive, negative, or neutral.

Adds AI-driven insights to enhance decision-making for dealerships.

📦 Containerization & Deployment: Docker & Kubernetes

Each service is containerized with Docker for consistent environments.

Application deployed on Kubernetes for scalable orchestration.

Ensures high availability, portability, and maintainability.

🔄 CI/CD: GitHub Actions + Linting + Cloud IDE Testing

Automated pipelines for code quality checks and deployments.

Enables continuous testing and integration for reliable releases.

🏗️ Solution Architecture

React Frontend → User interaction (login, register, view dealers, reviews).

Django Backend → User management, car models, proxy to microservices.

Express + MongoDB Service → Handles dealership and review data.

Flask Sentiment Analyzer → AI-powered sentiment classification.

Docker & Kubernetes → Containerized, scalable deployment.
