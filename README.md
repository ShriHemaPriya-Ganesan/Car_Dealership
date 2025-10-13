**🚗 Car Dealership**

Car buyers expect seamless, data-driven experiences when evaluating dealerships and sharing feedback. However, many existing platforms lack intuitive interfaces, real-time sentiment insights and secure, scalable infrastructure for handling both user-generated reviews and dealership data. This project bridges these gaps, delivering a robust, full-stack dealership solution with microservices at its core. 

They often face a fragmented online experience, limited transparency into dealership reputations, and cumbersome review processes. Car dealerships themselves often struggle with integrating user sentiment analytics and maintaining agile, responsive web platforms. There’s a strong need for a unified system that enables users to:

1. Discover dealerships and browse inventory nationwide.

2. Authentically review dealerships with built-in sentiment analysis.

3. Manage secure user registration and login.

4. Access all features across devices in a fast, cloud-native app.

**💡 Solution**

1. End users can register, log in, and interact via a React-powered frontend.

2. Car dealerships are managed through scalable backend services with robust data models.

3. Reviews are cross-checked for sentiment using NLP before posting, ensuring insightful feedback for both customers and dealerships.

4. Admins can oversee car models, makes, and dealership information using Django’s admin suite and APIs.

**🏗️ Solution Architecture**

| Layer | Tech Stack                        | Reasoning                                                                            |
|-------|-----------------------------------|--------------------------------------------------------------------------------------|
|Frontend| React                             | Used to build an interactive UI for login, registration, dealership listings, and reviews. |
|Backend| Python, Django, SQLite             | Rapid user auth, ORM-based modeling, tried-and-true session management.              |
|Dealership & Reviews | Node.js, Express, MongoDB            | Handles dealer and review management in a NoSQL schema for flexibility. Node.js + Express chosen for non-blocking I/O and scalability. |
|Sentiment Analysis | NLTK       | Adds AI-driven insights to enhance decision-making for dealerships.        |
|Deployment| Docker                           | Each service is containerized with Docker for consistent environments.         |

**🧑‍💻 Application Work Flow**

**Landing page offers registration and login, plus intuitive access to all dealerships.**
<img width="1900" height="908" alt="Dealership_home_page" src="https://github.com/user-attachments/assets/d2110ba8-c882-4dd6-979c-c1c76cb3e455" />
<img width="1057" height="876" alt="sign-up" src="https://github.com/user-attachments/assets/38c2110f-34f0-4ef7-a4a3-50a1665472df" />


**Users can view company background (About Us), contact details, and detailed dealership inventories.**
<img width="1901" height="907" alt="about_us" src="https://github.com/user-attachments/assets/e701f233-7917-456f-a898-67635ecb4280" />
<img width="1597" height="833" alt="image" src="https://github.com/user-attachments/assets/f8731193-74a3-4f6a-a6e3-8ac121e97e45" />


**Every dealership and review update is reflected dynamically, fostering transparency and trust.**
<img width="1917" height="902" alt="admin_login" src="https://github.com/user-attachments/assets/79ed1eb5-d8cd-48dd-bd60-171f7e0eeea2" />
<img width="1900" height="907" alt="car_models" src="https://github.com/user-attachments/assets/74aaa4cf-75ec-48ad-b8e8-e3652232bbca" />
<img width="1918" height="908" alt="cars" src="https://github.com/user-attachments/assets/36534be5-024b-4042-820f-382db93b0a0d" />
<img width="1078" height="441" alt="image" src="https://github.com/user-attachments/assets/a3c281da-fea8-4fc8-914e-e8c6411f06cd" />


