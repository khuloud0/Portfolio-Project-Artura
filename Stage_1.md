# 🚀 Stage 1: Idea Development Documentation

## 1. Idea Brainstorming & Evaluation
During the initial brainstorming sessions, we analyzed several project concepts, weighing their strengths, weaknesses, and the engineering rationale for selection or rejection:

| Proposed Idea | Strengths | Weaknesses | Decision Logic |
| :--- | :--- | :--- | :--- |
| **Event & Billing Management** | Comprehensive operational tool. | High complexity in financial logic and user permissions. | **Rejected:** Building a secure financial engine requires a longer audit cycle than our MVP window allows. |
| **Mapping Beauty** | Innovative visual concept. | High latency risks due to heavy reliance on external map APIs. | **Rejected:** Creating a custom GIS-based archive would consume too much infrastructure time over features. |
| **Color Analysis** | High personalization potential. | Requires complex Machine Learning (ML) models for skin-tone accuracy. | **Rejected:** Technical risk in algorithm accuracy might compromise product stability for an MVP. |
| **Location-Based Reminder** | Solves a daily productivity problem. | High market saturation with many existing large-scale competitors. | **Rejected:** Our goal was to build a niche B2B solution with unique relational data challenges. |
| **Interior Design Platform** | **Provides fast, user-friendly interior design suggestions without requiring professional design knowledge, and style.** | Provides fast, user-friendly interior design suggestions without requiring professional design knowledge. | **Selected:** Provides fast, user-friendly interior design suggestions without requiring professional design knowledge. |

---

## 2. Selected Product Summary: Why Interior Design Platform?

### 🚩 The Problem
Users often struggle to quickly generate and visualize suitable interior design ideas for their spaces without relying on professional designers or time-consuming manual searching across multiple platforms.

### ⚙️ The Engineering Rationale
The Interior Design Suggestion Platform is designed as a structured decision-support system that transforms user inputs into relevant design outputs through a template-based recommendation engine.

From a software engineering perspective, it functions as follows:

* **Relational Complexity:** It manages relationships between room types, styles, colors, and design templates within a structured database to generate consistent and relevant outputs.
* **Data-Driven Search:** It implements a rule-based filtering system that matches user inputs with predefined design categories instead of relying on unstructured browsing.
* **Full-Stack Integration:** It connects a Flask backend with a lightweight frontend and a SQL database to deliver a smooth and responsive user experience.

### 🌟 Potential Impact
The platform simplifies the interior design process by transforming it into a fast, structured, and accessible digital experience, reducing the time and effort required for users to generate meaningful design ideas.

It also provides a scalable foundation for future enhancements such as AI-generated designs, 3D visualization, and personalized recommendation systems.


## 3. 🚀 Project Roadmap

### Stage 1: Idea Development (Completed) ✅
* Define project concept and problem statement.
* Identify target users and initial features.

### Stage 2: Project Charter Development 
* Define objectives, scope, stakeholders, and risks.
* Finalize project documentation.

### Stage 3: Technical Documentation 📝
* Design system architecture.
* Create database schema (SQL).
* Define Flask routes and system flow.

### Stage 4: MVP Development 🛠️
* Build backend using Flask and Python.
* Develop frontend.
* Implement design suggestion system.
* Integrate database with templates.
* Add **Save Design** feature with progressive authentication.

### Stage 5: Project Closure 🏁
* Testing and bug fixing.
* Final UI improvements.
* Prepare final presentation and demo.
* Submit documentation and project report.

### Visual Roadmap & Future Scope
| Phase | Focus Area |
| :--- | :--- |
| **Phase 1: MVP** | Interior Design Suggestion System (Form-based inputs, template matching, Flask + SQL backend, basic results generation) |
| **Phase 2: Expansion**| User Personalization (Save Designs, user dashboard, improved recommendation logic, richer design database, progressive authentication enhancement) |
| **Phase 3: Diversification** |AI-powered design generation, image-based room input, 3D visualization, and smart interior design ecosystem integration |

---

## 4. Team Composition & Initial Roles

### 👥 The Project Team
| Member | Role |
| :--- | :--- |
| **Khuloud Alqarni** | **Backend Lead** |
| **Raghad Nassef** | **Frontend Lead** |
| **Layan Aldosari** | **QA Lead** |
| **Banan Aleid** | **Database Lead** & **Project Manager**|

## 5. Technical Stack & Tools
The team has selected a modern and scalable technical stack to ensure the performance and reliability of the Artura platform.

### 🛠 Backend & Infrastructure 
* **Language:** Python 
* **Framework:** Flask (RESTful API)
* **Authentication:** JWT (JSON Web Tokens)
* **Documentation:** Swagger 

### 🗄 Persistence & Data 
* **Database:** PostgreSQL (Relational Database)
* **ORM:** SQLAlchemy (for efficient database interactions)
* **Modeling:** mermaid / MySQL Workbench (for ERD design)

### 🎨 Frontend & Design
* **Languages:** HTML5, CSS3, JavaScript, React
* **Styling:** Tailwind CSS 
* **Prototyping:** Figma
* **Libraries:** React

### 🚀 Collaboration & DevOps
* **IDE:** **Visual Studio Code (VS Code)**
* **Version Control:** Git & GitHub
* **Project Management:** Notion / GitHub Projects
* **Communication:** Slack / Zoom
