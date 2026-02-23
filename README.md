#  RSET Community Centre

> A full-stack anonymous campus community platform that centralizes student services — including query discussions, rental listings, structured feedback, and restaurant reviews — into a unified web application.

---

##  Problem Statement

Campus services such as student queries, feedback systems, housing information, and food reviews are typically scattered across multiple platforms, leading to inefficient communication and low engagement.

**RSET Community Centre** solves this by providing a centralized, privacy-focused system where users interact through anonymous aliases — keeping identity private while fostering open community engagement.

---

##  Tech Stack

| Layer | Technologies |
|-------|-------------|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | Node.js, Express.js |
| Database | MongoDB (NoSQL) |

---

##  Key Technical Highlights

- **Anonymous user architecture** — alias-based identity system
- **Modular full-stack design** — clean separation of concerns
- **Filter-based property search** implementation
- **Clean and responsive UI** across all modules

---

##  System Architecture

### 1️⃣ Authentication & Alias Layer

- Users create a unique alias upon registration
- All user-generated content is mapped to the alias
- Real identity is never exposed at the UI level
- Backend maintains internal user reference for data integrity

### 2️⃣ Core Modules

####  Query Hub
- Create, read, and store discussion posts
- Category-based classification
- MongoDB-based persistent storage

####  Home Renting Module
- Dynamic filtering by bedrooms and cost range
- Structured property schema
- Card-based responsive UI

####  Feedback System
- Semester-based structured submission
- Category classification: classes, professors, and facilities
- Stored and retrieved via MongoDB

####  Restaurant Review Module
- Restaurant metadata: cuisine, cost, and rating
- User rating & review submission
- Aggregated display logic

####  Contact Module
- Message submission form
- Backend request handling

---

## 📸 Screenshots

###  Login Page
![Login](miniproject/output%20ss/Login.png)

###  Home Dashboard
![Home](miniproject/output%20ss/Home.png)

###  Query Hub
![Query Hub](miniproject/output%20ss/6.jpg)

###  Home Renting Module
![Renting](miniproject/output%20ss/Home%20rent.png)

###  Feedback System
![Feedback 1](miniproject/output%20ss/feedback.png)
---
![Feedback 2](miniproject/output%20ss/feedback1.png)

###  Restaurant Review Module
![Reviews 1](miniproject/output%20ss/foodreview.png)
---
![Reviews 2](miniproject/output%20ss/foodreview1.png)

###  Contact Page
![Contact](miniproject/output%20ss/contact.png)

---

##  Scalability & Future Enhancements

- [ ] Comment threading system
- [ ] Admin dashboard & moderation tools
- [ ] Role-based access control
- [ ] Cloud deployment (AWS / Render / Heroku)
- [ ] REST API separation for mobile integration

---

##  Getting Started

```bash
# Clone the repository
git clone https://github.com/annette009/Mini_Project.git

# Navigate into the project
cd rset-community-centre

# Install dependencies
npm install

# Start the server
node server.js
```

> Make sure MongoDB is running locally or configure a connection string in your `.env` file.

---
